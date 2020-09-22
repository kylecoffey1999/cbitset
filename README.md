# cbitset
[![Build Status](https://travis-ci.org/lemire/cbitset.png)](https://travis-ci.org/lemire/cbitset)

Simple bitset library in C. It includes fast functions
to compute cardinalities, unions, intersections...

- It is tiny: it is made of three files (two header files and one source file).
- It is tested.
- It is fast.

Usage in C:
```C
bitset_t * b = bitset_create();
bitset_set(b,10);
bitset_get(b,10);// returns true
```

To run tests:
```bash
make
./unit
```

Prerequisites: C11-compatible compiler (MSVC Users, please have a look at [C11 and C17 Standard Support Arriving in MSVC](https://devblogs.microsoft.com/cppblog/c11-and-c17-standard-support-arriving-in-msvc/)).

