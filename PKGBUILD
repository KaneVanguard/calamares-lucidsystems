# Maintainer: Kane Vanguard

pkgname=calamares-lucidsystems
pkgver=0.0.1
pkgrel=1
pkgdesc="LucidSystems configuration for the calamares installer"
arch=('i686' 'x86_64')
url="https://github.com/KaneVanguard/calamares-lucidsystems"
license=('GPL')
depends=('calamares')

package() {
  cd "$pkgdir"

  mkdir -p usr

  cp -R "$srcdir/etc" etc
  cp -R "$srcdir/usr/share" usr/share
}
