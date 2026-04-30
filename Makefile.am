AUTOMAKE_OPTIONS = foreign
hwprojdir = $(includedir)/hwprojdir
bin_PROGRAMS = hwproj
hwproj_SOURCES = main.c func.c
hwproj_HEADERS = header.h

.PHONY: clean-all
clean-all: maintainer-clean uninstall
	rm -rf aclocal.m4 autom4te.cache configure install-sh missing Makefile.in
