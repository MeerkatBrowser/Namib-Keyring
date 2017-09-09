pkgname=namib-keyring
pkgver=1.0.0
pkgrel=1
pkgdesc='Namib PGP keyring'
arch=('any')
url='https://github.com/MeerkatBrowser/namib-keyring'
license=('GPL')
sha256sums=('SKIP')
install="${pkgname}.install"
source=('Makefile'
        'namib.gpg'
        'namib-revoked'
        'namib-trusted')


package() {
	cd "${srcdir}"
	make PREFIX=/usr DESTDIR=${pkgdir} install
}
# -*- mode: bash;-*-
