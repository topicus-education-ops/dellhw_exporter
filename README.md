fix ldflags in `.promu.yml`

```
make crossbuild

tar cvzf dellhw_exporter-1.4.1.linux-amd64.tar.gz --transform 's,^,dellhw_exporter-1.4.1.linux-amd64/,S' --transform 's,.build/linux-amd64/,,' LICENSE NOTICE .build/linux-amd64/dellhw_exporter

sha256sum dellhw_exporter-1.4.1.linux-amd64.tar.gz > sha256sums.txt
```
