export ARCHS = arm64 arm64e
export CLI = 0
export TARGET = iphone:clang:14.5:15.0
export FINALPACKAGE=1
export THEOS_DEVICE_IP=192.168.1.113

include $(THEOS)/makefiles/common.mk

BUNDLE_NAME = Powercuff
Powercuff_FILES = Powercuff.m
Powercuff_CFLAGS = -fobjc-arc
Powercuff_FRAMEWORKS = UIKit
Powercuff_PRIVATE_FRAMEWORKS = ControlCenterUIKit
Powercuff_INSTALL_PATH = /Library/ControlCenter/Bundles/

include $(THEOS_MAKE_PATH)/bundle.mk
