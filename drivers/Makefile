# SPDX-License-Identifier: GPL-2.0
#
# Makefile for the input core drivers and stuff
#

# Each configuration option enables a list of files.

obj-$(CONFIG_INPUT)		+= input-core.o
input-core-y := input.o input-compat.o input-mt.o input-poller.o ff-core.o

obj-$(CONFIG_INPUT_FF_MEMLESS)	+= ff-memless.o
obj-$(CONFIG_INPUT_SPARSEKMAP)	+= sparse-keymap.o
obj-$(CONFIG_INPUT_MATRIXKMAP)	+= matrix-keymap.o

obj-$(CONFIG_INPUT_LEDS)	+= input-leds.o
obj-$(CONFIG_INPUT_MOUSEDEV)	+= mousedev.o
obj-$(CONFIG_INPUT_JOYDEV)	+= joydev.o
obj-$(CONFIG_INPUT_EVDEV)	+= evdev.o
obj-$(CONFIG_INPUT_EVBUG)	+= evbug.o

obj-$(CONFIG_INPUT_MOUSE)	+= mouse/
obj-$(CONFIG_INPUT_TOUCHSCREEN)	+= touchscreen/

obj-$(CONFIG_INPUT_APMPOWER)	+= apm-power.o

#
# GPIO
#

obj-$(CONFIG_IO_GPIO) += gpio/

#
# Emerald OS stuff
#

obj-$(CONFIG_OUTPUT_VIDEO) += video/
obj-$(CONFIG_INPUT_KEYOBOARD) += keyboard/
obj-$(CONFIG_IO_SERIAL) += serial/
