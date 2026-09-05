ifeq ($(CONFIG_BUILD_ARM64_DT_OVERLAY),y)
        dtbo-$(CONFIG_ARCH_KONA) += \
# BAILINT-TRIM:                 kona-cdp-overlay.dtbo \
# BAILINT-TRIM:                 kona-cdp-lcd-overlay.dtbo \
# BAILINT-TRIM:                 kona-mtp-overlay.dtbo \
# BAILINT-TRIM:                 kona-mtp-ws-overlay.dtbo \
# BAILINT-TRIM:                 kona-xr-overlay.dtbo \
# BAILINT-TRIM:                 kona-rumi-overlay.dtbo \
# BAILINT-TRIM:                 kona-qrd-overlay.dtbo \
# BAILINT-TRIM: 		kona-xrfusion-overlay.dtbo \
# BAILINT-TRIM:                 kona-hdk-overlay.dtbo

kona-cdp-overlay.dtbo-base := kona.dtb kona-v2.dtb kona-v2.1.dtb
kona-cdp-lcd-overlay.dtbo-base := kona.dtb kona-v2.dtb kona-v2.1.dtb
kona-mtp-overlay.dtbo-base := kona.dtb kona-v2.dtb kona-v2.1.dtb
kona-mtp-ws-overlay.dtbo-base := kona.dtb kona-v2.dtb kona-v2.1.dtb
kona-xr-overlay.dtbo-base := kona.dtb kona-v2.dtb kona-v2.1.dtb
kona-rumi-overlay.dtbo-base := kona.dtb kona-v2.dtb kona-v2.1.dtb
kona-qrd-overlay.dtbo-base := kona.dtb kona-v2.dtb kona-v2.1.dtb
kona-xrfusion-overlay.dtbo-base := kona.dtb kona-v2.dtb kona-v2.1.dtb
kona-hdk-overlay.dtbo-base := kona.dtb kona-v2.dtb kona-v2.1.dtb

else
dtb-$(CONFIG_ARCH_KONA) += kona-rumi.dtb \
# BAILINT-TRIM:         kona-mtp.dtb \
# BAILINT-TRIM:         kona-mtp-ws.dtb \
# BAILINT-TRIM:         kona-xr.dtb \
# BAILINT-TRIM: 	kona-xrfusion.dtb \
# BAILINT-TRIM:         kona-cdp.dtb \
# BAILINT-TRIM:         kona-cdp-lcd.dtb \
# BAILINT-TRIM:         kona-qrd.dtb \
# BAILINT-TRIM:         kona-v2-rumi.dtb \
# BAILINT-TRIM:         kona-v2-mtp.dtb \
# BAILINT-TRIM:         kona-v2-mtp-ws.dtb \
# BAILINT-TRIM:         kona-v2-cdp.dtb \
# BAILINT-TRIM:         kona-v2-qrd.dtb \
# BAILINT-TRIM: 	kona-v2-xrfusion.dtb \
# BAILINT-TRIM:         kona-hdk.dtb \
# BAILINT-TRIM:         kona-v2.1-mtp.dtb \
# BAILINT-TRIM:         kona-v2.1-mtp-ws.dtb \
# BAILINT-TRIM:         kona-v2.1-cdp.dtb \
# BAILINT-TRIM:         kona-v2.1-qrd.dtb \
# BAILINT-TRIM:         kona-v2.1-hdk.dtb \
# BAILINT-TRIM: 	kona-v2.1-xrfusion.dtb
endif

ifeq ($(CONFIG_BUILD_ARM64_DT_OVERLAY_NOT_OEM),y)
dtbo-$(CONFIG_ARCH_LITO) += lito-rumi-overlay.dtbo \
                lito-mtp-overlay.dtbo \
                lito-v2-mtp-overlay.dtbo \
                lito-cdp-overlay.dtbo \
                lito-v2-cdp-overlay.dtbo \
                lito-atp-overlay.dtbo \
                lito-v2-atp-overlay.dtbo \
                lito-v2-atp-lcd-overlay.dtbo \
                lito-qrd-overlay.dtbo \
                lito-v2-qrd-overlay.dtbo

lito-rumi-overlay.dtbo-base := lito.dtb lito-v2.dtb
lito-mtp-overlay.dtbo-base := lito.dtb
lito-v2-mtp-overlay.dtbo-base := lito-v2.dtb
lito-cdp-overlay.dtbo-base := lito.dtb
lito-v2-cdp-overlay.dtbo-base := lito-v2.dtb
lito-atp-overlay.dtbo-base := lito.dtb
lito-v2-atp-overlay.dtbo-base := lito-v2.dtb
lito-v2-atp-lcd-overlay.dtbo-base := lito-v2.dtb
lito-qrd-overlay.dtbo-base := lito.dtb
lito-v2-qrd-overlay.dtbo-base := lito-v2.dtb

