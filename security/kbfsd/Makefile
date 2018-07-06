# $FreeBSD$

PORTNAME=	kbfsd
DISTVERSIONPREFIX=	v
DISTVERSION=	0.2.0
CATEGORIES=	security
MASTER_SITES=	#
DISTFILES=	#
EXTRACT_ONLY=	#

MAINTAINER=	0mp@FreeBSD.org
COMMENT=	Daemon for the Keybase filesystem (KBFS)

LICENSE=	BSD2CLAUSE

USE_RC_SUBR=	kbfsd
NO_BUILD=	yes
NO_INSTALL=	yes
NO_ARCH=	yes

RUN_DEPENDS=	kbfsfuse:security/kbfs \
		keybase:security/keybase

.include <bsd.port.mk>
