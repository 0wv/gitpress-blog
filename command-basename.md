---
title: basenameコマンドのつかいかた
date: 2021/6/10 21:57:00
---

# basename

ファイルパスからファイル名を抜き出します。

## イディオム

```
basename [ファイルパス]
```

## こんな時に使う

### `ab/cd/ef`からファイル名を抜き出したい！

```sh
basename ab/cd/ef # => ef
```