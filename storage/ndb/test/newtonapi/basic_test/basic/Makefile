include .defs.mk

TYPE := ndbapitest

BIN_TARGET := newton_basic
BIN_TARGET_LIBS :=
BIN_TARGET_ARCHIVES := NEWTON_BASICTEST_COMMON NEWTON_API
SOURCES    := basic.cpp

CCFLAGS_LOC := -I.. -I$(call fixpath,$(NDB_TOP)/include/util) -I$(call fixpath,$(NDB_TOP)/include/newtonapi) -I$(call fixpath,$(NDB_TOP)/include/portlib)

include $(NDB_TOP)/Epilogue.mk


