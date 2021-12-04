pkgname=add
pkgver=1
pkgrel=1
pkgdesc="Alternative Danish Dvorak"
arch=('i686' 'x86_64')
license=('WTFPL')
url='https://github.com/nikor/add'
source=('add')
md5sums=('4ffae14df38221ee788e2010f1d1d163')

package() {
    mkdir -p ${pkgdir}/usr/share/X11/xkb/symbols/
    install -Dm644 $startdir/add ${pkgdir}/usr/share/X11/xkb/symbols/ 
}
