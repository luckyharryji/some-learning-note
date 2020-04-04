# Guide: using folly as 3rd party libary

put some node to write down the process to using folly as a independent developer

for macOS, `brew` can be used directly:


```
brew install folly 
```

then compile with clang or gcc:

```
clang++ test.cpp -std=c++14 -lfolly -lglog -ldl -ldouble-conversion -lpthread -o test
```