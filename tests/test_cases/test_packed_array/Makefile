# Copyright cocotb contributors
# Licensed under the Revised BSD License, see LICENSE for details.
# SPDX-License-Identifier: BSD-3-Clause

PWD=$(shell pwd)

VERILOG_SOURCES = $(PWD)/packed_array.sv

COCOTB_TEST_MODULES = test_packed_array

ifeq ($(SIM), verilator)
	EXTRA_ARGS = "--timing"
endif

include $(shell cocotb-config --makefiles)/Makefile.sim
