# $NetBSD: Makefile,v 1.20 2021/05/24 19:55:33 wiz Exp $

DISTNAME=	HTML-StripScripts-1.06
PKGNAME=	p5-${DISTNAME}
PKGREVISION=	5
CATEGORIES=	www perl5
MASTER_SITES=	${MASTER_SITE_PERL_CPAN:=HTML/}

MAINTAINER=	bouyer@NetBSD.org
HOMEPAGE=	https://metacpan.org/release/HTML-StripScripts
COMMENT=	Perl5 module to strip scripting constructs out of HTML
LICENSE=	${PERL5_LICENSE}

PERL5_PACKLIST=	auto/HTML/StripScripts/.packlist

.include "../../lang/perl5/module.mk"
.include "../../mk/bsd.pkg.mk"
