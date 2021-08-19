AUTOMAKE_OPTIONS = foreign
ACLOCAL_AMFLAGS = -I m4
SUBDIRS = src scripts man
EXTRA_DIST = LICENSE README.md

AM_LDFLAGS = -shared -O3

# Alias test target to make Travis CI happy
.PHONY: test
test: check
