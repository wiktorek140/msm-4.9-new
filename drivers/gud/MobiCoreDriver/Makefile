#/*
# * Copyright (c) 2013-2018 TRUSTONIC LIMITED
# * All Rights Reserved.
# *
# * This program is free software; you can redistribute it and/or
# * modify it under the terms of the GNU General Public License
# * version 2 as published by the Free Software Foundation.
# *
# * This program is distributed in the hope that it will be useful,
# * but WITHOUT ANY WARRANTY; without even the implied warranty of
# * MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the
# * GNU General Public License for more details.
# */
#
# Makefile for the Kinibi core driver
#

# add -Wall to try to catch everything we can.
EXTRA_CFLAGS += -Wall
EXTRA_CFLAGS += -DNDEBUG
EXTRA_CFLAGS +=  -Wno-declaration-after-statement

mcDrvModule-objs := \
	admin.o \
	client.o \
	clientlib.o \
	clock.o \
	fastcall.o \
	iwp.o \
	logging.o \
	main.o \
	mcp.o \
	mmu.o \
	nq.o \
	pm.o \
	scheduler.o \
	session.o \
	teeclientapi.o \
	user.o

obj-$(CONFIG_TEE_MOBICORE) += mcDrvModule.o