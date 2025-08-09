pkgname=kaomoji-menu
pkgver=0.2
pkgrel=1
pkgdesc="Kaomoji menu for bemenu on wayland with history"
arch=('any')
url="https://github.com/therealzoxide/kaomoji"
license=('MIT')
depends=(
	'bemenu-wayland'
	'wl-clipboard'
)
source=("https://github.com/therealzoxide/kaomoji/releases/download/v0.2/kaomoji.tar.xz")

package() {
  install -Dm755 -t "${pkgdir}/usr/bin" kaomoji
}
sha256sums=('1c9ff5205805f8d26540cbfcdc5bbf8090eaa1ee794334db7caa19d23ee925f8')
