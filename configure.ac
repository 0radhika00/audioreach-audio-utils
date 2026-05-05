# Process this file with autoconf to produce a configure script

AC_PREREQ([2.69])
AC_INIT([audioreach-audio-utils], [1.0.0])
AM_INIT_AUTOMAKE([foreign])

AC_CONFIG_SRCDIR([README.md])
AC_CONFIG_AUX_DIR([build-aux])

# Keep top-level configure lightweight and defer actual builds to subprojects.
AC_CONFIG_SUBDIRS([
        audio-route
        audio-plugins/audio-plugin-headers
        audio-plugins/dac_plugin
        audio-plugins/mercury_plugin
])

AC_CONFIG_FILES([Makefile])
AC_OUTPUT

