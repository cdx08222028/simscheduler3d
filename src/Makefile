# Makefile.in generated by automake 1.11.6 from Makefile.am.
# src/Makefile.  Generated from Makefile.in by configure.

# Copyright (C) 1994, 1995, 1996, 1997, 1998, 1999, 2000, 2001, 2002,
# 2003, 2004, 2005, 2006, 2007, 2008, 2009, 2010, 2011 Free Software
# Foundation, Inc.
# This Makefile.in is free software; the Free Software Foundation
# gives unlimited permission to copy and/or distribute it,
# with or without modifications, as long as this notice is preserved.

# This program is distributed in the hope that it will be useful,
# but WITHOUT ANY WARRANTY, to the extent permitted by law; without
# even the implied warranty of MERCHANTABILITY or FITNESS FOR A
# PARTICULAR PURPOSE.





am__make_dryrun = \
  { \
    am__dry=no; \
    case $$MAKEFLAGS in \
      *\\[\ \	]*) \
        echo 'am--echo: ; @echo "AM"  OK' | $(MAKE) -f - 2>/dev/null \
          | grep '^AM OK$$' >/dev/null || am__dry=yes;; \
      *) \
        for am__flg in $$MAKEFLAGS; do \
          case $$am__flg in \
            *=*|--*) ;; \
            *n*) am__dry=yes; break;; \
          esac; \
        done;; \
    esac; \
    test $$am__dry = yes; \
  }
pkgdatadir = $(datadir)/simscheduler
pkgincludedir = $(includedir)/simscheduler
pkglibdir = $(libdir)/simscheduler
pkglibexecdir = $(libexecdir)/simscheduler
am__cd = CDPATH="$${ZSH_VERSION+.}$(PATH_SEPARATOR)" && cd
install_sh_DATA = $(install_sh) -c -m 644
install_sh_PROGRAM = $(install_sh) -c
install_sh_SCRIPT = $(install_sh) -c
INSTALL_HEADER = $(INSTALL_DATA)
transform = $(program_transform_name)
NORMAL_INSTALL = :
PRE_INSTALL = :
POST_INSTALL = :
NORMAL_UNINSTALL = :
PRE_UNINSTALL = :
POST_UNINSTALL = :
bin_PROGRAMS = SimScheduler$(EXEEXT) $(am__EXEEXT_1)
subdir = src
DIST_COMMON = $(dist_data_DATA) $(srcdir)/Makefile.am \
	$(srcdir)/Makefile.in
ACLOCAL_M4 = $(top_srcdir)/aclocal.m4
am__aclocal_m4_deps = $(top_srcdir)/configure.ac
am__configure_deps = $(am__aclocal_m4_deps) $(CONFIGURE_DEPENDENCIES) \
	$(ACLOCAL_M4)
mkinstalldirs = $(install_sh) -d
CONFIG_HEADER = $(top_builddir)/config.h
CONFIG_CLEAN_FILES =
CONFIG_CLEAN_VPATH_FILES =
#am__EXEEXT_1 = tinyqueue$(EXEEXT) tinylist$(EXEEXT) \
#	tinyprioq$(EXEEXT) tinyoq$(EXEEXT)
am__installdirs = "$(DESTDIR)$(bindir)" "$(DESTDIR)$(datadir)"
PROGRAMS = $(bin_PROGRAMS)
am__SimScheduler_SOURCES_DIST = main.c processlist.c tinyoq.c \
	tinylist.c process.c schedsys.c schedsysgl.c
am__objects_1 = SimScheduler-schedsysgl.$(OBJEXT)
am_SimScheduler_OBJECTS = SimScheduler-main.$(OBJEXT) \
	SimScheduler-processlist.$(OBJEXT) \
	SimScheduler-tinyoq.$(OBJEXT) SimScheduler-tinylist.$(OBJEXT) \
	SimScheduler-process.$(OBJEXT) SimScheduler-schedsys.$(OBJEXT) \
	$(am__objects_1)
SimScheduler_OBJECTS = $(am_SimScheduler_OBJECTS)
SimScheduler_LDADD = $(LDADD)
SimScheduler_LINK = $(CCLD) $(SimScheduler_CFLAGS) $(CFLAGS) \
	$(SimScheduler_LDFLAGS) $(LDFLAGS) -o $@
am_tinylist_OBJECTS = tinylist-tinylist.$(OBJEXT)
tinylist_OBJECTS = $(am_tinylist_OBJECTS)
tinylist_LDADD = $(LDADD)
tinylist_LINK = $(CCLD) $(tinylist_CFLAGS) $(CFLAGS) $(AM_LDFLAGS) \
	$(LDFLAGS) -o $@
am_tinyoq_OBJECTS = tinyoq-tinyoq.$(OBJEXT)
tinyoq_OBJECTS = $(am_tinyoq_OBJECTS)
tinyoq_LDADD = $(LDADD)
tinyoq_LINK = $(CCLD) $(tinyoq_CFLAGS) $(CFLAGS) $(AM_LDFLAGS) \
	$(LDFLAGS) -o $@
am_tinyprioq_OBJECTS = tinyprioq-tinyprioq.$(OBJEXT)
tinyprioq_OBJECTS = $(am_tinyprioq_OBJECTS)
tinyprioq_LDADD = $(LDADD)
tinyprioq_LINK = $(CCLD) $(tinyprioq_CFLAGS) $(CFLAGS) $(AM_LDFLAGS) \
	$(LDFLAGS) -o $@
am_tinyqueue_OBJECTS = tinyqueue-tinyqueue.$(OBJEXT)
tinyqueue_OBJECTS = $(am_tinyqueue_OBJECTS)
tinyqueue_LDADD = $(LDADD)
tinyqueue_LINK = $(CCLD) $(tinyqueue_CFLAGS) $(CFLAGS) $(AM_LDFLAGS) \
	$(LDFLAGS) -o $@
DEFAULT_INCLUDES = -I. -I$(top_builddir)
depcomp = $(SHELL) $(top_srcdir)/depcomp
am__depfiles_maybe = depfiles
am__mv = mv -f
COMPILE = $(CC) $(DEFS) $(DEFAULT_INCLUDES) $(INCLUDES) $(AM_CPPFLAGS) \
	$(CPPFLAGS) $(AM_CFLAGS) $(CFLAGS)
CCLD = $(CC)
LINK = $(CCLD) $(AM_CFLAGS) $(CFLAGS) $(AM_LDFLAGS) $(LDFLAGS) -o $@
SOURCES = $(SimScheduler_SOURCES) $(tinylist_SOURCES) \
	$(tinyoq_SOURCES) $(tinyprioq_SOURCES) $(tinyqueue_SOURCES)
DIST_SOURCES = $(am__SimScheduler_SOURCES_DIST) $(tinylist_SOURCES) \
	$(tinyoq_SOURCES) $(tinyprioq_SOURCES) $(tinyqueue_SOURCES)
am__can_run_installinfo = \
  case $$AM_UPDATE_INFO_DIR in \
    n|no|NO) false;; \
    *) (install-info --version) >/dev/null 2>&1;; \
  esac
am__vpath_adj_setup = srcdirstrip=`echo "$(srcdir)" | sed 's|.|.|g'`;
am__vpath_adj = case $$p in \
    $(srcdir)/*) f=`echo "$$p" | sed "s|^$$srcdirstrip/||"`;; \
    *) f=$$p;; \
  esac;
am__strip_dir = f=`echo $$p | sed -e 's|^.*/||'`;
am__install_max = 40
am__nobase_strip_setup = \
  srcdirstrip=`echo "$(srcdir)" | sed 's/[].[^$$\\*|]/\\\\&/g'`
