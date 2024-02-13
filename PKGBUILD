pkgname=x11-dvorak
pkgver=0.0.1
pkgrel=1
pkgdesc="A script to restore dvorak layout after an X11 update"
arch=('any')
depends=('xkeyboard-config')
source=('us' 'x11-dvorak.hook')
sha256sums=('dc75288d77c3a8a50aaa936fe2d8d60d772dc475eddd1804a13cb9f515c2b38f' 'e1f74b79096d1c043ac60875258f810e5d63dd33997f45bc5cc7f48cfbf03a4f')
license=('BSD')

package() {
	install -Dm644 x11-dvorak.hook "$pkgdir/usr/share/libalpm/hooks/x11-dvorak.hook" 
	install -Dm644 us "$pkgdir/usr/share/x11-dvorak/us"
}
