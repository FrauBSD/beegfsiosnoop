############################################################ IDENT(1)
#
# $Title: Makefile for installing beegfsiosnoop $
# $Copyright: 2020 Devin Teske. All rights reserved. $
# $FrauBSD: beegfsiosnoop/GNUmakefile 2020-04-17 15:32:58 -0700 freebsdfrau $
#
############################################################ CONFIGURATION

DESTDIR=	
BINDIR=		$(DESTDIR)/usr/bin

############################################################ PATHS

CP_F=		cp -f
MKDIR_P=	mkdir -p
RM_F=		rm -f

############################################################ OBJECTS

PROG=		beegfsiosnoop

############################################################ TARGETS

all:
	@printf "Options:\n"
	@printf "\tmake install\tInstall $(PROG)\n"
	@printf "\tmake uninstall\tUninstall $(PROG)\n"

install:
	$(MKDIR_P) $(BINDIR)
	$(CP_F) $(PROG) $(BINDIR)/

uninstall:
	$(RM_F) $(BINDIR)/$(PROG)

################################################################################
# END
################################################################################
