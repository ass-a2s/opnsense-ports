# $FreeBSD$

PORTNAME=	scientific
PORTVERSION=	0.3.5.3
PORTREVISION=	2
CATEGORIES=	devel haskell

MAINTAINER=	haskell@FreeBSD.org
COMMENT=	Numbers represented using scientific notation

LICENSE=	BSD3CLAUSE

DEPRECATED=		Haskell libraries are getting pushed out of the ports tree. If you are using this port for development, consider switching to cabal sandboxes (old way), cabal new-build (new way), or use devel/stack. If you believe this port shouldn't be removed, contact haskell@FreeBSD.org
EXPIRATION_DATE=	2019-04-14

USE_CABAL=	hashable>=1.1.2 integer-logarithms vector

.include "${.CURDIR}/../../lang/ghc/bsd.cabal.mk"
.include <bsd.port.mk>
