# Sprint Boot Kubernetes Bazel

This repository is an example java [Spring Boot](https://spring.io/projects/spring-boot) web application built and deployed to [Kubernetes](https://kubernetes.io/) with [Bazel](https://bazel.build/)

Update or add dependencies with:
```sh
bazel run @unpinned_maven//:pin
```

Build with:
```sh
bazel build //src/main:com.example.hello
```

Test with:
```sh
bazel test //...
```
