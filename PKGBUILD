# Maintainer : Martin Wimpress <code@flexion.org>
# Contributor: Frederik "Freso" S. Olesen <freso.dk@gmail.com>

pkgname=networkmanager-dispatcher-rdpd
pkgver=1.0
pkgrel=2
pkgdesc="Dispatcher Script for xrdp"
arch=(any)
license=('MIT')
url="http://www.gnome.org/projects/NetworkManager"
depends=('networkmanager' 'xrdp-git')
backup=(etc/NetworkManager/dispatcher.d/10-rdpd)
changelog=ChangeLog
source=("10-rdpd")
sha256sums=('ccf01015cb19d43d5d21066c8715f76d431d675419a65e01a572ff73a486c654')

package() {
    install -Dm700 "${srcdir}/10-rdpd" "${pkgdir}/etc/NetworkManager/dispatcher.d/10-rdpd"
}