am__nobase_strip = \
  for p in $$list; do echo "$$p"; done | sed -e "s|$$srcdirstrip/||"
am__nobase_list = $(am__nobase_strip_setup); \
  for p in $$list; do echo "$$p $$p"; done | \
  sed "s| $$srcdirstrip/| |;"' / .*\//!s/ .*/ ./; s,\( .*\)/[^/]*$$,\1,' | \
  $(AWK) 'BEGIN { files["."] = "" } { files[$$2] = files[$$2] " " $$1; \
    if (++n[$$2] == $(am__install_max)) \
      { print $$2, files[$$2]; n[$$2] = 0; files[$$2] = "" } } \
    END { for (dir in files) print dir, files[dir] }'
am__base_list = \
  sed '$$!N;$$!N;$$!N;$$!N;$$!N;$$!N;$$!N;s/\n/ /g' | \
  sed '$$!N;$$!N;$$!N;$$!N;s/\n/ /g'
am__uninstall_files_from_dir = { \
  test -z "$$files" \
    || { test ! -d "$$dir" && test ! -f "$$dir" && test ! -r "$$dir"; } \
    || { echo " ( cd '$$dir' && rm -f" $$files ")"; \
         $(am__cd) "$$dir" && rm -f $$files; }; \
  }
DATA = $(dist_data_DATA)
ETAGS = etags
CTAGS = ctags
DISTFILES = $(DIST_COMMON) $(DIST_SOURCES) $(TEXINFOS) $(EXTRA_DIST)
ACLOCAL = aclocal-1.11
AMTAR = $${TAR-tar}
ASSIMP_CFLAGS = -I/usr/include/assimp  
ASSIMP_LIBS = -L/usr/lib -lassimp  
AUTOCONF = autoconf
AUTOHEADER = autoheader
AUTOMAKE = automake-1.11
AWK = gawk
CC = gcc
CCDEPMODE = depmode=gcc3
CFLAGS = -g -O2
CPP = gcc -E
CPPFLAGS = 
CYGPATH_W = echo
DEFS = -DHAVE_CONFIG_H
DEPDIR = .deps
ECHO_C = 
ECHO_N = -n
ECHO_T = 
EGREP = /bin/grep -E
EXEEXT = 
FTGL_CFLAGS = -I/usr/include/FTGL -I/usr/include/freetype2  
FTGL_LIBS = -lftgl  
GREP = /bin/grep
INSTALL = /usr/bin/install -c
INSTALL_DATA = ${INSTALL} -m 644
INSTALL_PROGRAM = ${INSTALL}
INSTALL_SCRIPT = ${INSTALL}
INSTALL_STRIP_PROGRAM = $(install_sh) -c -s
LDFLAGS = 
LIBOBJS = 
LIBS = 
LTLIBOBJS = 
MAKEINFO = makeinfo
MKDIR_P = /bin/mkdir -p
OBJEXT = o
OPENMP_LIBS = 
PACKAGE = simscheduler
PACKAGE_BUGREPORT = oteodoro@uci.edu
PACKAGE_NAME = SimScheduler
PACKAGE_STRING = SimScheduler 1.0
PACKAGE_TARNAME = simscheduler
PACKAGE_URL = 
PACKAGE_VERSION = 1.0
PATH_SEPARATOR = :
PKG_CONFIG = /usr/bin/pkg-config
PKG_CONFIG_LIBDIR = 
PKG_CONFIG_PATH = 
SDL_CFLAGS = -D_GNU_SOURCE=1 -D_REENTRANT -I/usr/include/SDL  
SDL_LIBS = -lSDL -lpthread  
SET_MAKE = 
SHELL = /bin/sh
STRIP = 
VERSION = 1.0
abs_builddir = /home/orson/simsched.minified/SimScheduler/src
abs_srcdir = /home/orson/simsched.minified/SimScheduler/src
abs_top_builddir = /home/orson/simsched.minified/SimScheduler
abs_top_srcdir = /home/orson/simsched.minified/SimScheduler
ac_ct_CC = gcc
am__include = include
am__leading_dot = .
am__quote = 
am__tar = $${TAR-tar} chof - "$$tardir"
am__untar = $${TAR-tar} xf -
bindir = ${exec_prefix}/bin
build_alias = 
builddir = .
datadir = ${datarootdir}
datarootdir = ${prefix}/share
docdir = ${datarootdir}/doc/${PACKAGE_TARNAME}
dvidir = ${docdir}
exec_prefix = ${prefix}
host_alias = 
htmldir = ${docdir}
includedir = ${prefix}/include
infodir = ${datarootdir}/info
install_sh = ${SHELL} /home/orson/install-sh
libdir = ${exec_prefix}/lib
libexecdir = ${exec_prefix}/libexec
localedir = ${datarootdir}/locale
localstatedir = ${prefix}/var
mandir = ${datarootdir}/man
mkdir_p = /bin/mkdir -p
oldincludedir = /usr/include
pdfdir = ${docdir}
prefix = /usr/local
program_transform_name = s,x,x,
psdir = ${docdir}
sbindir = ${exec_prefix}/sbin
sharedstatedir = ${prefix}/com
srcdir = .
sysconfdir = ${prefix}/etc
target_alias = 
top_build_prefix = ../
top_builddir = ..
top_srcdir = ..
GRAPHICS_CFLAGS = -DHAVE_SDL -DHAVE_ASSIMP -DHAVE_FTGL
#GRAPHICS_SOURCES = 
GRAPHICS_SOURCES = schedsysgl.c
TESTPROGS = 
#TESTPROGS = tinyqueue tinylist tinyprioq tinyoq
SimScheduler_SOURCES = main.c processlist.c tinyoq.c tinylist.c process.c schedsys.c $(GRAPHICS_SOURCES)
SimScheduler_LDFLAGS = $(SDL_LIBS) $(ASSIMP_LIBS) $(FTGL_LIBS) $(OPENMP_LIBS)
SimScheduler_CFLAGS = $(GRAPHICS_CFLAGS) $(SDL_CFLAGS) $(ASSIMP_CFLAGS) $(FTGL_CFLAGS)
SimScheduler_MANS = simscheduler.1
tinylist_CFLAGS = -DTEST
tinylist_SOURCES = tinylist.c
tinyoq_CFLAGS = -DTEST
tinyoq_SOURCES = tinyoq.c
tinyprioq_CFLAGS = -DTEST
tinyprioq_SOURCES = tinyprioq.c
tinyqueue_CFLAGS = -DTEST
tinyqueue_SOURCES = tinyqueue.c
EXTRA_DIST = in0.txt in1.txt out0.txt out1.txt
dist_data_DATA = cpu.blend hd.blend queuecontainer.blend queuenode.blend
all: all-am

.SUFFIXES:
.SUFFIXES: .c .o .obj
$(srcdir)/Makefile.in:  $(srcdir)/Makefile.am  $(am__configure_deps)
	@for dep in $?; do \
	  case '$(am__configure_deps)' in \
	    *$$dep*) \
	      ( cd $(top_builddir) && $(MAKE) $(AM_MAKEFLAGS) am--refresh ) \
	        && { if test -f $@; then exit 0; else break; fi; }; \
	      exit 1;; \
	  esac; \
	done; \
	echo ' cd $(top_srcdir) && $(AUTOMAKE) --gnu src/Makefile'; \
	$(am__cd) $(top_srcdir) && \
	  $(AUTOMAKE) --gnu src/Makefile
