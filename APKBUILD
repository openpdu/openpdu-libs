# Contributor: Paolo Asperti <paolo@asperti.com>
# Maintainer: Paolo Asperti <paolo@asperti.com>
pkgname=openpdu-libs
pkgver=0.1.0
pkgrel=1
pkgdesc="OpenPDU project - misc python libraries"
url="https://github.com/openpdu/openpdu-libs"
arch="noarch"
license="GPL2"
depends="python"
makedepends=""
subpackages=""
source=""
options="!check"

build() {
	:
}

package() {
	mkdir -p "$pkgdir"
	# create directory tree
	install -Dd usr "$pkgdir"/usr
	
	cp -r usr "$pkgdir"/
}
