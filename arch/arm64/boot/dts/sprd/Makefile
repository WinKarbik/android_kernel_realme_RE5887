# SPDX-License-Identifier: GPL-2.0

ifeq ($(BSP_BUILD_FAMILY),sharkl3)
dtbo-$(CONFIG_ARCH_SPRD) += \
	sp9863a-3h10-overlay.dtbo \
	sp9863a-1c10-overlay.dtbo \
	sp9863a-1h10-overlay.dtbo \
	sp9863a-1h10_go-overlay.dtbo

sp9863a-3h10-overlay.dtbo-base := sp9863a.dtb
sp9863a-1c10-overlay.dtbo-base := sp9863a.dtb
sp9863a-1h10-overlay.dtbo-base := sp9863a.dtb
sp9863a-1h10_go-overlay.dtbo-base := sp9863a.dtb
endif

ifeq ($(BSP_BUILD_FAMILY),sharkl5Pro)
dtbo-$(CONFIG_ARCH_SPRD) += \
	ums512-1h10-overlay.dtbo \
	ums512-1h10_go-overlay.dtbo \
	ums512-2h10-overlay.dtbo

ums512-1h10-overlay.dtbo-base := ums512.dtb
ums512-1h10_go-overlay.dtbo-base := ums512.dtb
ums512-2h10-overlay.dtbo-base := ums512.dtb
endif

ifeq ($(BSP_BUILD_FAMILY),sharkl5)
dtbo-$(CONFIG_ARCH_SPRD) += \
	ums312-1h10-overlay.dtbo \
	ums312-2h10-overlay.dtbo

ums312-1h10-overlay.dtbo-base := ums312.dtb
ums312-2h10-overlay.dtbo-base := ums312.dtb
endif

dtbo-$(CONFIG_ARCH_SPRD) += ums9230-haps-backdoor-overlay.dtbo \
	ums9230-haps-flash-overlay.dtbo \
	ums9230-zebu-backdoor-overlay.dtbo \
	ums9230-1h10-overlay.dtbo \
	ums9230-4h10-overlay.dtbo \
	RMX3506-overlay.dtbo \
	ums9230-4h10-go-overlay.dtbo \
	RMX3581-go-overlay.dtbo \
	ums9230-3h10-overlay.dtbo \
	ums9230-14c10-overlay.dtbo \
	ums9230-1h10-go2g-overlay.dtbo \
	ums9230-3h10-go-overlay.dtbo

ums9230-haps-backdoor-overlay.dtbo-base := ums9230-haps.dtb
ums9230-haps-flash-overlay.dtbo-base := ums9230-haps.dtb
ums9230-zebu-backdoor-overlay.dtbo-base := ums9230-zebu.dtb
ums9230-1h10-overlay.dtbo-base := ums9230.dtb
ums9230-4h10-overlay.dtbo-base := ums9230.dtb
RMX3506-overlay.dtbo-base := ums9230.dtb
ums9230-4h10-go-overlay.dtbo-base := ums9230.dtb
RMX3581-go-overlay.dtbo-base := ums9230.dtb
ums9230-3h10-overlay.dtbo-base := ums9230.dtb
ums9230-1h10-go2g-overlay.dtbo-base := ums9230.dtb
ums9230-3h10-go-overlay.dtbo-base := ums9230.dtb
ums9230-14c10-overlay.dtbo-base := ums9230.dtb

always		:= $(dtb-y) $(dtbo-y)
subdir-y	:= $(dts-dirs)
clean-files	:= *.dtb *.dtbo
