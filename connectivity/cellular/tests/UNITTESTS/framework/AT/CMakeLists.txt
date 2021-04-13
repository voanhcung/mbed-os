# Copyright (c) 2021 ARM Limited. All rights reserved.
# SPDX-License-Identifier: Apache-2.0

list(APPEND MBED_ADD_UNITTEST_SUBDIRS
    at_cellularcontext
    at_cellulardevice
    at_cellularinformation
    at_cellularnetwork
    at_cellularsms
    at_cellularstack
)

mbed_add_all_subdirectories("${MBED_ADD_UNITTEST_SUBDIRS}")
