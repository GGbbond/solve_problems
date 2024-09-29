删除系统中所有的fmt，确保只有一个用```sudo apt install libfmt-dev```安装的fmt(注意残留的静态库)
在armor_detector.cpp中加入```#include <fmt/format.h>```
