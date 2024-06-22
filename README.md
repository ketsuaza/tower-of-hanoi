# Tower-of-hanoi
This is a solver of tower-of-hanoi.


# Usage
## Requirements
 * C/C++ compiler (which can compile C++ 20)
 * CMake 3.5+

## Clean building project (manual)
```bash
❯ git submodule init && git submodule update
❯ rm -rf build && mkdir build
❯ cd build
❯ cmake ..
❯ make -j9 && make install
❯ cd ..
```
 
## Testing project (manual)
```bash
❯ ./bin/hanoi_solver_test
```

```bash
❯ ./bin/hanoi-main 3
```


# Lisence
MIT