AUTOMAKE_OPTIONS = foreign
SUBDIRS = src scripts man
EXTRA_DIST = LICENSE README.md

lib_LTLIBRARIES=libbtfs.la
libbtfs_la_SOURCES=SUBDIRS
#libbtfs_la_CFLAGS=-fPIC
#libbtfs_la_CPPFLAGS=-fPIC -Wc++11-extensions
libbtfs_la_CXXFLAGS=-fPIC -Wc++11-extensions
libbtfs_la_LDFLAGS= -shared -fPIC
libtest_la_LDFLAGS = -module -avoid-version -export-dynamic

# Alias test target to make Travis CI happy
.PHONY: test
test: check
