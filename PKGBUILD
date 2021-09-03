pkgname=rebornos-lightdm-gtk-greeter-config
pkgver=1.0
pkgrel=1.1
pkgdesc="RebornOS config used in lightdm-gtk-greeter"
arch=('any')
url="https://gitlab.com/rebornos-team/rebornos-special-system-files/rebornos-lightdm-gtk-greeter-config"
license=('GPL3')
source=('lightdm.conf' 
        'lightdm-gtk-greeter.conf')
sha256sums=('9195405969b3fcc00d99d0a0ef1a6f659751dd9727cb2b330bde64ab5548f4ce'
            'bed727471444276a88b3383bd128ef990505c90d6f4fba8cb32179b11557c033')

package() {
  mkdir -p ${pkgdir}/etc/lightdm
  install -Dm644 ${srcdir}/lightdm.conf ${pkgdir}/etc/lightdm
  install -Dm644 ${srcdir}/lightdm-gtk-greeter.conf ${pkgdir}/etc/lightdm
}

