AC_PREREQ(2.59)
AC_COPYRIGHT([none])
AC_INIT([libshout_aac], [1])
AC_CONFIG_MACRO_DIR([m4])
AC_CONFIG_SRCDIR(aac.c)
AM_CONFIG_HEADER(config.h)

AC_CANONICAL_SYSTEM
AC_LANG(C)

AM_INIT_AUTOMAKE

C_GNU_SOURCE
AC_PROG_CC
AC_PROG_CC_STDC
AC_PROG_INSTALL
AC_PROG_LIBTOOL

AC_ARG_VAR([PLUGIN_DIR], [plugin installation directory])
if test "x$PLUGIN_DIR" = x; then
	AC_MSG_FAILURE([Can't determine plugin installation directory])
fi

AC_ARG_VAR([SHOUTSRC], [libshout source directory])
if test "x$SHOUTSRC" = x; then
	AC_MSG_FAILURE([Can't determine libshout source directory])
fi


AC_CONFIG_FILES([Makefile])
AC_OUTPUT
