##===- lib/Target/SystemZ/Makefile ---------------------------*- Makefile -*-===##
#
#                     The LLVM Compiler Infrastructure
#
# This file is distributed under the University of Illinois Open Source
# License. See LICENSE.TXT for details.
#
##===----------------------------------------------------------------------===##

LEVEL = ../../..
LIBRARYNAME = LLVMSystemZCodeGen
TARGET = SystemZ

# Make sure that tblgen is run, first thing.
BUILT_SOURCES = SystemZGenRegisterInfo.inc SystemZGenInstrInfo.inc \
		SystemZGenAsmWriter.inc SystemZGenDAGISel.inc \
		SystemZGenSubtargetInfo.inc SystemZGenCallingConv.inc

DIRS = TargetInfo MCTargetDesc

include $(LEVEL)/Makefile.common

