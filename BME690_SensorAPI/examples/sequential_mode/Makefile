COINES_INSTALL_PATH ?= ../../../..

EXAMPLE_FILE ?= sequential_mode.c

API_LOCATION ?= ../..

C_SRCS += \
$(API_LOCATION)/bme69x.c \
../common/common.c

INCLUDEPATHS += \
$(API_LOCATION) \
../common

COINES_BACKEND?=COINES_BRIDGE

include $(COINES_INSTALL_PATH)/coines.mk