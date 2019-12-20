# Demos


## Building Multi-Arch Images for Arm and x86 with Docker Desktop


```
docker buildx --help
```

```
docker buildx ls
```

```
docker buildx create --help
```

```
docker buildx create --name testbuild1
```


````
docker buildx inspect --bootstrap
```


```
docker logim
```


```
docker buildx build --platform linux/arm64,linux/arm/v7 -t ajeetraina/docker-cctv-raspbian --push .
```


#  CLI Tools

```
docker run --rm mplatform/mquery ajeetraina/docker-cctv-raspbian
```
