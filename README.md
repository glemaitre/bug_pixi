### Reproducer

To reproduce the problem:

```sh
cd package_2
pixi shell
```

It leads to the following error:

```sh
 │ ╭─ Packaging new files
 │ │ Copying done!
 │ │ Post-processing done!
 │ │ Writing test files
 │ │ Writing metadata for package
 │ │ Copying license files
 │ │
 │ ╰─────────────────── (took 1 second)
 │
 ╰─────────────────── (took 2 seconds)
Error:   × failed to build 'package_2' from '.'
  ╰─▶   × No license files were copied
```