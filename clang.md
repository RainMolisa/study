# clang相关
## 1 libclang安装
```
pip install libclang
```
## 2 clang安装
找一个llvm-project-15.0.4.src.tar.xz。然后解压，在这个目录里面创一个release 文件夹，然后再cd 到release文件夹下面
```
cmake -G "Unix Makefiles" -DLLVM_TARGETS_TO_BUILD=X86 -DCMAKE_BUILD_TYPE=Release -DLLVM_ENABLE_PROJECTS="clang;clang-tools-extra" ../llvm
```
```
make -j16
```