.PRECIOUS: Makefile
Makefile: $(srcdir)/Makefile.in $(top_builddir)/config.status
	@case '$?' in \
	  *config.status*) \
	    cd $(top_builddir) && $(MAKE) $(AM_MAKEFLAGS) am--refresh;; \
	  *) \
	    echo ' cd $(top_builddir) && $(SHELL) ./config.status $(subdir)/$@ $(am__depfiles_maybe)'; \
	    cd $(top_builddir) && $(SHELL) ./config.status $(subdir)/$@ $(am__depfiles_maybe);; \
	esac;

$(top_builddir)/config.status: $(top_srcdir)/configure $(CONFIG_STATUS_DEPENDENCIES)
	cd $(top_builddir) && $(MAKE) $(AM_MAKEFLAGS) am--refresh

$(top_srcdir)/configure:  $(am__configure_deps)
	cd $(top_builddir) && $(MAKE) $(AM_MAKEFLAGS) am--refresh
$(ACLOCAL_M4):  $(am__aclocal_m4_deps)
	cd $(top_builddir) && $(MAKE) $(AM_MAKEFLAGS) am--refresh
$(am__aclocal_m4_deps):
install-binPROGRAMS: $(bin_PROGRAMS)
	@$(NORMAL_INSTALL)
	@list='$(bin_PROGRAMS)'; test -n "$(bindir)" || list=; \
	if test -n "$$list"; then \
	  echo " $(MKDIR_P) '$(DESTDIR)$(bindir)'"; \
	  $(MKDIR_P) "$(DESTDIR)$(bindir)" || exit 1; \
	fi; \
	for p in $$list; do echo "$$p $$p"; done | \
	sed 's/$(EXEEXT)$$//' | \
	while read p p1; do if test -f $$p; \
	  then echo "$$p"; echo "$$p"; else :; fi; \
	done | \
	sed -e 'p;s,.*/,,;n;h' -e 's|.*|.|' \
	    -e 'p;x;s,.*/,,;s/$(EXEEXT)$$//;$(transform);s/$$/$(EXEEXT)/' | \
	sed 'N;N;N;s,\n, ,g' | \
	$(AWK) 'BEGIN { files["."] = ""; dirs["."] = 1 } \
	  { d=$$3; if (dirs[d] != 1) { print "d", d; dirs[d] = 1 } \
	    if ($$2 == $$4) files[d] = files[d] " " $$1; \
	    else { print "f", $$3 "/" $$4, $$1; } } \
	  END { for (d in files) print "f", d, files[d] }' | \
	while read type dir files; do \
	    if test "$$dir" = .; then dir=; else dir=/$$dir; fi; \
	    test -z "$$files" || { \
	      echo " $(INSTALL_PROGRAM_ENV) $(INSTALL_PROGRAM) $$files '$(DESTDIR)$(bindir)$$dir'"; \
	      $(INSTALL_PROGRAM_ENV) $(INSTALL_PROGRAM) $$files "$(DESTDIR)$(bindir)$$dir" || exit $$?; \
	    } \
	; done

uninstall-binPROGRAMS:
	@$(NORMAL_UNINSTALL)
	@list='$(bin_PROGRAMS)'; test -n "$(bindir)" || list=; \
	files=`for p in $$list; do echo "$$p"; done | \
	  sed -e 'h;s,^.*/,,;s/$(EXEEXT)$$//;$(transform)' \
	      -e 's/$$/$(EXEEXT)/' `; \
	test -n "$$list" || exit 0; \
	echo " ( cd '$(DESTDIR)$(bindir)' && rm -f" $$files ")"; \
	cd "$(DESTDIR)$(bindir)" && rm -f $$files

clean-binPROGRAMS:
	-test -z "$(bin_PROGRAMS)" || rm -f $(bin_PROGRAMS)
SimScheduler$(EXEEXT): $(SimScheduler_OBJECTS) $(SimScheduler_DEPENDENCIES) $(EXTRA_SimScheduler_DEPENDENCIES) 
	@rm -f SimScheduler$(EXEEXT)
	$(SimScheduler_LINK) $(SimScheduler_OBJECTS) $(SimScheduler_LDADD) $(LIBS)
tinylist$(EXEEXT): $(tinylist_OBJECTS) $(tinylist_DEPENDENCIES) $(EXTRA_tinylist_DEPENDENCIES) 
	@rm -f tinylist$(EXEEXT)
	$(tinylist_LINK) $(tinylist_OBJECTS) $(tinylist_LDADD) $(LIBS)
tinyoq$(EXEEXT): $(tinyoq_OBJECTS) $(tinyoq_DEPENDENCIES) $(EXTRA_tinyoq_DEPENDENCIES) 
	@rm -f tinyoq$(EXEEXT)
	$(tinyoq_LINK) $(tinyoq_OBJECTS) $(tinyoq_LDADD) $(LIBS)
tinyprioq$(EXEEXT): $(tinyprioq_OBJECTS) $(tinyprioq_DEPENDENCIES) $(EXTRA_tinyprioq_DEPENDENCIES) 
	@rm -f tinyprioq$(EXEEXT)
	$(tinyprioq_LINK) $(tinyprioq_OBJECTS) $(tinyprioq_LDADD) $(LIBS)
tinyqueue$(EXEEXT): $(tinyqueue_OBJECTS) $(tinyqueue_DEPENDENCIES) $(EXTRA_tinyqueue_DEPENDENCIES) 
	@rm -f tinyqueue$(EXEEXT)
	$(tinyqueue_LINK) $(tinyqueue_OBJECTS) $(tinyqueue_LDADD) $(LIBS)

mostlyclean-compile:
	-rm -f *.$(OBJEXT)

distclean-compile:
	-rm -f *.tab.c

include ./$(DEPDIR)/SimScheduler-main.Po
include ./$(DEPDIR)/SimScheduler-process.Po
include ./$(DEPDIR)/SimScheduler-processlist.Po
include ./$(DEPDIR)/SimScheduler-schedsys.Po
include ./$(DEPDIR)/SimScheduler-schedsysgl.Po
include ./$(DEPDIR)/SimScheduler-tinylist.Po
include ./$(DEPDIR)/SimScheduler-tinyoq.Po
include ./$(DEPDIR)/tinylist-tinylist.Po
include ./$(DEPDIR)/tinyoq-tinyoq.Po
include ./$(DEPDIR)/tinyprioq-tinyprioq.Po
include ./$(DEPDIR)/tinyqueue-tinyqueue.Po

.c.o:
	$(COMPILE) -MT $@ -MD -MP -MF $(DEPDIR)/$*.Tpo -c -o $@ $<
	$(am__mv) $(DEPDIR)/$*.Tpo $(DEPDIR)/$*.Po
#	source='$<' object='$@' libtool=no \
#	DEPDIR=$(DEPDIR) $(CCDEPMODE) $(depcomp) \
#	$(COMPILE) -c $<

.c.obj:
	$(COMPILE) -MT $@ -MD -MP -MF $(DEPDIR)/$*.Tpo -c -o $@ `$(CYGPATH_W) '$<'`
	$(am__mv) $(DEPDIR)/$*.Tpo $(DEPDIR)/$*.Po
#	source='$<' object='$@' libtool=no \
#	DEPDIR=$(DEPDIR) $(CCDEPMODE) $(depcomp) \
#	$(COMPILE) -c `$(CYGPATH_W) '$<'`

SimScheduler-main.o: main.c
	$(CC) $(DEFS) $(DEFAULT_INCLUDES) $(INCLUDES) $(AM_CPPFLAGS) $(CPPFLAGS) $(SimScheduler_CFLAGS) $(CFLAGS) -MT SimScheduler-main.o -MD -MP -MF $(DEPDIR)/SimScheduler-main.Tpo -c -o SimScheduler-main.o `test -f 'main.c' || echo '$(srcdir)/'`main.c
	$(am__mv) $(DEPDIR)/SimScheduler-main.Tpo $(DEPDIR)/SimScheduler-main.Po
