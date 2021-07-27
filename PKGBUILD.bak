# Maintainer: Rajan Pandey <pandey11rajan@gmail.com>

pkgname=heera-mirrorlist
pkgver=1
pkgrel=1
pkgdesc="heera mirror list  to install heera specific packages with pacman"
arch=('any')
url="https://github.com/heera-os/heera-mirrorlist"
license=('GPL')
backup=(etc/pacman.d/heera-mirrorlist)
source=(mirrorlist)

package() {
	mkdir -p "$pkgdir/etc/pacman.d"
	install -m644 "$srcdir/mirrorlist" "$pkgdir/etc/pacman.d/heera-mirrorlist"
}

sha256sums=('1b94370705a5f74165cd2cb05516d5b0874a751a02eb4cb0b0e6d7e412ec7c4b')
