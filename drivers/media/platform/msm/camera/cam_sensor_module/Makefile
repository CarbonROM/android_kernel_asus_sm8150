obj-$(CONFIG_SPECTRA_CAMERA) += cam_res_mgr/
obj-$(CONFIG_SPECTRA_CAMERA) += cam_sensor_utils/
obj-$(CONFIG_SPECTRA_CAMERA) += cam_cci/
obj-$(CONFIG_SPECTRA_CAMERA) += cam_sensor_io/
obj-$(CONFIG_SPECTRA_CAMERA) += cam_csiphy/
obj-$(CONFIG_SPECTRA_CAMERA) += cam_actuator/
obj-$(CONFIG_SPECTRA_CAMERA) += cam_sensor/
obj-$(CONFIG_SPECTRA_CAMERA) += cam_flash/
obj-$(CONFIG_SPECTRA_CAMERA) += cam_eeprom/
obj-$(CONFIG_SPECTRA_CAMERA) += cam_ois/
ifeq ($(ASUS_FTM),y)
    subdir-ccflags-y += -DCAM_FACTORY_CONFIG
endif
obj-$(CONFIG_SPECTRA_CAMERA) += cam_ir_led/
