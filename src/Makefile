# Author: crifan
# Date: 2012-05-16
#
# -----------------------------------------------------------------
#  generate output from DocBook sources
#  this is entry makefile for docbook
# -----------------------------------------------------------------
# run this makefile under src directory:
# [office]
# pwd = /home/CLi/develop/docbook/books/xxx/src
# [home]
# pwd = /cygdrive/e/Dev_Root/docbook/dev/books/xxx/src

################################################################################
# Project Settings
################################################################################

# also means main source file name
PROJECT_NAME = uboot_starts_analysis
SUB_SRC_FILES = \
    preface.xml \
    ch01_starts_explanation.xml \
    ch01s1_set_cpu_mode.xml \
    ch01s2_close_watchdog.xml \
    ch01s3_disable_interrupt.xml \
    ch01s4_setup_stack_pointer.xml \
    ch01s5_clear_bss.xml \
    ch01s6_handle_exception.xml \
    ch02_starts_summary.xml \
    ch03_related_knowledge.xml \
    reference.xml \

DOCBOOK_MAKEFILE_ROOT = ../../../config
################################################################################
# Include docbook makefile
################################################################################
include $(DOCBOOK_MAKEFILE_ROOT)/docbook.mk