# Contributor: max1m <mr[dot]mxm86[at]gmail[dot]com>
     
pkgname=2gis-kurgan
pkgver=80
pkgrel=1
pkgdesc="Map of Kurgan for 2GIS, November 2012"
arch=('i686' 'x86_64')
url="http://kurgan.2gis.ru/how-get/linux/"
license=('custom')
depends=('2gis>=3.9.0.1')
source=("http://download.2gis.ru/arhives/2GISData_Kurgan-80.orig.zip")
md5sums=('eaddd2e72b57cac993dfc5ce58628352')
     
build() {
     
   cd $startdir
     
# Installing to /opt/2gis
  install -D -m 644 ${startdir}/src/2gis/3.0/Data_Kurgan.dgdat "${startdir}/pkg/opt/2gis/kurgan.dgdat" || return 1
  install -D -m 644 ${startdir}/src/2gis/3.0/Plugins/DGisLan/Kurgan.dglf "${startdir}/pkg/opt/2gis/Plugins/DGisLan/Kurgan.dglf" || return 1
     
}

