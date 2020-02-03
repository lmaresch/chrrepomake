# This PKGBUILD is part of the VDR4Arch project [https://github.com/vdr4arch]

# Maintainer: Libor Maresch <github@maresch.family>
pkgname=chrrepomake
pkgver=0.0.1
pkgrel=1
pkgdesc="Tool to autobuild a set of PKGBUILDs in a chroot environment"
url="https://github.com/lmaresch/chrrepomake"
arch=('any')
license=('GPL2')
depends=('python' 'devtools' 'python-dateutil' 'python-pytz')


package() {
  cd $startdir
  install -m755 -d ${pkgdir}/usr/bin
  install -m755 chrrepomake ${pkgdir}/usr/bin
}

