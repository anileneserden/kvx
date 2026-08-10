# Maintainer: Anıl <anileneserden@gmail.com>
pkgname=kvx
pkgver=1.0.0
pkgrel=1
pkgdesc="KuvixOS Development and Build Tool"
arch=('any')
url="https://github.com/anileneserden/KuvixOS-V2"
license=('MIT')
depends=('python')
source=() # Yerel dosya kullanacağımız için şimdilik boş bırakıyoruz

package() {
    install -Dm755 "$startdir/kvx" "$pkgdir/usr/bin/kvx"
}