#	source='main.c' object='SimScheduler-main.o' libtool=no \
#	DEPDIR=$(DEPDIR) $(CCDEPMODE) $(depcomp) \
#	$(CC) $(DEFS) $(DEFAULT_INCLUDES) $(INCLUDES) $(AM_CPPFLAGS) $(CPPFLAGS) $(SimScheduler_CFLAGS) $(CFLAGS) -c -o SimScheduler-main.o `test -f 'main.c' || echo '$(srcdir)/'`main.c

SimScheduler-main.obj: main.c
	$(CC) $(DEFS) $(DEFAULT_INCLUDES) $(INCLUDES) $(AM_CPPFLAGS) $(CPPFLAGS) $(SimScheduler_CFLAGS) $(CFLAGS) -MT SimScheduler-main.obj -MD -MP -MF $(DEPDIR)/SimScheduler-main.Tpo -c -o SimScheduler-main.obj `if test -f 'main.c'; then $(CYGPATH_W) 'main.c'; else $(CYGPATH_W) '$(srcdir)/main.c'; fi`
	$(am__mv) $(DEPDIR)/SimScheduler-main.Tpo $(DEPDIR)/SimScheduler-main.Po
#	source='main.c' object='SimScheduler-main.obj' libtool=no \
#	DEPDIR=$(DEPDIR) $(CCDEPMODE) $(depcomp) \
#	$(CC) $(DEFS) $(DEFAULT_INCLUDES) $(INCLUDES) $(AM_CPPFLAGS) $(CPPFLAGS) $(SimScheduler_CFLAGS) $(CFLAGS) -c -o SimScheduler-main.obj `if test -f 'main.c'; then $(CYGPATH_W) 'main.c'; else $(CYGPATH_W) '$(srcdir)/main.c'; fi`

SimScheduler-processlist.o: processlist.c
	$(CC) $(DEFS) $(DEFAULT_INCLUDES) $(INCLUDES) $(AM_CPPFLAGS) $(CPPFLAGS) $(SimScheduler_CFLAGS) $(CFLAGS) -MT SimScheduler-processlist.o -MD -MP -MF $(DEPDIR)/SimScheduler-processlist.Tpo -c -o SimScheduler-processlist.o `test -f 'processlist.c' || echo '$(srcdir)/'`processlist.c
	$(am__mv) $(DEPDIR)/SimScheduler-processlist.Tpo $(DEPDIR)/SimScheduler-processlist.Po
#	source='processlist.c' object='SimScheduler-processlist.o' libtool=no \
#	DEPDIR=$(DEPDIR) $(CCDEPMODE) $(depcomp) \
#	$(CC) $(DEFS) $(DEFAULT_INCLUDES) $(INCLUDES) $(AM_CPPFLAGS) $(CPPFLAGS) $(SimScheduler_CFLAGS) $(CFLAGS) -c -o SimScheduler-processlist.o `test -f 'processlist.c' || echo '$(srcdir)/'`processlist.c

SimScheduler-processlist.obj: processlist.c
	$(CC) $(DEFS) $(DEFAULT_INCLUDES) $(INCLUDES) $(AM_CPPFLAGS) $(CPPFLAGS) $(SimScheduler_CFLAGS) $(CFLAGS) -MT SimScheduler-processlist.obj -MD -MP -MF $(DEPDIR)/SimScheduler-processlist.Tpo -c -o SimScheduler-processlist.obj `if test -f 'processlist.c'; then $(CYGPATH_W) 'processlist.c'; else $(CYGPATH_W) '$(srcdir)/processlist.c'; fi`
	$(am__mv) $(DEPDIR)/SimScheduler-processlist.Tpo $(DEPDIR)/SimScheduler-processlist.Po
#	source='processlist.c' object='SimScheduler-processlist.obj' libtool=no \
#	DEPDIR=$(DEPDIR) $(CCDEPMODE) $(depcomp) \
#	$(CC) $(DEFS) $(DEFAULT_INCLUDES) $(INCLUDES) $(AM_CPPFLAGS) $(CPPFLAGS) $(SimScheduler_CFLAGS) $(CFLAGS) -c -o SimScheduler-processlist.obj `if test -f 'processlist.c'; then $(CYGPATH_W) 'processlist.c'; else $(CYGPATH_W) '$(srcdir)/processlist.c'; fi`

SimScheduler-tinyoq.o: tinyoq.c
	$(CC) $(DEFS) $(DEFAULT_INCLUDES) $(INCLUDES) $(AM_CPPFLAGS) $(CPPFLAGS) $(SimScheduler_CFLAGS) $(CFLAGS) -MT SimScheduler-tinyoq.o -MD -MP -MF $(DEPDIR)/SimScheduler-tinyoq.Tpo -c -o SimScheduler-tinyoq.o `test -f 'tinyoq.c' || echo '$(srcdir)/'`tinyoq.c
	$(am__mv) $(DEPDIR)/SimScheduler-tinyoq.Tpo $(DEPDIR)/SimScheduler-tinyoq.Po
#	source='tinyoq.c' object='SimScheduler-tinyoq.o' libtool=no \
#	DEPDIR=$(DEPDIR) $(CCDEPMODE) $(depcomp) \
#	$(CC) $(DEFS) $(DEFAULT_INCLUDES) $(INCLUDES) $(AM_CPPFLAGS) $(CPPFLAGS) $(SimScheduler_CFLAGS) $(CFLAGS) -c -o SimScheduler-tinyoq.o `test -f 'tinyoq.c' || echo '$(srcdir)/'`tinyoq.c

SimScheduler-tinyoq.obj: tinyoq.c
	$(CC) $(DEFS) $(DEFAULT_INCLUDES) $(INCLUDES) $(AM_CPPFLAGS) $(CPPFLAGS) $(SimScheduler_CFLAGS) $(CFLAGS) -MT SimScheduler-tinyoq.obj -MD -MP -MF $(DEPDIR)/SimScheduler-tinyoq.Tpo -c -o SimScheduler-tinyoq.obj `if test -f 'tinyoq.c'; then $(CYGPATH_W) 'tinyoq.c'; else $(CYGPATH_W) '$(srcdir)/tinyoq.c'; fi`
	$(am__mv) $(DEPDIR)/SimScheduler-tinyoq.Tpo $(DEPDIR)/SimScheduler-tinyoq.Po
#	source='tinyoq.c' object='SimScheduler-tinyoq.obj' libtool=no \
#	DEPDIR=$(DEPDIR) $(CCDEPMODE) $(depcomp) \
#	$(CC) $(DEFS) $(DEFAULT_INCLUDES) $(INCLUDES) $(AM_CPPFLAGS) $(CPPFLAGS) $(SimScheduler_CFLAGS) $(CFLAGS) -c -o SimScheduler-tinyoq.obj `if test -f 'tinyoq.c'; then $(CYGPATH_W) 'tinyoq.c'; else $(CYGPATH_W) '$(srcdir)/tinyoq.c'; fi`

SimScheduler-tinylist.o: tinylist.c
	$(CC) $(DEFS) $(DEFAULT_INCLUDES) $(INCLUDES) $(AM_CPPFLAGS) $(CPPFLAGS) $(SimScheduler_CFLAGS) $(CFLAGS) -MT SimScheduler-tinylist.o -MD -MP -MF $(DEPDIR)/SimScheduler-tinylist.Tpo -c -o SimScheduler-tinylist.o `test -f 'tinylist.c' || echo '$(srcdir)/'`tinylist.c
	$(am__mv) $(DEPDIR)/SimScheduler-tinylist.Tpo $(DEPDIR)/SimScheduler-tinylist.Po
