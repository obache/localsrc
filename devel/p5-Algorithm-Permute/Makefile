# $NetBSD: Makefile,v 1.14 2021/05/24 19:50:04 wiz Exp $

DISTNAME=	Algorithm-Permute-0.16
PKGNAME=	p5-${DISTNAME}
PKGREVISION=	4
CATEGORIES=	devel perl5
MASTER_SITES=	${MASTER_SITE_PERL_CPAN:=Algorithm/}

MAINTAINER=	pkgsrc-users@NetBSD.org
HOMEPAGE=	https://metacpan.org/release/Algorithm-Permute
COMMENT=	Perl module for generating permutations with object oriented interface
LICENSE=	${PERL5_LICENSE}

# for make test
BUILD_DEPENDS+=	p5-Test-LeakTrace-[0-9]*:../../devel/p5-Test-LeakTrace

PERL5_PACKLIST=		auto/Algorithm/Permute/.packlist

.include "../../lang/perl5/module.mk"
.include "../../mk/bsd.pkg.mk"
