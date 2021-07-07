---
title: Gitpodのタイムゾーンを変える
date: 2021/07/07 19:58:34
---

# Gitpodのタイムゾーンを変える

## 手順

1. https://gitpod.io/variables に移動する。

2. "New Variable" を押す。

3. 次の変数を作成する。

| Name | Value | Scope |
| --- | --- | --- |
| TZ | Asia/Tokyo | \*/\* |

"Value" にタイムゾーン名が入ります。
日本標準時に設定する場合は "Asia/Tokyo" と入力します。
