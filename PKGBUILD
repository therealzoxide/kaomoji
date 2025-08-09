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
source=("https://github.com/therealzoxide/archdots/releases/download/v0.2/kaomoji.tar.xz")

package() {
  install -Dm755 -t "${pkgdir}/usr/bin" kaomoji
}
sha256sums=('9042028671fe1446c5e9e05d234279c0cb6b3f4c60e8c87876471085a2309639')
