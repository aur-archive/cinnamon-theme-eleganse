# Maintainer: mwgg
# Contributor: Ner0

pkgname=cinnamon-theme-eleganse
pkgver=1.4
pkgrel=1
pkgdesc="Cinnamon theme based on Elegance"
url="http://cinnamon-spices.linuxmint.com/themes/view/20"
license=('GPL')
arch=('any')
depends=('cinnamon')
source=("http://cinnamon-spices.linuxmint.com/uploads/themes/UN31-2EID-Z236.zip")
md5sums=('cdb3e0ac53ff7ab890a851754114245b')

package() {
  find Eleganse/ -type f -exec install -Dm644 '{}' "$pkgdir/usr/share/themes/{}" \;
}
