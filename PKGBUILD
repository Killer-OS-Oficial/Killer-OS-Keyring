pkgname=killer-os-keyring
pkgver=stable
pkgrel=1
pkgdesc='Killer-OS PGP Keyring'
arch=('x86_64')
url='https://github.com/ctlos/ctlos-keyring'
license=('GPL')
install="${pkgname}.install"
source=('Makefile'
        'killeros.gpg'
        'killeros-revoked'
        'killeros-trusted')
sha256sums=('SKIP'
            'SKIP'
            'SKIP'
            'SKIP')

package() {
  cd "${srcdir}"
  make PREFIX=/usr DESTDIR=${pkgdir} install
}
