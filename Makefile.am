EXTRA_LTLIBRARIES =
bin_PROGRAMS =
bin_SCRIPTS =
check_PROGRAMS =
lib_LTLIBRARIES =
man1_MANS =
nobase_dist_pkgdata_DATA =
nobase_lib_LTLIBRARIES =
noinst_LIBRARIES =
noinst_LTLIBRARIES =
noinst_PROGRAMS =
noinst_SCRIPTS =

TESTS = $(check_PROGRAMS)

AM_CPPFLAGS = -I$(srcdir) -I.
AM_CFLAGS = -g -Wall -march=native
AM_CXXFLAGS = -g -Wall -march=native
AM_LDFLAGS = -lpthread

ACLOCAL_AMFLAGS = -I m4

include $(srcdir)/base/Makefile.am
include $(srcdir)/index/Makefile.am
include $(srcdir)/tools/text-classifier/Makefile.am
