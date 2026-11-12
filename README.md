# Cutest picture

Entry for [make.fun cutest-picture-01](https://make.fun/bounty/cutest-picture-01).

`main.ts` copies `entry.png` to the grader output. The file is a 1024 by 1024 JPEG of a kitten in a knitted blanket. The contest keeps the name `entry.png` and tells PNG from JPEG by the first bytes.

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out node --experimental-strip-types main.ts
```
