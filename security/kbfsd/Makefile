# $FreeBSD$

PORTNAME=	kbfsd
DISTVERSIONPREFIX=	v
DISTVERSION=	0.4.0
CATEGORIES=	security
MASTER_SITES=	#
DISTFILES=	#
EXTRACT_ONLY=	#

MAINTAINER=	0mp@FreeBSD.org
COMMENT=	Service daemon for the Keybase filesystem (KBFS)

# There is no license file.
LICENSE=	BSD2CLAUSE

USE_RC_SUBR=	kbfsd
NO_ARCH=	yes
NO_BUILD=	yes
NO_INSTALL=	yes

RUN_DEPENDS=	kbfsfuse:security/kbfs \
		keybase:security/keybase

.include <bsd.port.mk>
