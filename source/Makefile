PROJECT = blink
BUILD_DIR = bin

# SHARED_DIR = ../my-common-code
# AFILES += api-asm.S
# CFILES += api.c
CFILES = main.c



# TODO - you will need to edit these two lines!
DEVICE = lm4f120xl
LDSCRIPT = ../platform/core/ek-lm4f120xl.ld
# OOCD_FILE = board/stm32f4discovery.cfg

# You shouldn't have to edit anything below here.
VPATH += $(SHARED_DIR)
INCLUDES += $(patsubst %,-I%, . $(SHARED_DIR))
OPENCM3_DIR=../platform/core/libopencm3

include $(OPENCM3_DIR)/mk/genlink-config.mk
include ../rules.mk
include $(OPENCM3_DIR)/mk/genlink-rules.mk
