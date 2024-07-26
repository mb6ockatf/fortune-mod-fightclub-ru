# Maintainer: mb6ockatf <mdddmmmm@yandex.ru>
# Contributor: mb6ockatf <github.com/mb6ockatf>

pkgname=fortune-mod-fightclub-ru
pkgver=1
pkgrel=1
pkgdesc="#fightclub fortune cookie file in Russian"
arch=('any')
license=('AGPL-3.0-or-later')
url="https://github.com/mb6ockatf"
depends=('fortune-mod')
groups=('fortune-mods')
source=('fightclub_ru')
sha256sums=('b417118353738c8c5c7aed26c7ffe3cd0ae0078dc234f839d4106c88e2af062f')

build() {
	strfile ${srcdir}/fightclub_ru ${srcdir}/fightclub_ru.dat
}

package() {
	  install -D -m644 ${srcdir}/fightclub_ru ${pkgdir}/usr/share/fortune/fightclub_ru
	  install -D -m644 ${srcdir}/fightclub_ru.dat ${pkgdir}/usr/share/fortune/fightclub_ru.dat
}
