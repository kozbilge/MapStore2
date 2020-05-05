[![Build Status](https://travis-ci.org/geosolutions-it/MapStore2.svg?branch=master)](https://travis-ci.org/geosolutions-it/MapStore2)
[![Coverage Status](https://coveralls.io/repos/github/geosolutions-it/MapStore2/badge.svg?branch=master)](https://coveralls.io/github/geosolutions-it/MapStore2?branch=master)
[![Codacy Badge](https://api.codacy.com/project/badge/Grade/1648d484427346e2877006dc287379b6)](https://app.codacy.com/app/geosolutions/MapStore2?utm_source=github.com&utm_medium=referral&utm_content=geosolutions-it/MapStore2&utm_campaign=badger)
[![Documentation Status](https://readthedocs.org/projects/mapstore2/badge/?version=latest)](https://mapstore.readthedocs.io/en/latest/?badge=latest)
[![Twitter URL](https://img.shields.io/twitter/url/https/twitter.com/fold_left.svg?style=social&label=Follow%20%40mapstore2)](https://twitter.com/mapstore2)
[![Twitter URL](https://img.shields.io/twitter/url/https/twitter.com/fold_left.svg?style=social&label=Follow%20%40GeoserverTR)](https://twitter.com/geoservertr)

MapStore
========
MapStore web haritalar yapabilmeniz için standart haritalama araçları(örn:[OpenLayers](http://openlayers.org/) and [Leaflet](http://leafletjs.com/)) kullanılarak oluşturulmuş bir frameworktür.

MapStore çeşitli örnek uygulamalara sahiptir:
 * MapViewer basit bir harita sergileme uygulamasıdır. Daha önce başka servislerle oluşturduğunuz haritaları sergilemenizi sağlar (Geoserver ya da GeoSore gibi servisler).
 * MapPublisher ise haritalari oluşturmanıza, kayıt etmenize ve paylaşmanıza olana sağlayan bir araçtır. Tıpkı OpenStreetMap, Google, MapQuest gibi karmaşık harita servisleri oluşturmanıza ve kurumunuzda kullanmanıza imkan tanır.

Detaylı bilgi için Geoserver Türkiye'de MapStore forumunu inceleyebilirsiniz: [MapStore](https://forum.geoserver.com.tr/mapstore).

İndirme (Download)
------------
Geoserver Türkiye ekibi tarafından incelenmiş son sürümü [buraya tıklayarak](https://github.com/kozbilge/MapStore2/archive/master.zip) indirebilirsiniz.

[Tüm Sürümler İçin GeoSolutions Sayfasını Ziyaret Ediniz](https://github.com/geosolutions-it/MapStore2/releases)

Hızlı Başlangıç
------------
MapStore yazılımını test etmeniz için iki farklı yol bulunuyor. Bunlardan birincisi [Docker](https://www.docker.com/) diğeri ise [Apache Tomcat](http://tomcat.apache.org/).
Her iki şekilde de nasıl kurulum yapılacağı hakkında sitemizden detaylı bilgi alabilirsiniz [Geoserver Türkiye](http://www.geoserver.com.tr/)

### Docker Kullanarak Yükleme

Docker hubundan son sürümü yükleyin:

`docker pull geosolutionsit/mapstore2`

`docker run --name mapstore -p8080:8080  geosolutionsit/mapstore2`

Bu adımları uyguladıktan sonra aşağıdaki bağlantıyı kullanarak MapStore'unuza erişim sağlayabilirsiniz.

[http://localhost:8080/mapstore](http://localhost:8080/mapstore)

Varsayılan admin kullanıcı adınız: admin
Varsayılan admin şifreniz: admin

### WAR Dosyası Kullanarak Tomcat Üzerinde Çalıştırma

MapStore dosyalarını indirdikten sorna sisteminizde kurulu olan Java web uygulama servisine dosyalarınızı yükleyin (bu işlem normalde "webapps" klasörüne kopyalayarak yapılabilir). 

Eğer sisteminizde bir Java Uygulama Yürütücüsü yoksa Tomcat'i bu amaçla kullanabilirsiniz. [Tomcat](https://tomcat.apache.org/download-70.cgi) bağlantısına tıklayarak indirmeniz mümkün.

Dosyalarınızı kopyaladıktan sonra MapStore'unuza aşağıdaki bağlantıdan erişebilirsiniz:

[http://localhost:8080/mapstore](http://localhost:8080/mapstore)

Varsayılan admin kullanıcı adınız: admin
Varsayılan admin şifreniz: admin

Documentation
-------------
You can find more documentation about how to build, install or develop with MapStore on the [documentation site](https://mapstore.readthedocs.io/en/latest/).

### Topluluk Desteği

Açık kaynak kodlu CBS yazılımlarına topluluk desteğini [Geoserver](https://www.geoserver.com.tr) adresinde bulunan [Geoserver Forum](https://www.geoserver.com.tr) adresinden alabilirsiniz.

### Profesyonel Destek

Şu an için resmi olarak profesyonel destek sağlayan yerli bir GeoSolutions ekibi bulunmamakla birlikte [Geoserver Türkiye](https://www.geoserver.com.tr) üzerinden bizimle iletişime geçmeniz halinde sizi GeoSolutions ekibiyle bağlantıya sokabiliriz.

[Geoserver Türkiye](https://www.geoserver.com.tr)
