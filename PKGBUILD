pkgname=hello_world
pkgver=1.0
pkgrel=1
arch=(x86_64)
makedepends=(gcc)
source=("hello_world.c")

build() {
	gcc -o hello_world hello_world.c
}

package() {
	install -dm 755 "$pkgdir/usr/bin"
	install -m 755 hello_world "$pkgdir/usr/bin"
}
md5sums=('9e66513a924519bdf4ea27d73138a944')
