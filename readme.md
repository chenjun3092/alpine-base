InnoTech-alpine-basic
=====================

See the wiki  http://cfwiki.innotechapp.com/mediawiki/index.php/Docker_images to see how we build images.

Builds a alpine-basic image with extra packages installed (bash openssl curl) and compile and install monit in /opt/monit.

Basic config of monit its included, making able to copy monit conf files in /opt/monit/etc/conf.d or /opt/tools/conf.d


```
docker build -t <repo>/alpine-basic:<version> .
```

To run:

```
docker run -it <repo>/alpine-basic:<version> 
```

