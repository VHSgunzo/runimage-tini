# Maintainer: VHSgunzo <vhsgunzo.github.io>

pkgname='runimage-tini'
pkgver='0.20.0'
pkgrel='1'
pkgdesc='tini for RunImage container'
url='https://github.com/VHSgunzo/tini'
arch=('x86_64' 'aarch64')
license=('MIT')
options=(!strip)
provides=("tini=$pkgver-$pkgrel")
depends=('runimage-static')
source=("$url/releases/download/v$pkgver/tini-${CARCH}")
sha256sums=('SKIP')

package() {
  install -Dm755 "tini-${CARCH}" "${pkgdir}/var/RunDir/sharun/bin/tini"
}
