AC_INIT([cedit], [1.0])                                                                                                                 
AM_INIT_AUTOMAKE([foreign])
AC_CONFIG_SRCDIR([cedit.c])
AC_CONFIG_HEADERS([config.h])

# Checks for programs.
AC_PROG_CC

# Common compiler flags
CFLAGS = "-Wall -O2"

# Checks for libraries.
AC_CHECK_LIB([ncurses], [initscr])

# Checks for typedefs, structures, and compiler characteristics.
AC_CHECK_HEADER_STDBOOL

# Checks for header files.
AC_CHECK_HEADERS([stdlib.h string.h termios.h])

AC_CONFIG_FILES([Makefile])
AC_OUTPUT
