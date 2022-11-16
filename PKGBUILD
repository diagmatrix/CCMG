# PKGBUILD of CCMG

pkgname=otf-ccmg
pkgver=1.0
pkgrel=1
pkgdesc='A sans-serif font that uses the symbols of CCMG'
arch=('any')
url='https://github.com/diagmatrix/CCMG'
license=('GPL3')
source=("CCMG-${pkgver}.otf::https://github.com/diagmatrix/CCMG/blob/master/CCMG.otf")
sha256sums=('2272096ac4c2655b58c1d5f4969687b60f3a4db5d39ea9694ebd574775227cb9')

package() {
    install -dm 755 "${pkgdir}/usr/share/fonts/OTF"
    install -m 644 CCMG-${pkgver}.otf "${pkgdir}/usr/share/fonts/OTF/CCMG.otf"
}