#	source='tinylist.c' object='SimScheduler-tinylist.o' libtool=no \
#	DEPDIR=$(DEPDIR) $(CCDEPMODE) $(depcomp) \
#	$(CC) $(DEFS) $(DEFAULT_INCLUDES) $(INCLUDES) $(AM_CPPFLAGS) $(CPPFLAGS) $(SimScheduler_CFLAGS) $(CFLAGS) -c -o SimScheduler-tinylist.o `test -f 'tinylist.c' || echo '$(srcdir)/'`tinylist.c

SimScheduler-tinylist.obj: tinylist.c
	$(CC) $(DEFS) $(DEFAULT_INCLUDES) $(INCLUDES) $(AM_CPPFLAGS) $(CPPFLAGS) $(SimScheduler_CFLAGS) $(CFLAGS) -MT SimScheduler-tinylist.obj -MD -MP -MF $(DEPDIR)/SimScheduler-tinylist.Tpo -c -o SimScheduler-tinylist.obj `if test -f 'tinylist.c'; then $(CYGPATH_W) 'tinylist.c'; else $(CYGPATH_W) '$(srcdir)/tinylist.c'; fi`
	$(am__mv) $(DEPDIR)/SimScheduler-tinylist.Tpo $(DEPDIR)/SimScheduler-tinylist.Po
#	source='tinylist.c' object='SimScheduler-tinylist.obj' libtool=no \
#	DEPDIR=$(DEPDIR) $(CCDEPMODE) $(depcomp) \
#	$(CC) $(DEFS) $(DEFAULT_INCLUDES) $(INCLUDES) $(AM_CPPFLAGS) $(CPPFLAGS) $(SimScheduler_CFLAGS) $(CFLAGS) -c -o SimScheduler-tinylist.obj `if test -f 'tinylist.c'; then $(CYGPATH_W) 'tinylist.c'; else $(CYGPATH_W) '$(srcdir)/tinylist.c'; fi`

SimScheduler-process.o: process.c
	$(CC) $(DEFS) $(DEFAULT_INCLUDES) $(INCLUDES) $(AM_CPPFLAGS) $(CPPFLAGS) $(SimScheduler_CFLAGS) $(CFLAGS) -MT SimScheduler-process.o -MD -MP -MF $(DEPDIR)/SimScheduler-process.Tpo -c -o SimScheduler-process.o `test -f 'process.c' || echo '$(srcdir)/'`process.c
	$(am__mv) $(DEPDIR)/SimScheduler-process.Tpo $(DEPDIR)/SimScheduler-process.Po
#	source='process.c' object='SimScheduler-process.o' libtool=no \
#	DEPDIR=$(DEPDIR) $(CCDEPMODE) $(depcomp) \
#	$(CC) $(DEFS) $(DEFAULT_INCLUDES) $(INCLUDES) $(AM_CPPFLAGS) $(CPPFLAGS) $(SimScheduler_CFLAGS) $(CFLAGS) -c -o SimScheduler-process.o `test -f 'process.c' || echo '$(srcdir)/'`process.c

SimScheduler-process.obj: process.c
	$(CC) $(DEFS) $(DEFAULT_INCLUDES) $(INCLUDES) $(AM_CPPFLAGS) $(CPPFLAGS) $(SimScheduler_CFLAGS) $(CFLAGS) -MT SimScheduler-process.obj -MD -MP -MF $(DEPDIR)/SimScheduler-process.Tpo -c -o SimScheduler-process.obj `if test -f 'process.c'; then $(CYGPATH_W) 'process.c'; else $(CYGPATH_W) '$(srcdir)/process.c'; fi`
	$(am__mv) $(DEPDIR)/SimScheduler-process.Tpo $(DEPDIR)/SimScheduler-process.Po
#	source='process.c' object='SimScheduler-process.obj' libtool=no \
#	DEPDIR=$(DEPDIR) $(CCDEPMODE) $(depcomp) \
#	$(CC) $(DEFS) $(DEFAULT_INCLUDES) $(INCLUDES) $(AM_CPPFLAGS) $(CPPFLAGS) $(SimScheduler_CFLAGS) $(CFLAGS) -c -o SimScheduler-process.obj `if test -f 'process.c'; then $(CYGPATH_W) 'process.c'; else $(CYGPATH_W) '$(srcdir)/process.c'; fi`

SimScheduler-schedsys.o: schedsys.c
	$(CC) $(DEFS) $(DEFAULT_INCLUDES) $(INCLUDES) $(AM_CPPFLAGS) $(CPPFLAGS) $(SimScheduler_CFLAGS) $(CFLAGS) -MT SimScheduler-schedsys.o -MD -MP -MF $(DEPDIR)/SimScheduler-schedsys.Tpo -c -o SimScheduler-schedsys.o `test -f 'schedsys.c' || echo '$(srcdir)/'`schedsys.c
	$(am__mv) $(DEPDIR)/SimScheduler-schedsys.Tpo $(DEPDIR)/SimScheduler-schedsys.Po
#	source='schedsys.c' object='SimScheduler-schedsys.o' libtool=no \
#	DEPDIR=$(DEPDIR) $(CCDEPMODE) $(depcomp) \
#	$(CC) $(DEFS) $(DEFAULT_INCLUDES) $(INCLUDES) $(AM_CPPFLAGS) $(CPPFLAGS) $(SimScheduler_CFLAGS) $(CFLAGS) -c -o SimScheduler-schedsys.o `test -f 'schedsys.c' || echo '$(srcdir)/'`schedsys.c

SimScheduler-schedsys.obj: schedsys.c
	$(CC) $(DEFS) $(DEFAULT_INCLUDES) $(INCLUDES) $(AM_CPPFLAGS) $(CPPFLAGS) $(SimScheduler_CFLAGS) $(CFLAGS) -MT SimScheduler-schedsys.obj -MD -MP -MF $(DEPDIR)/SimScheduler-schedsys.Tpo -c -o SimScheduler-schedsys.obj `if test -f 'schedsys.c'; then $(CYGPATH_W) 'schedsys.c'; else $(CYGPATH_W) '$(srcdir)/schedsys.c'; fi`
	$(am__mv) $(DEPDIR)/SimScheduler-schedsys.Tpo $(DEPDIR)/SimScheduler-schedsys.Po
#	source='schedsys.c' object='SimScheduler-schedsys.obj' libtool=no \
#	DEPDIR=$(DEPDIR) $(CCDEPMODE) $(depcomp) \
#	$(CC) $(DEFS) $(DEFAULT_INCLUDES) $(INCLUDES) $(AM_CPPFLAGS) $(CPPFLAGS) $(SimScheduler_CFLAGS) $(CFLAGS) -c -o SimScheduler-schedsys.obj `if test -f 'schedsys.c'; then $(CYGPATH_W) 'schedsys.c'; else $(CYGPATH_W) '$(srcdir)/schedsys.c'; fi`

SimScheduler-schedsysgl.o: schedsysgl.c
	$(CC) $(DEFS) $(DEFAULT_INCLUDES) $(INCLUDES) $(AM_CPPFLAGS) $(CPPFLAGS) $(SimScheduler_CFLAGS) $(CFLAGS) -MT SimScheduler-schedsysgl.o -MD -MP -MF $(DEPDIR)/SimScheduler-schedsysgl.Tpo -c -o SimScheduler-schedsysgl.o `test -f 'schedsysgl.c' || echo '$(srcdir)/'`schedsysgl.c
	$(am__mv) $(DEPDIR)/SimScheduler-schedsysgl.Tpo $(DEPDIR)/SimScheduler-schedsysgl.Po
