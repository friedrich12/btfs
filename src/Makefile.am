EXTRACXXFLAGS = -std=c++14 \
                -Wall \
                -Wextra \
                -Wconversion \
                -Wsign-compare \
                -Wsign-conversion \
                -Wno-unused-parameter

AUTOMAKE_OPTIONS = subdir-objects
ACLOCAL_AMFLAGS = $(ACLOCAL_FLAGS)

lib_LTLIBRARIES=libbtfs.la
libbtfs_la_SOURCES= btfs.cc
libbtfs_la_CXXFLAGS= $(EXTRACXXFLAGS) $(FUSE_CFLAGS) $(LIBTORRENT_CFLAGS) $(LIBCURL_CFLAGS)
libbtfs_la_LIBADD = $(FUSE_LIBS) $(LIBTORRENT_LIBS) $(LIBCURL_LIBS)
