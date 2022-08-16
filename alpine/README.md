## Usage

Example usage with a CMake project:

```shell
docker run \
    -v $PWD:$PWD \
    -w $PWD \
    -e PACKAGES=libwhatever-dev \
    spritsail/alpine-cmake \
    sh -c 'mkdir build && cd build && cmake .. && make'
```
