# Makefile for acct_gather_interconnect/none plugin

AUTOMAKE_OPTIONS = foreign

PLUGIN_FLAGS = -module -avoid-version --export-dynamic

AM_CPPFLAGS = -DSLURM_PLUGIN_DEBUG -I$(top_srcdir) -I$(top_srcdir)/src/common

pkglib_LTLIBRARIES = acct_gather_interconnect_none.la

# Null job completion logging plugin.
acct_gather_interconnect_none_la_SOURCES = acct_gather_interconnect_none.c

acct_gather_interconnect_none_la_LDFLAGS = $(PLUGIN_FLAGS)

