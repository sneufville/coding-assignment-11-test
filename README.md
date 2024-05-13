Link to repository
https://github.com/sneufville/coding-assignment-11-test

## Instructions for running

# build image
```shell
docker build . -t "sneufville-coding-assign11-test:v1.0"
```

# run application container
```shell
docker run --name neufville_simon_coding_assignment11_test -dp 7775:7775 sneufville-coding-assign11-test:v1.0
```
