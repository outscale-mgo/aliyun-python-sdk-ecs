# Maintainer: Matthias gatto <matthias.gatto@outscale.com>
# Reference: PKGBUILD(5)

pkgname=aliyun-python-sdk-ecs
pkgver=4.19.9
pkgrel=1
pkgdesc='The ecs module of Aliyun Python sdk'

arch=('any')
url='https://github.com/aliyun/aliyun-openapi-python-sdk/'
license=(BSD)

makedepends=('python-pip')

package() {
	PIP_CONFIG_FILE=/dev/null pip install --isolated --root="$pkgdir" --ignore-installed --no-deps aliyun-python-sdk-ecs
}
