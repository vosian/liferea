## Process this file with automake to produce Makefile.in
AM_CPPFLAGS = \
	-DPACKAGE_DATA_DIR=\""$(datadir)"\" \
	-DPACKAGE_LIB_DIR=\""$(pkglibdir)"\" \
	-DPACKAGE_LOCALE_DIR=\""$(prefix)/$(DATADIRNAME)/locale"\" \
	-I$(top_srcdir)/src

noinst_LIBRARIES = libligwget.a

libligwget_a_CFLAGS = $(PACKAGE_CFLAGS)
libligwget_a_SOURCES = \
	$(BUILT_SOURCES) \
	gwget_download_manager.c\
	gwget_download_manager.h\
	main_window_cb.c\
	main_window_cb.h\
	gwget_data.c\
	gwget_data.h\
	wget-log.c\
	wget-log.h\
	utils.c\
	utils.h\
	new_window.c\
	new_window.h\
	md5.h \
	md5.c
