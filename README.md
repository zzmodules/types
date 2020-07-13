types
=====

> A variety of commonly used types from `stddef.h` for ZZ

## Installation

Add this to your `zz.toml` file:

```toml
[dependencies]
types = "*"

[repos]
types = "git://github.com/zzmodules/types"
```

## Usage

```c++
using types::{
  double,
  float,
  long,
  size_t,
  ssize_t,
  off_t,
  time_t,
}
```


## License

MIT
