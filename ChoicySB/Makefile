INSTALL_TARGET_PROCESSES = SpringBoard

include $(THEOS)/makefiles/common.mk

TWEAK_NAME = ChoicySB

ChoicySB_FILES = $(wildcard *.x) $(wildcard *.m) ../Shared.m ../ChoicyPrefsMigrator.m
ChoicySB_CFLAGS = -fobjc-arc -Wno-unguarded-availability-new
ChoicySB_PRIVATE_FRAMEWORKS = BackBoardServices
ChoicySB_OBJ_FILES = $(THEOS)/vendor/lib/iphone/rootless/libroot.a

include $(THEOS_MAKE_PATH)/tweak.mk
