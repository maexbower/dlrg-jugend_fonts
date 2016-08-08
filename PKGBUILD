# Maintainer: Maximilian Bauknecht <maximilian.bauknecht@gmail.com>
packager="Maximilian Bauknecht <maximilian.bauknecht@gmail.com>"
pkgname="dlrg-jugend_fonts"
pkgver=1.0
pkgrel=1
license=('custom')
pkgdesc="Installs the original DLRG-Jugend fonts from their Website"
url="http://layout.dlrg-jugend.de"
arch=(any)
depends=(fontconfig xorg-font-utils)
source=("http://layout.dlrg-jugend.de/content/schriften/DLRG-Jugend-Schriften.zip")
md5sums=("ed8a4bdb5e9c1b0bcfa9ba2373c30fa6")
install=$pkgname.install
build() {
	echo "Only for authorized people" > LICENSE
}

package() {
  install -Dm644 "LICENSE" "$pkgdir/usr/share/licenses/dlrg-jugend_fonts/license"
  install -Dm644 "DLRG-Jugend_Fonts/windows/DLRGJugendText.ttf" "$pkgdir/usr/share/fonts/DLRG-Jugend/DLRGJugendText.ttf"
  install -Dm644 "DLRG-Jugend_Fonts/windows/DLRGJugendText-Bold.ttf" "$pkgdir/usr/share/fonts/DLRG-Jugend/DLRGJugendText-Bold.ttf"
  install -Dm644 "DLRG-Jugend_Fonts/windows/DLRGJugendText-BoldItalic.ttf" "$pkgdir/usr/share/fonts/DLRG-Jugend/DLRGJugendText-BoldItalic.ttf"
  install -Dm644 "DLRG-Jugend_Fonts/windows/DLRGJugendText-Italic.ttf" "$pkgdir/usr/share/fonts/DLRG-Jugend/DLRGJugendText-Italic.ttf"
  install -Dm644 "DLRG-Jugend_Fonts/windows/DLRGJugendTitel-Bold.ttf" "$pkgdir/usr/share/fonts/DLRG-Jugend/DLRGJugendTitel-Bold.ttf"
  install -Dm644 "DLRG-Jugend_Fonts/windows/DLRGJugendTitelLeicht-Bold.ttf" "$pkgdir/usr/share/fonts/DLRG-Jugend/DLRGJugendTitelLeicht-Bold.ttf"
  install -Dm644 "DLRG-Jugend_Fonts/windows/DLRGJugendTitelLeicht-Regular.ttf" "$pkgdir/usr/share/fonts/DLRG-Jugend/DLRGJugendTitelLeicht-Regular.ttf"
  install -Dm644 "DLRG-Jugend_Fonts/windows/DLRGJugendTitel-Regular.ttf" "$pkgdir/usr/share/fonts/DLRG-Jugend/DLRGJugendTitel-Regular.ttf"
}
