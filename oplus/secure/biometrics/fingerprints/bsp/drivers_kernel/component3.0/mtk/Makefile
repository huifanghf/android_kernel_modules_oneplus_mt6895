obj-$(CONFIG_OPLUS_FINGERPRINT_COMMON) += oplus_fp_common/

### Capacitive fingerprint sensor
# Mediatek not need it

### Optical fingerprint sensor
ifneq ($(CONFIG_OPLUS_FINGERPRINT_GOODIX)_$(CONFIG_OPLUS_FINGERPRINT_GOODIX_OPTICAL), _)
obj-y += goodix_optical_fp/
endif
obj-$(CONFIG_OPLUS_FINGERPRINT_JIIOV_OPTICAL)  += anc_driver/

### FEATURE MACRO
ccflags-$(CONFIG_OPLUS_FINGERPRINT_NAVIGATION_ENABLE) += -DFP_NAVIGATION_ENABLE