#	source='schedsysgl.c' object='SimScheduler-schedsysgl.o' libtool=no \
#	DEPDIR=$(DEPDIR) $(CCDEPMODE) $(depcomp) \
#	$(CC) $(DEFS) $(DEFAULT_INCLUDES) $(INCLUDES) $(AM_CPPFLAGS) $(CPPFLAGS) $(SimScheduler_CFLAGS) $(CFLAGS) -c -o SimScheduler-schedsysgl.o `test -f 'schedsysgl.c' || echo '$(srcdir)/'`schedsysgl.c

SimScheduler-schedsysgl.obj: schedsysgl.c
	$(CC) $(DEFS) $(DEFAULT_INCLUDES) $(INCLUDES) $(AM_CPPFLAGS) $(CPPFLAGS) $(SimScheduler_CFLAGS) $(CFLAGS) -MT SimScheduler-schedsysgl.obj -MD -MP -MF $(DEPDIR)/SimScheduler-schedsysgl.Tpo -c -o SimScheduler-schedsysgl.obj `if test -f 'schedsysgl.c'; then $(CYGPATH_W) 'schedsysgl.c'; else $(CYGPATH_W) '$(srcdir)/schedsysgl.c'; fi`
	$(am__mv) $(DEPDIR)/SimScheduler-schedsysgl.Tpo $(DEPDIR)/SimScheduler-schedsysgl.Po
#	source='schedsysgl.c' object='SimScheduler-schedsysgl.obj' libtool=no \
#	DEPDIR=$(DEPDIR) $(CCDEPMODE) $(depcomp) \
#	$(CC) $(DEFS) $(DEFAULT_INCLUDES) $(INCLUDES) $(AM_CPPFLAGS) $(CPPFLAGS) $(SimScheduler_CFLAGS) $(CFLAGS) -c -o SimScheduler-schedsysgl.obj `if test -f 'schedsysgl.c'; then $(CYGPATH_W) 'schedsysgl.c'; else $(CYGPATH_W) '$(srcdir)/schedsysgl.c'; fi`

tinylist-tinylist.o: tinylist.c
	$(CC) $(DEFS) $(DEFAULT_INCLUDES) $(INCLUDES) $(AM_CPPFLAGS) $(CPPFLAGS) $(tinylist_CFLAGS) $(CFLAGS) -MT tinylist-tinylist.o -MD -MP -MF $(DEPDIR)/tinylist-tinylist.Tpo -c -o tinylist-tinylist.o `test -f 'tinylist.c' || echo '$(srcdir)/'`tinylist.c
	$(am__mv) $(DEPDIR)/tinylist-tinylist.Tpo $(DEPDIR)/tinylist-tinylist.Po
#	source='tinylist.c' object='tinylist-tinylist.o' libtool=no \
#	DEPDIR=$(DEPDIR) $(CCDEPMODE) $(depcomp) \
#	$(CC) $(DEFS) $(DEFAULT_INCLUDES) $(INCLUDES) $(AM_CPPFLAGS) $(CPPFLAGS) $(tinylist_CFLAGS) $(CFLAGS) -c -o tinylist-tinylist.o `test -f 'tinylist.c' || echo '$(srcdir)/'`tinylist.c

tinylist-tinylist.obj: tinylist.c
	$(CC) $(DEFS) $(DEFAULT_INCLUDES) $(INCLUDES) $(AM_CPPFLAGS) $(CPPFLAGS) $(tinylist_CFLAGS) $(CFLAGS) -MT tinylist-tinylist.obj -MD -MP -MF $(DEPDIR)/tinylist-tinylist.Tpo -c -o tinylist-tinylist.obj `if test -f 'tinylist.c'; then $(CYGPATH_W) 'tinylist.c'; else $(CYGPATH_W) '$(srcdir)/tinylist.c'; fi`
	$(am__mv) $(DEPDIR)/tinylist-tinylist.Tpo $(DEPDIR)/tinylist-tinylist.Po
#	source='tinylist.c' object='tinylist-tinylist.obj' libtool=no \
#	DEPDIR=$(DEPDIR) $(CCDEPMODE) $(depcomp) \
#	$(CC) $(DEFS) $(DEFAULT_INCLUDES) $(INCLUDES) $(AM_CPPFLAGS) $(CPPFLAGS) $(tinylist_CFLAGS) $(CFLAGS) -c -o tinylist-tinylist.obj `if test -f 'tinylist.c'; then $(CYGPATH_W) 'tinylist.c'; else $(CYGPATH_W) '$(srcdir)/tinylist.c'; fi`

tinyoq-tinyoq.o: tinyoq.c
	$(CC) $(DEFS) $(DEFAULT_INCLUDES) $(INCLUDES) $(AM_CPPFLAGS) $(CPPFLAGS) $(tinyoq_CFLAGS) $(CFLAGS) -MT tinyoq-tinyoq.o -MD -MP -MF $(DEPDIR)/tinyoq-tinyoq.Tpo -c -o tinyoq-tinyoq.o `test -f 'tinyoq.c' || echo '$(srcdir)/'`tinyoq.c
	$(am__mv) $(DEPDIR)/tinyoq-tinyoq.Tpo $(DEPDIR)/tinyoq-tinyoq.Po
#	source='tinyoq.c' object='tinyoq-tinyoq.o' libtool=no \
#	DEPDIR=$(DEPDIR) $(CCDEPMODE) $(depcomp) \
#	$(CC) $(DEFS) $(DEFAULT_INCLUDES) $(INCLUDES) $(AM_CPPFLAGS) $(CPPFLAGS) $(tinyoq_CFLAGS) $(CFLAGS) -c -o tinyoq-tinyoq.o `test -f 'tinyoq.c' || echo '$(srcdir)/'`tinyoq.c

tinyoq-tinyoq.obj: tinyoq.c
	$(CC) $(DEFS) $(DEFAULT_INCLUDES) $(INCLUDES) $(AM_CPPFLAGS) $(CPPFLAGS) $(tinyoq_CFLAGS) $(CFLAGS) -MT tinyoq-tinyoq.obj -MD -MP -MF $(DEPDIR)/tinyoq-tinyoq.Tpo -c -o tinyoq-tinyoq.obj `if test -f 'tinyoq.c'; then $(CYGPATH_W) 'tinyoq.c'; else $(CYGPATH_W) '$(srcdir)/tinyoq.c'; fi`
	$(am__mv) $(DEPDIR)/tinyoq-tinyoq.Tpo $(DEPDIR)/tinyoq-tinyoq.Po
#	source='tinyoq.c' object='tinyoq-tinyoq.obj' libtool=no \
#	DEPDIR=$(DEPDIR) $(CCDEPMODE) $(depcomp) \
#	$(CC) $(DEFS) $(DEFAULT_INCLUDES) $(INCLUDES) $(AM_CPPFLAGS) $(CPPFLAGS) $(tinyoq_CFLAGS) $(CFLAGS) -c -o tinyoq-tinyoq.obj `if test -f 'tinyoq.c'; then $(CYGPATH_W) 'tinyoq.c'; else $(CYGPATH_W) '$(srcdir)/tinyoq.c'; fi`

