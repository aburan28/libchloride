
AM_CPPFLAGS = \
	-Ilibcurvecp

LDADD = \
	libcurvecp/libcurvecp.la

bin_PROGRAMS = \
	curvecpprintkey \
	curvecpmakekey \
	curvecpclient \
	curvecpserver \
	curvecpmessage

curvecpprintkey_SOURCES = \
	curvecpprintkey.c

curvecpmakekey_SOURCES = \
	curvecpmakekey.c

curvecpclient_SOURCES = \
	curvecpclient.c

curvecpserver_SOURCES = \
	curvecpserver.c

curvecpmessage_SOURCES = \
	curvecpmessage.c

EXTRA_DIST = \
	README

SUBDIRS = \
	libcurvecp
