AC_PREREQ([2.65])
AC_INIT([csv_parser], [0.1.0], [vilkeliskis.t@gmail.com])
AC_CONFIG_AUX_DIR(config)
AC_CONFIG_MACRO_DIR(config)
AM_INIT_AUTOMAKE(tar-ustar dist-zip foreign subdir-objects)

# This lets us use PACKAGE_VERSION in Makefiles
AC_SUBST(PACKAGE_VERSION)

# Initialize libtool so we could build shared objects.
LT_INIT

# Checks for programs.
AC_PROG_CC

AC_CONFIG_FILES([Makefile src/Makefile tests/Makefile examples/Makefile])
AC_OUTPUT
