############################################################ IDENT(1)
#
# $Title: Makefile for installing beegfsiosnoop $
# $Copyright: 2020 Devin Teske. All rights reserved. $
# $FrauBSD: beegfsiosnoop/GNUmakefile 2020-02-16 13:01:04 -0800 freebsdfrau $
#
############################################################ CONFIGURATION

DESTDIR=	
BINDIR=		$(DESTDIR)/usr/bin

############################################################ PATHS

CP_F=		cp -f
MKDIR_P=	mkdir -p
RM_F=		rm -f

############################################################ OBJECTS

BEEGFSIOSNOOP=	beegfsiosnoop

############################################################ TARGETS

all:
	@printf "Options:\n"
	@printf "\tmake install\tInstall beegfsiosnoop\n"
	@printf "\tmake uninstall\tUninstall beegfsiosnoop\n"

install:
	$(MKDIR_P) $(BINDIR)
	$(CP_F) $(BEEGFSIOSNOOP) $(BINDIR)/

uninstall:
	$(RM_F) $(BINDIR)/$(BEEGFSIOSNOOP)

################################################################################
# END
################################################################################
