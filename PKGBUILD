# Contributor & Maintainer: Acho Arnold <arnold@archlinux.info>

pkgname=sprungebash
pkgver=1
pkgrel=0
pkgdesc="A simple bash script to upload files to sprunge.us from the command line"
arch=("any")
license=('GPL3')
url="http://sprunge.us/"
depends=('bash' 'curl')
optdepends=('xsel: automatically putting the URL on the X selection  clipboard for easy pasting'
	'xclip: an alternative to xsel')
source=("./sprungebash.sh")
sha1sums=('ebcda703dc6967f3905eb9a7221f56c1b1130e6c')

build() {
	mkdir -p $pkgdir/usr/bin
	install sprungebash.sh $pkgdir/usr/bin/sprungebash -m 755 || return 1
}