tinyprioq-tinyprioq.o: tinyprioq.c
	$(CC) $(DEFS) $(DEFAULT_INCLUDES) $(INCLUDES) $(AM_CPPFLAGS) $(CPPFLAGS) $(tinyprioq_CFLAGS) $(CFLAGS) -MT tinyprioq-tinyprioq.o -MD -MP -MF $(DEPDIR)/tinyprioq-tinyprioq.Tpo -c -o tinyprioq-tinyprioq.o `test -f 'tinyprioq.c' || echo '$(srcdir)/'`tinyprioq.c
	$(am__mv) $(DEPDIR)/tinyprioq-tinyprioq.Tpo $(DEPDIR)/tinyprioq-tinyprioq.Po
#	source='tinyprioq.c' object='tinyprioq-tinyprioq.o' libtool=no \
#	DEPDIR=$(DEPDIR) $(CCDEPMODE) $(depcomp) \
#	$(CC) $(DEFS) $(DEFAULT_INCLUDES) $(INCLUDES) $(AM_CPPFLAGS) $(CPPFLAGS) $(tinyprioq_CFLAGS) $(CFLAGS) -c -o tinyprioq-tinyprioq.o `test -f 'tinyprioq.c' || echo '$(srcdir)/'`tinyprioq.c

tinyprioq-tinyprioq.obj: tinyprioq.c
	$(CC) $(DEFS) $(DEFAULT_INCLUDES) $(INCLUDES) $(AM_CPPFLAGS) $(CPPFLAGS) $(tinyprioq_CFLAGS) $(CFLAGS) -MT tinyprioq-tinyprioq.obj -MD -MP -MF $(DEPDIR)/tinyprioq-tinyprioq.Tpo -c -o tinyprioq-tinyprioq.obj `if test -f 'tinyprioq.c'; then $(CYGPATH_W) 'tinyprioq.c'; else $(CYGPATH_W) '$(srcdir)/tinyprioq.c'; fi`
	$(am__mv) $(DEPDIR)/tinyprioq-tinyprioq.Tpo $(DEPDIR)/tinyprioq-tinyprioq.Po
#	source='tinyprioq.c' object='tinyprioq-tinyprioq.obj' libtool=no \
#	DEPDIR=$(DEPDIR) $(CCDEPMODE) $(depcomp) \
#	$(CC) $(DEFS) $(DEFAULT_INCLUDES) $(INCLUDES) $(AM_CPPFLAGS) $(CPPFLAGS) $(tinyprioq_CFLAGS) $(CFLAGS) -c -o tinyprioq-tinyprioq.obj `if test -f 'tinyprioq.c'; then $(CYGPATH_W) 'tinyprioq.c'; else $(CYGPATH_W) '$(srcdir)/tinyprioq.c'; fi`

tinyqueue-tinyqueue.o: tinyqueue.c
	$(CC) $(DEFS) $(DEFAULT_INCLUDES) $(INCLUDES) $(AM_CPPFLAGS) $(CPPFLAGS) $(tinyqueue_CFLAGS) $(CFLAGS) -MT tinyqueue-tinyqueue.o -MD -MP -MF $(DEPDIR)/tinyqueue-tinyqueue.Tpo -c -o tinyqueue-tinyqueue.o `test -f 'tinyqueue.c' || echo '$(srcdir)/'`tinyqueue.c
	$(am__mv) $(DEPDIR)/tinyqueue-tinyqueue.Tpo $(DEPDIR)/tinyqueue-tinyqueue.Po
#	source='tinyqueue.c' object='tinyqueue-tinyqueue.o' libtool=no \
#	DEPDIR=$(DEPDIR) $(CCDEPMODE) $(depcomp) \
#	$(CC) $(DEFS) $(DEFAULT_INCLUDES) $(INCLUDES) $(AM_CPPFLAGS) $(CPPFLAGS) $(tinyqueue_CFLAGS) $(CFLAGS) -c -o tinyqueue-tinyqueue.o `test -f 'tinyqueue.c' || echo '$(srcdir)/'`tinyqueue.c

tinyqueue-tinyqueue.obj: tinyqueue.c
	$(CC) $(DEFS) $(DEFAULT_INCLUDES) $(INCLUDES) $(AM_CPPFLAGS) $(CPPFLAGS) $(tinyqueue_CFLAGS) $(CFLAGS) -MT tinyqueue-tinyqueue.obj -MD -MP -MF $(DEPDIR)/tinyqueue-tinyqueue.Tpo -c -o tinyqueue-tinyqueue.obj `if test -f 'tinyqueue.c'; then $(CYGPATH_W) 'tinyqueue.c'; else $(CYGPATH_W) '$(srcdir)/tinyqueue.c'; fi`
	$(am__mv) $(DEPDIR)/tinyqueue-tinyqueue.Tpo $(DEPDIR)/tinyqueue-tinyqueue.Po
#	source='tinyqueue.c' object='tinyqueue-tinyqueue.obj' libtool=no \
#	DEPDIR=$(DEPDIR) $(CCDEPMODE) $(depcomp) \
#	$(CC) $(DEFS) $(DEFAULT_INCLUDES) $(INCLUDES) $(AM_CPPFLAGS) $(CPPFLAGS) $(tinyqueue_CFLAGS) $(CFLAGS) -c -o tinyqueue-tinyqueue.obj `if test -f 'tinyqueue.c'; then $(CYGPATH_W) 'tinyqueue.c'; else $(CYGPATH_W) '$(srcdir)/tinyqueue.c'; fi`
install-dist_dataDATA: $(dist_data_DATA)
	@$(NORMAL_INSTALL)
	@list='$(dist_data_DATA)'; test -n "$(datadir)" || list=; \
	if test -n "$$list"; then \
	  echo " $(MKDIR_P) '$(DESTDIR)$(datadir)'"; \
	  $(MKDIR_P) "$(DESTDIR)$(datadir)" || exit 1; \
	fi; \
	for p in $$list; do \
	  if test -f "$$p"; then d=; else d="$(srcdir)/"; fi; \
	  echo "$$d$$p"; \
	done | $(am__base_list) | \
	while read files; do \
	  echo " $(INSTALL_DATA) $$files '$(DESTDIR)$(datadir)'"; \
	  $(INSTALL_DATA) $$files "$(DESTDIR)$(datadir)" || exit $$?; \
	done

uninstall-dist_dataDATA:
	@$(NORMAL_UNINSTALL)
	@list='$(dist_data_DATA)'; test -n "$(datadir)" || list=; \
	files=`for p in $$list; do echo $$p; done | sed -e 's|^.*/||'`; \
	dir='$(DESTDIR)$(datadir)'; $(am__uninstall_files_from_dir)

ID: $(HEADERS) $(SOURCES) $(LISP) $(TAGS_FILES)
	list='$(SOURCES) $(HEADERS) $(LISP) $(TAGS_FILES)'; \
	unique=`for i in $$list; do \
	    if test -f "$$i"; then echo $$i; else echo $(srcdir)/$$i; fi; \
	  done | \
	  $(AWK) '{ files[$$0] = 1; nonempty = 1; } \
	      END { if (nonempty) { for (i in files) print i; }; }'`; \
	mkid -fID $$unique
tags: TAGS

TAGS:  $(HEADERS) $(SOURCES)  $(TAGS_DEPENDENCIES) \
		$(TAGS_FILES) $(LISP)
	set x; \
	here=`pwd`; \
	list='$(SOURCES) $(HEADERS)  $(LISP) $(TAGS_FILES)'; \
	unique=`for i in $$list; do \
	    if test -f "$$i"; then echo $$i; else echo $(srcdir)/$$i; fi; \
	  done | \
	  $(AWK) '{ files[$$0] = 1; nonempty = 1; } \
	      END { if (nonempty) { for (i in files) print i; }; }'`; \
	shift; \
	if test -z "$(ETAGS_ARGS)$$*$$unique"; then :; else \
	  test -n "$$unique" || unique=$$empty_fix; \
	  if test $$# -gt 0; then \
	    $(ETAGS) $(ETAGSFLAGS) $(AM_ETAGSFLAGS) $(ETAGS_ARGS) \
	      "$$@" $$unique; \
	  else \
	    $(ETAGS) $(ETAGSFLAGS) $(AM_ETAGSFLAGS) $(ETAGS_ARGS) \
	      $$unique; \
	  fi; \
	fi
