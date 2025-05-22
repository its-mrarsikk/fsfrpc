# Maintainer: Marcel B <irpd6s1qp@mozmail.com>
pkgname=fsfrpc
pkgver=1.0.0
pkgrel=1
pkgdesc="Shows your proprietary package count in Discord Rich Presence"
license=('GPL')
arch=('any')
url="https://github.com/its-mrarsikk/fsfrpc"
depends=("python" "python-pypresence" "absolutely-proprietary")
source=("fsfrpc.py")
sha256sums=('700418c3e4a2cf2262b44d39b8063f320741164658bf4ebc4f47a6e939a0ade2')

package() {
	install -Dm755 "$srcdir/fsfrpc.py" "$pkgdir/usr/bin/fsfrpc"
}
