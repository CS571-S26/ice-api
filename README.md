build
```bash
docker build . -t ctnelson1997/cs571-s26-ice-api
docker push ctnelson1997/cs571-s26-ice-api
```

run
```bash
docker pull ctnelson1997/cs571-s26-ice-api
docker run --name=cs571_s26_ice_api -d --restart=always -p 59999:59999 -v /cs571/s26/ice:/cs571 ctnelson1997/cs571-s26-ice-api
```
