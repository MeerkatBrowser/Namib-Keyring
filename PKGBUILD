pkgname=namib-keyring
pkgver=1.0.0
pkgrel=1
pkgdesc='Namib PGP keyring'
arch=('any')
url='https://github.com/MeerkatBrowser/namib-keyring'
license=('GPL')
install="${pkgname}.install"
source=('Makefile'
        'namib.gpg'
        'namib-revoked'
        'namib-trusted')
        
sha256sums=('cef04e188946c509a1e63b29f6994b365c715b146a3939f1d3083460602d8f10'
            '8748c89f3aa33486911b4c902648f142c8faecc94bf6ee4c4c113cda541cdec7'
            'e16f1596201850fd4a63680b27f603cb64e67176159be3d8ed78a4403fdb1700'
            '9e7dc2bf1bf32f9b91a3a968375391252b65c259be2551e1f64be3af0b7f01b2')


package() {
	cd "${srcdir}"
	make PREFIX=/usr DESTDIR=${pkgdir} install
}
# -*- mode: bash;-*-
