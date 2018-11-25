pkgname=patata
pkgver=6
pkgrel=1
pkgdesc="A pomodoro timer for the shell uses Taskwarrior"
arch=('any')
url="https://github.com/rrmelcer/patata"
license=('MIT')
depends=('alsa-utils'
         'task')
source=('patata.sh'
        'notification.wav'
        'LICENSE')
md5sums=('afb17063051076f016a4d64c487594a1'
         'b01bacb54937c9bdd831f4d4ffd2e31c'
         'a293b2ed2538166d3956653c2110cb2f')
package() {
	install -D $srcdir/patata.sh $pkgdir/usr/bin/$pkgname
	install -D -m644 $srcdir/LICENSE $pkgdir/usr/share/licenses/$pkgname/LICENSE
	install -D $srcdir/notification.wav $pkgdir/usr/lib/$pkgname/notification.wav
}
