# Maintainer: Thomas Berryhill <tb01110100@gmail.com>

pkgname=xkfetch-git
pkgver=0.7.1
pkgrel=1
pkgdesc="a fast and simple xkcd-fetching tool"
arch=('any')
url="https://github.com/tb01110100/xkfetch"
license=('MIT')
depends=('curl' 'feh' 'bc')
source=('git://github.com/tb01110100/xkfetch.git')
md5sums=('SKIP')
_gitname='xkfetch'

package() {
  cd "$_gitname" &&
  install -m 755 -D xkfetch "$pkgdir/usr/bin/xkfetch" &&
  install -m 644 -D LICENSE "$pkgdir/usr/share/licenses/xkfetch/LICENSE"
}
