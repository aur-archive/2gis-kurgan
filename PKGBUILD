# Contributor: max1m <mr[dot]mxm86[at]gmail[dot]com>
     
pkgname=2gis-kurgan
pkgver=74
pkgrel=1
pkgdesc="Map of Kurgan for 2GIS, May 2012"
arch=('i686' 'x86_64')
url="http://kurgan.2gis.ru/how-get/linux/"
license=('custom')
depends=('2gis>=3.6.0.2')
source=("http://download.2gis.ru/arhives/2GISData_Kurgan-${pkgver}.orig.zip")
md5sums=('8f454b0813dd1267b63f3bfe06a7a456')
     
build() {
     
   cd $startdir
     
# Installing to /opt/2gis
  install -D -m 644 ${startdir}/src/2gis/3.0/Data_Kurgan.dgdat "${startdir}/pkg/opt/2gis/kurgan.dgdat" || return 1
  install -D -m 644 ${startdir}/src/2gis/3.0/Plugins/DGisLan/Kurgan.dglf "${startdir}/pkg/opt/2gis/Plugins/DGisLan/Kurgan.dglf" || return 1
     
}

