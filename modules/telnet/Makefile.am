SUBDIRS = . tests

pkgdatadir = @ZORP_PYTHON_DIR@
pkglibdir = @zorp_libdir@

LIBS     = @MODULES_LIBS@
CPPFLAGS = @MODULES_CPPFLAGS@


pkgdata_DATA = Telnet.py

pkglib_LTLIBRARIES = libtelnet.la

libtelnet_la_SOURCES = telnet.cc telnetpolicy.cc telnetsuboption.cc telnet.h telnetpolicy.h telnetsuboption.h telnettls.cc telnettls.h telnetprotocol.cc telnetprotocol.h telnetstate.cc telnetstate.h telnetlineedit.cc telnetlineedit.h telnetoption.cc telnetoption.h

EXTRA_DIST = $(pkgdata_DATA) 
