# $FreeBSD$

PORTNAME=	SoapyPlutoSDR
DISTVERSIONPREFIX=	soapy-plutosdr-
DISTVERSION=	0.1.0
PORTREVISION=	1
CATEGORIES=	comms hamradio

MAINTAINER=	yuri@FreeBSD.org
COMMENT=	Soapy SDR plugin for PlutoSDR

LICENSE=	GPLv2
LICENSE_FILE=	${WRKSRC}/LICENSE

LIB_DEPENDS=	libiio.so:misc/libiio \
		libSoapySDR.so:misc/soapysdr

USES=		cmake compiler:c++11-lang pkgconfig
USE_GITHUB=	yes
GH_ACCOUNT=	pothosware

PLIST_FILES=	lib/SoapySDR/modules0.7/libPlutSDRSupport.so

.include <bsd.port.mk>
