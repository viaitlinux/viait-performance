# Maintainer: Librewish <librewish@gmail.com>
# Maintainer: dr460nf1r3 <dr460nf1r3@garudalinux.org>

pkgname=performance-tweaks
pkgdesc='Tweaks to improve performance'
pkgver=1.0.1
pkgrel=1
arch=('any')
url="https://gitlab.com/garuda-linux/themes-and-settings/settings/$pkgname"
license=('GPL')
depends=('hdparm')   
makedepends=('coreutils')
source=("$pkgname-$pkgver.tar.gz::$url/-/archive/$pkgver/$pkgname-$pkgver.tar.gz")
sha256sums=('SKIP')
provides=('performance-tweaks')
conflicts=('performance-tweaks' 'powersave-tweaks' 'tlp' 'auto-cpufreq-git' 'thermald' 'precached-git')
install=$pkgname.install

package() {
    install -d $pkgdir/etc
    cp -rf $srcdir/$pkgname-$pkgver/etc $pkgdir
}
