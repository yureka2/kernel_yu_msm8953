#
# Makefile for the QCOM specific video device drivers
# based on V4L2.
#
obj-$(CONFIG_MSM_VIDC_V4L2) += vidc/
obj-y += broadcast/
obj-$(CONFIG_DVB_MPQ) += dvb/
ifeq ($(CONFIG_MACH_CMCC_MSM8953),y)
obj-$(CONFIG_MSMB_CAMERA) += camera_v2_markw/
else
obj-$(CONFIG_MSMB_CAMERA) += camera_v2/
endif
obj-y += sde/