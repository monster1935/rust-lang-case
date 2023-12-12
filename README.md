# rust-lang-case
This repo is used for store some rust case.

## 运行

``` bash
cargo run
```

等同于

```bash
# 1. build 
cargo build 


# 2. run
./target/debug/run-lang-case
```

- 默认为debug模式，编译速度较快，运行速度较慢
- 可以使用 `cargo run --release` 这样性能会比较高

`cargo check` 是我们在代码开发过程中最常用的命令，它的作用很简单：快速的检查一下代码能否编译通过。