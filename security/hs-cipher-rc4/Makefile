# $FreeBSD$

PORTNAME=	cipher-rc4
PORTVERSION=	0.1.4
PORTREVISION=	7
CATEGORIES=	security haskell

MAINTAINER=	haskell@FreeBSD.org
COMMENT=	Fast RC4 cipher implementation

LICENSE=	BSD3CLAUSE

DEPRECATED=		Haskell libraries are getting pushed out of the ports tree. If you are using this port for development, consider switching to cabal sandboxes (old way), cabal new-build (new way), or use devel/stack. If you believe this port shouldn't be removed, contact haskell@FreeBSD.org
EXPIRATION_DATE=	2019-04-14

USE_CABAL=	byteable crypto-cipher-types>=0.0.5

.include "${.CURDIR}/../../lang/ghc/bsd.cabal.mk"
.include <bsd.port.mk>
