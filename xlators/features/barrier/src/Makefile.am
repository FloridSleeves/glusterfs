xlator_LTLIBRARIES = barrier.la
xlatordir = $(libdir)/glusterfs/$(PACKAGE_VERSION)/xlator/features

barrier_la_LDFLAGS = -module $(GF_XLATOR_DEFAULT_LDFLAGS)

barrier_la_SOURCES = barrier.c

barrier_la_LIBADD = $(top_builddir)/libglusterfs/src/libglusterfs.la

noinst_HEADERS = barrier.h barrier-mem-types.h

AM_CPPFLAGS = $(GF_CPPFLAGS) -I$(top_srcdir)/libglusterfs/src \
	-I$(top_srcdir)/rpc/xdr/src -I$(top_builddir)/rpc/xdr/src

AM_CFLAGS = -Wall $(GF_CFLAGS)

CLEANFILES =
