# Location of top-level MicroPython directory
MPY_DIR = ../micropython

# Name of module
MOD = usbkeyboard

# Source files (.c or .py)
SRC = main.c

# Architecture to build for (x86, x64, armv7m, xtensa, xtensawin)
ARCH = xtensawin

# Include to get the rules for compiling and linking the module
include $(MPY_DIR)/py/dynruntime.mk

all: $(MOD).mpy
	cp $(MOD).mpy ..