else
ifeq ($(CONFIG_BUILD_ARM64_DT_OVERLAY),y)
        dtbo-$(CONFIG_ARCH_LITO) += \
                avicii-overlay-dvt.dtbo \
                avicii-overlay-dvt-v2.1.dtbo \
                avicii-overlay-pvt.dtbo \
                avicii-overlay-pvt-v2.1.dtbo

avicii-overlay-dvt.dtbo-base := lito.dtb
avicii-overlay-dvt-v2.1.dtbo-base := lito.dtb
avicii-overlay-pvt.dtbo-base := lito.dtb
avicii-overlay-pvt-v2.1.dtbo-base := lito.dtb

else
dtb-$(CONFIG_ARCH_LITO) += lito-rumi.dtb \
                lito-mtp.dtb \
                lito-cdp.dtb \
                lito-atp.dtb \
                lito-qrd.dtb \
                lito-v2-mtp.dtb \
                lito-v2-cdp.dtb \
                lito-v2-atp.dtb \
                lito-v2-atp-lcd.dtb \
                lito-v2-qrd.dtb
endif
endif

ifeq ($(CONFIG_BUILD_ARM64_DT_OVERLAY),y)
dtbo-$(CONFIG_ARCH_LAGOON) += \
# BAILINT-TRIM: 		lagoon-rumi-overlay.dtbo \
# BAILINT-TRIM: 		lagoon-mtp-overlay.dtbo \
# BAILINT-TRIM: 		lagoon-mtp-usbc-overlay.dtbo \
# BAILINT-TRIM: 		lagoon-cdp-overlay.dtbo \
# BAILINT-TRIM: 		lagoon-atp-overlay.dtbo \
# BAILINT-TRIM: 		lagoon-qrd-overlay.dtbo

lagoon-rumi-overlay.dtbo-base := lagoon.dtb
lagoon-mtp-overlay.dtbo-base := lagoon.dtb
lagoon-mtp-usbc-overlay.dtbo-base := lagoon.dtb
lagoon-cdp-overlay.dtbo-base := lagoon.dtb
lagoon-atp-overlay.dtbo-base := lagoon.dtb
lagoon-qrd-overlay.dtbo-base := lagoon.dtb
else
dtb-$(CONFIG_ARCH_LAGOON) += \
# BAILINT-TRIM: 		lagoon-rumi.dtb \
# BAILINT-TRIM: 		lagoon-mtp.dtb \
# BAILINT-TRIM: 		lagoon-mtp-usbc.dtb \
# BAILINT-TRIM: 		lagoon-cdp.dtb \
# BAILINT-TRIM: 		lagoon-atp.dtb \
# BAILINT-TRIM: 		lagoon-qrd.dtb
endif

ifeq ($(CONFIG_BUILD_ARM64_DT_OVERLAY),y)
        dtbo-$(CONFIG_ARCH_BENGAL) += \
# BAILINT-TRIM:                 bengal-rumi-overlay.dtbo \
# BAILINT-TRIM:                 bengal-qrd-overlay.dtbo \
# BAILINT-TRIM:                 bengal-idp-overlay.dtbo \
# BAILINT-TRIM:                 bengal-idp-usbc-overlay.dtbo \
# BAILINT-TRIM:                 bengalp-idp-overlay.dtbo

bengal-rumi-overlay.dtbo-base := bengal.dtb
bengal-qrd-overlay.dtbo-base := bengal.dtb
bengal-idp-overlay.dtbo-base := bengal.dtb
bengal-idp-usbc-overlay.dtbo-base := bengal.dtb
bengalp-idp-overlay.dtbo-base := bengalp.dtb
else
dtb-$(CONFIG_ARCH_BENGAL) += bengal-rumi.dtb \
# BAILINT-TRIM:                 bengal-qrd.dtb \
# BAILINT-TRIM: 		bengal-idp.dtb \
# BAILINT-TRIM: 		bengal-idp-usbc.dtb \
# BAILINT-TRIM: 		bengalp-idp.dtb
endif

ifeq ($(CONFIG_BUILD_ARM64_DT_OVERLAY),y)
        dtbo-$(CONFIG_ARCH_SCUBA) += \
# BAILINT-TRIM:                 scuba-rumi-overlay.dtbo \
# BAILINT-TRIM:                 scuba-idp-overlay.dtbo

scuba-rumi-overlay.dtbo-base := scuba.dtb
scuba-idp-overlay.dtbo-base := scuba.dtb
else
dtb-$(CONFIG_ARCH_SCUBA) += scuba-rumi.dtb \
# BAILINT-TRIM: 	scuba-idp.dtb
endif

always		:= $(dtb-y)
subdir-y	:= $(dts-dirs)
# BAILINT-TRIM: clean-files    := *.dtb *.dtbo
