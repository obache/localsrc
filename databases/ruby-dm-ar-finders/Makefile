# $NetBSD: Makefile,v 1.2 2017/07/30 22:32:12 wiz Exp $

DISTNAME=	dm-ar-finders-1.2.0
CATEGORIES=	databases

MAINTAINER=	pkgsrc-users@NetBSD.org
HOMEPAGE=	https://github.com/datamapper/dm-ar-finders
COMMENT=	DataMapper plugin providing ActiveRecord-style finders
LICENSE=	mit

DEPENDS+=	${RUBY_PKGPREFIX}-dm-core>=1.2.0<1.3:../../databases/ruby-dm-core

.include "../../lang/ruby/gem.mk"
.include "../../mk/bsd.pkg.mk"
