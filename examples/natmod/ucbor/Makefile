# Location of top-level MicroPython directory
MPY_DIR = ../../..

# Name of module
MOD = ucbor

TINYCBOR_SRC_DIR = ./tinycbor/src

CFLAGS += -I$(TINYCBOR_SRC_DIR)

# Source files (.c or .py)
SRC = ucbor.c \
		$(TINYCBOR_SRC_DIR)/cborencoder.c \
		$(TINYCBOR_SRC_DIR)/cborerrorstrings.c \
		$(TINYCBOR_SRC_DIR)/cborparser.c \
		$(TINYCBOR_SRC_DIR)/cborparser_dup_string.c

# Architecture to build for (x86, x64, armv7m, xtensa, xtensawin)
ARCH = x64

# Include to get the rules for compiling and linking the module
include $(MPY_DIR)/py/dynruntime.mk