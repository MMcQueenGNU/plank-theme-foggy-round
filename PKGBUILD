# Maintainer: McQueen <clear3239@yahoo.com>
_pkgname=plank-theme-foggy-round
pkgname=$_pkgname-git
pkgver=0.4
pkgrel=1
pkgdesc="Foggy-Round theme for Plank"
arch=('any')
url='https://www.gnome-look.org/p/1201603/'
license=('GPL3')
depends=('plank')
makedepends=('git')
source=("https://github.com/MMcQueenGNU/$_pkgname.git")
sha256sums=('ab8a9f1f9b2a34b54d8b180441945cd81254932c1942c5e61584de5668034109')

build() {
	true
}

package() {
	cd $srcdir/$_pkgname
	mkdir -p $pkgdir/usr/share/plank/themes/foggy-round
	install -m 755 dock.theme $pkgdir/usr/share/plank/themes/foggy-round/
}
