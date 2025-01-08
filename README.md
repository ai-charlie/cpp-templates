# linux /macos下使用makefile运行c/c++模版

## 使用makefile构建可执行文件

```shell
make
# help：
# choose your compiler, e.g. gcc/clang
# example override to clang: make run CC=clang
# choose input c/c++ file
# example : make CFILES = A.cc B.cc C.cc
# modify result name
# example override : make run RESULT=main
```

## 使用make运行可执行文件

```shell
make run
```

## 使用makefile清除构建文件

```shell
make clear
```


# cmakelist

CMakeProject 文件夹下为CMakelist.txt的模版
