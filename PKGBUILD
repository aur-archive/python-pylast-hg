# Maintainer: Kacper Żuk <kacper.b.zuk+aur@gmail.com>

_pkgname=python-pylast
pkgname=$_pkgname-hg
provides=$_pkgname
pkgver=20140513
pkgrel=1
pkgdesc="a python interface to last.fm (and other api-compatible websites) (python3 package)"
arch=(any)
url="https://code.google.com/p/pylast/"
license=('Apache')
makedepends=('mercurial')
depends=('python')
options=(!emptydirs)
source=("$_pkgname"::hg+https://code.google.com/p/pylast/)
md5sums=('SKIP')

package() {
  cd "$srcdir/$_pkgname"
  python3 setup.py install --root="$pkgdir/" --optimize=1
}

# vim:set ts=2 sw=2 et:
