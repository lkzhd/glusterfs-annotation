xlator_LTLIBRARIES = shard.la
xlatordir = $(libdir)/glusterfs/$(PACKAGE_VERSION)/xlator/features

shard_la_LDFLAGS = -module -avoid-version

shard_la_SOURCES = shard.c

shard_la_LIBADD = $(top_builddir)/libglusterfs/src/libglusterfs.la

noinst_HEADERS = shard.h shard-mem-types.h

AM_CPPFLAGS = $(GF_CPPFLAGS) -I$(top_srcdir)/libglusterfs/src

AM_CFLAGS = -Wall $(GF_CFLAGS)

CLEANFILES =
