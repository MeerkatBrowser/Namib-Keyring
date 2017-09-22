pkgname=namib-keyring
pkgver=17.09
pkgrel=1
pkgdesc='Namib PGP keyring'
arch=('any')
url='https://github.com/MeerkatBrowser/namib-keyring'
license=('GPL')
install="${pkgname}.install"
source=('Makefile'
        'namib.gpg'
        'namib-trusted')
        
sha256sums=('519c8f2342c616d7ba6c4c2571151c0748ec455e1f781578f86b070300ad50d6'
            '8748c89f3aa33486911b4c902648f142c8faecc94bf6ee4c4c113cda541cdec7'
            '9e7dc2bf1bf32f9b91a3a968375391252b65c259be2551e1f64be3af0b7f01b2')


package() {
	cd "${srcdir}"
	make PREFIX=/usr DESTDIR=${pkgdir} install
}
# -*- mode: bash;-*-
