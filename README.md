### Reproducer

To reproduce the problem:

```sh
cd package_2
pixi shell
```

It leads to the following error:

```sh
thread 'main2' panicked at crates/pixi_record/src/pinned_source.rs:266:73:
the workspace_root should be part of the source build path at this point: StripPrefixError(())
note: run with `RUST_BACKTRACE=1` environment variable to display a backtrace

thread 'main' panicked at crates/pixi/src/main.rs:49:10:
Tokio executor failed, was there a panic?: Any { .. }
```