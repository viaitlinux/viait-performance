# Maintainer: Librewish <librewish@gmail.com>
# Maintainer: dr460nf1r3 <dr460nf1r3@garudalinux.org>

pkgname=performance-tweaks
pkgdesc='Tweaks to improve performance'
pkgver=2.0.0
pkgrel=1
arch=('any')
url="https://gitlab.com/garuda-linux/themes-and-settings/settings/$pkgname"
license=('GPL')
depends=('hdparm')
makedepends=('coreutils')
source=("$pkgname-$pkgver.tar.gz::$url/-/archive/$pkgver/$pkgname-$pkgver.tar.gz")
sha256sums=('SKIP')
conflicts=('powersave-tweaks' 'tlp' 'auto-cpufreq' 'thermald')
install=$pkgname.install

package() {
    install -d $pkgdir/usr/lib
    cp -rf $srcdir/$pkgname-$pkgver/usr $pkgdir
}
