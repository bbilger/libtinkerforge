## libtinkerforge:

AC_INIT([libtinkerforge], [1.0.0], [https://github.com/bbilger/libtinkerforge/issues], [tinkerforge], [https://github.com/bbilger/libtinkerforge])
AC_PREREQ([2.69])
AM_INIT_AUTOMAKE([-Wall no-define])

AC_CONFIG_HEADERS([config.h])
AC_PROG_CXX
LT_INIT([disable-static])

# API/ABI version, starting from C/C++ binding version 2.0.13
# for updating rules check:
# http://www.gnu.org/software/libtool/manual/libtool.html#Updating-version-info
# Library version should be increased upon binding version increase but
# has nothing to do with the binding version itself. Check binding 
# chengelog to decide what needs to be increased.
AC_SUBST([TINKERFORGE_SO_VERSION], [0:0:0])

# Multi Lib Version
# Should not be increased without good reason.
# (This version has nothing to do with the version defined in AC_INIT - the 
# package version - nor with the ABI/API version.)
AC_SUBST([TINKERFORGE_MULTI_LIB_VERSION], [1.0])

AC_CONFIG_FILES([Makefile
                 tinkerforge-${TINKERFORGE_MULTI_LIB_VERSION}.pc:tinkerforge.pc.in])
AC_OUTPUT
