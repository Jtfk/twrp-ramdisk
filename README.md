#### TWRP-ramdisk
Flags used to compile

DEVICE_RESOLUTION := 480x800  
RECOVERY_GRAPHICS_USE_LINELENGTH := true  
TW_HAS_NO_RECOVERY_PARTITION := true  
TW_FLASH_FROM_STORAGE := true  
TW_INTERNAL_STORAGE_PATH := "/storage/sdcard0"  
TW_INTERNAL_STORAGE_MOUNT_POINT := "sdcard0"  
TW_EXTERNAL_STORAGE_PATH := "/storage/sdcard1"  
TW_EXTERNAL_STORAGE_MOUNT_POINT := "sdcard1"  
TW_INCLUDE_JB_CRYPTO := true  
TW_CRYPTO_FS_TYPE := "ext4"  
TW_CRYPTO_REAL_BLKDEV := "/dev/block/mmcblk0p5"  
TW_CRYPTO_MNT_POINT := "/data"  
TW_CRYPTO_FS_OPTIONS := "noatime,nosuid,nodev,discard,noauto_da_alloc,journal_async_commit,errors=panic wait,check"  
TW_CRYPTO_FS_FLAGS := "0x00000406"  
TW_CRYPTO_KEY_LOC := "/efs/metadata"  
TW_INCLUDE_FUSE_EXFAT := true  
TW_BOARD_CUSTOM_GRAPHICS := ../../../device/samsung/u8500-common/recovery/twrp-graphics.c  
TW_BRIGHTNESS_PATH := /sys/class/backlight/panel/brightness  
TW_MAX_BRIGHTNESS := 255  
TW_NO_USB_STORAGE := true  
TW_NO_REBOOT_BOOTLOADER := true  
TW_HAS_DOWNLOAD_MODE := true  
TW_THEME := portrait_mdpi  
TW_EXCLUDE_SUPERSU := true  
TW_NO_CPU_TEMP := true  
