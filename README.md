# Tennis Shop Service (C++)

## Pre-requisite


## VSCode CMake Extension

1. Select Kit: GCC 11.4
2. CMake: Quick Start: project name, executable or lib
3. select variant: debug, release, etc.
4. CMake: Configure
```shell
    [main] Configuring project: tennis-shop-cpp-service 
    [proc] Executing command: /usr/local/bin/cmake --no-warn-unused-cli -DCMAKE_BUILD_TYPE:STRING=Debug -DCMAKE_EXPORT_COMPILE_COMMANDS:BOOL=TRUE -DCMAKE_C_COMPILER:FILEPATH=/usr/bin/gcc -DCMAKE_CXX_COMPILER:FILEPATH=/usr/bin/g++ -S/home/xiao/tennis-shop-cpp-service -B/home/xiao/tennis-shop-cpp-service/build -G "Unix Makefiles"
```
5. CMake: Build
```shell
[proc] Executing command: /usr/local/bin/cmake --build /home/xiao/tennis-shop-cpp-service/build --config Debug --target all -j 18 --
[build] [ 50%] Linking CXX executable tennis-shop-cpp-service
[build] [100%] Built target tennis-shop-cpp-service

```

6. CMAKE: Debugging