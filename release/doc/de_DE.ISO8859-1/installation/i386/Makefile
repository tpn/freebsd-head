# $FreeBSD$
# $FreeBSDde: de-docproj/relnotes/de_DE.ISO8859-1/installation/i386/Makefile,v 1.2 2002/03/10 18:41:43 ue Exp $
# $Id: Makefile,v 1.3 2002/03/10 15:37:18 ue Exp $
# basiert auf: 1.4

RELN_ROOT?= ${.CURDIR}/../../..

DOC?= article
FORMATS?= html
INSTALL_COMPRESSED?= gz
INSTALL_ONLY_COMPRESSED?=

# SGML content
SRCS+=	article.sgml
SRCS+=	../common/artheader.sgml
SRCS+=	../common/abstract.sgml
SRCS+=	../common/install.sgml
SRCS+=	../common/layout.sgml
SRCS+=	../common/trouble.sgml
SRCS+=	../common/upgrade.sgml

.include "${RELN_ROOT}/share/mk/doc.relnotes.mk"
.include "${DOC_PREFIX}/share/mk/doc.project.mk"