ctags: CTAGS
CTAGS:  $(HEADERS) $(SOURCES)  $(TAGS_DEPENDENCIES) \
		$(TAGS_FILES) $(LISP)
	list='$(SOURCES) $(HEADERS)  $(LISP) $(TAGS_FILES)'; \
	unique=`for i in $$list; do \
	    if test -f "$$i"; then echo $$i; else echo $(srcdir)/$$i; fi; \
	  done | \
	  $(AWK) '{ files[$$0] = 1; nonempty = 1; } \
	      END { if (nonempty) { for (i in files) print i; }; }'`; \
	test -z "$(CTAGS_ARGS)$$unique" \
	  || $(CTAGS) $(CTAGSFLAGS) $(AM_CTAGSFLAGS) $(CTAGS_ARGS) \
	     $$unique

GTAGS:
	here=`$(am__cd) $(top_builddir) && pwd` \
	  && $(am__cd) $(top_srcdir) \
	  && gtags -i $(GTAGS_ARGS) "$$here"

distclean-tags:
	-rm -f TAGS ID GTAGS GRTAGS GSYMS GPATH tags

distdir: $(DISTFILES)
	@srcdirstrip=`echo "$(srcdir)" | sed 's/[].[^$$\\*]/\\\\&/g'`; \
	topsrcdirstrip=`echo "$(top_srcdir)" | sed 's/[].[^$$\\*]/\\\\&/g'`; \
	list='$(DISTFILES)'; \
	  dist_files=`for file in $$list; do echo $$file; done | \
	  sed -e "s|^$$srcdirstrip/||;t" \
	      -e "s|^$$topsrcdirstrip/|$(top_builddir)/|;t"`; \
	case $$dist_files in \
	  */*) $(MKDIR_P) `echo "$$dist_files" | \
			   sed '/\//!d;s|^|$(distdir)/|;s,/[^/]*$$,,' | \
			   sort -u` ;; \
	esac; \
	for file in $$dist_files; do \
	  if test -f $$file || test -d $$file; then d=.; else d=$(srcdir); fi; \
	  if test -d $$d/$$file; then \
	    dir=`echo "/$$file" | sed -e 's,/[^/]*$$,,'`; \
	    if test -d "$(distdir)/$$file"; then \
	      find "$(distdir)/$$file" -type d ! -perm -700 -exec chmod u+rwx {} \;; \
	    fi; \
	    if test -d $(srcdir)/$$file && test $$d != $(srcdir); then \
	      cp -fpR $(srcdir)/$$file "$(distdir)$$dir" || exit 1; \
	      find "$(distdir)/$$file" -type d ! -perm -700 -exec chmod u+rwx {} \;; \
	    fi; \
	    cp -fpR $$d/$$file "$(distdir)$$dir" || exit 1; \
	  else \
	    test -f "$(distdir)/$$file" \
	    || cp -p $$d/$$file "$(distdir)/$$file" \
	    || exit 1; \
	  fi; \
	done
check-am: all-am
check: check-am
all-am: Makefile $(PROGRAMS) $(DATA)
installdirs:
	for dir in "$(DESTDIR)$(bindir)" "$(DESTDIR)$(datadir)"; do \
	  test -z "$$dir" || $(MKDIR_P) "$$dir"; \
	done
install: install-am
install-exec: install-exec-am
install-data: install-data-am
uninstall: uninstall-am

install-am: all-am
	@$(MAKE) $(AM_MAKEFLAGS) install-exec-am install-data-am

installcheck: installcheck-am
install-strip:
	if test -z '$(STRIP)'; then \
	  $(MAKE) $(AM_MAKEFLAGS) INSTALL_PROGRAM="$(INSTALL_STRIP_PROGRAM)" \
	    install_sh_PROGRAM="$(INSTALL_STRIP_PROGRAM)" INSTALL_STRIP_FLAG=-s \
	      install; \
	else \
	  $(MAKE) $(AM_MAKEFLAGS) INSTALL_PROGRAM="$(INSTALL_STRIP_PROGRAM)" \
	    install_sh_PROGRAM="$(INSTALL_STRIP_PROGRAM)" INSTALL_STRIP_FLAG=-s \
	    "INSTALL_PROGRAM_ENV=STRIPPROG='$(STRIP)'" install; \
	fi
mostlyclean-generic:

clean-generic:

distclean-generic:
	-test -z "$(CONFIG_CLEAN_FILES)" || rm -f $(CONFIG_CLEAN_FILES)
	-test . = "$(srcdir)" || test -z "$(CONFIG_CLEAN_VPATH_FILES)" || rm -f $(CONFIG_CLEAN_VPATH_FILES)

maintainer-clean-generic:
	@echo "This command is intended for maintainers to use"
	@echo "it deletes files that may require special tools to rebuild."
clean: clean-am

clean-am: clean-binPROGRAMS clean-generic mostlyclean-am

distclean: distclean-am
	-rm -rf ./$(DEPDIR)
	-rm -f Makefile
distclean-am: clean-am distclean-compile distclean-generic \
	distclean-tags

dvi: dvi-am

dvi-am:

html: html-am

html-am:

info: info-am

info-am:

install-data-am: install-dist_dataDATA

install-dvi: install-dvi-am

install-dvi-am:

install-exec-am: install-binPROGRAMS

install-html: install-html-am

install-html-am:

install-info: install-info-am

install-info-am:

install-man:

install-pdf: install-pdf-am

install-pdf-am:

install-ps: install-ps-am

install-ps-am:

installcheck-am:

maintainer-clean: maintainer-clean-am
	-rm -rf ./$(DEPDIR)
	-rm -f Makefile
maintainer-clean-am: distclean-am maintainer-clean-generic

mostlyclean: mostlyclean-am

mostlyclean-am: mostlyclean-compile mostlyclean-generic

pdf: pdf-am

pdf-am:

ps: ps-am

ps-am:

uninstall-am: uninstall-binPROGRAMS uninstall-dist_dataDATA

.MAKE: install-am install-strip

.PHONY: CTAGS GTAGS all all-am check check-am clean clean-binPROGRAMS \
	clean-generic ctags distclean distclean-compile \
	distclean-generic distclean-tags distdir dvi dvi-am html \
	html-am info info-am install install-am install-binPROGRAMS \
	install-data install-data-am install-dist_dataDATA install-dvi \
	install-dvi-am install-exec install-exec-am install-html \
	install-html-am install-info install-info-am install-man \
	install-pdf install-pdf-am install-ps install-ps-am \
	install-strip installcheck installcheck-am installdirs \
	maintainer-clean maintainer-clean-generic mostlyclean \
	mostlyclean-compile mostlyclean-generic pdf pdf-am ps ps-am \
	tags uninstall uninstall-am uninstall-binPROGRAMS \
	uninstall-dist_dataDATA

#override CFLAGS=-O0 -g

##override CFLAGS=-mtune=generic -O0 -g
#override CFLAGS=-mtune=generic

# Tell versions [3.59,3.63) of GNU make to not export all variables.
# Otherwise a system limit (for SysV at least) may be exceeded.
.NOEXPORT:
