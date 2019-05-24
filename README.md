# rxcpp-wrap-test

Clone rxcpp.

```shell
git clone --recursive -b v4.1.0 git@github.com:ReactiveX/RxCpp.git
```

Execute tests.

```shell
cp -r rxcpp/* RxCpp/
cd RxCpp
meson build
ninja -C build test
```
