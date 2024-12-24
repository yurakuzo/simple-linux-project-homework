bin_PROGRAMS = simple_program
simple_program_SOURCES = main.c func.c
simple_program_CPPFLAGS = -I$(top_srcdir)/src

install-data-local:
	$(INSTALL) -m 644 $(top_srcdir)/src/header.h $(DESTDIR)$(includedir)

uninstall-local:
	rm -f $(DESTDIR)$(includedir)/header.h

