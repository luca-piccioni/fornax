
AC_INIT([fornax], [0.1])
AC_CONFIG_HEADERS(config.h)
AC_CONFIG_MACRO_DIR([m4])
AC_CONFIG_SRCDIR([fornax/fornax.cpp])
AM_INIT_AUTOMAKE

: ${CXXFLAGS=""}
AC_PROG_CXX([C++])
AX_CXX_COMPILE_STDCXX_11

AC_ARG_ENABLE([debug], AC_HELP_STRING([--enable-debug], [Enable debug compilation]), [enable_debug=true], [enable_debug=false])

AM_CONDITIONAL([DEBUG], [test x"$enable_debug" = x"true"])

AC_CONFIG_FILES([Makefile])
AC_CONFIG_FILES([fornax/Makefile])

AC_OUTPUT
