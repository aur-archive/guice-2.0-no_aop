# Maintainer: Roy Lines <roy@roylines.co.uk>

pkgname=guice-2.0-no_aop
pkgver=2.0
pkgrel=2
pkgdesc="a lightweight dependency injection framework for Java, without AOP, suitable for Android"
arch=('any')
noextract=('${pkgname}.jar')

url="http://code.google.com/p/google-guice/"
license=('Apache')

source=("${pkgname}.jar::http://google-guice.googlecode.com/files/${pkgname}.jar")
md5sums=('e3b7459929fe55a8389ca77eaa47139c')

package() {
  cd "${srcdir}"
  install -Dm644 ${pkgname}.jar "${pkgdir}/usr/share/java/${pkgname}.jar"
}
