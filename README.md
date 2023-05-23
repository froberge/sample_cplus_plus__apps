# Sample C++ programs running in Containers

Hello World writting in C++ and running inside a container.

This repo uses [Podman](https://podman.io/) which is the best free and open source container tools to `build` and `run` the container.


## Requirement
* An instance of Podman running in your terminal.

---

## Hello world example

In a terminal go to the `helloword` folder 

### How to Build.

This will build the container using the latest tag version.

```
podman build -t helloworld-cplus-plus .
```

### How to Run

```
podman run --name helloworld -it helloworld-cplus-plus
```

### How to Stop

```
podman stop helloword
```

```
podman rm helloword
```

---

## Pyramid example

In a terminal go to the `pyramid` folder 

### How to Build.

This will build the container using the latest tag version.

```
podman build -t pyramid-cplus-plus .
```

### How to Run

```
podman run --name pyramid -it pyramid-cplus-plus
```

### How to Stop

```
podman stop pyramid
```

```
podman rm pyramid
```

---