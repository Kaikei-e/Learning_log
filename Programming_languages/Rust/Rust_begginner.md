# Summary of understanding about Rust : Rustの勉強についてのまとめ

## Rustとは

### 概要
- ベアメタル言語
- 2021現在でのスローガン：「効率的で信頼できるソフトウェアを誰もが作れる言語」

### 目標

それは安全性にある。
以下「詳解Rustプログラミング」p15 より
```markdown
- ぶら下がりポインタ
- データ競合
- バッファオーバーフロー
- イテレータの無効化
```
がある


## Rustに関する情報

### キーフレーズ、印象に残ったこと

「詳解Rustプログラミング」ｐ23より
```
Rustコミュニティは、「コンパイラの仕事の少ないシンプルな言語」より、
「コンパイラの仕事が多い比較的大きな言語」を好む。
Rustコンパイラは、プログラムのサイズとスピードの両方を積極的に最適化する。
```

### 理解できていないキーワード

少し理解が進んだら下の項目に移動する。

- ゼロコストの抽象(Rustの哲学)
- ヒープ
- スタック
- 共有参照
- 参照カウント
- ポインタ型
- セマンティクス
- データ指向プログラミング
- ディスパッチ(メソッドをディスパッチする)
- ライフタイム省略（lifetime elision）
- ハイジェニックマクロ(hygenic macro)
- 移動の意味(move semantics)
- 代数的データ型(algebric data types)
- デリファレンス（参照の目的、アドレスの目的が少しわかった。）


<br>

### 理解が深まったキーワード




### Reference

- "Rust in Action" by Tim McNamara
- 「詳解Rustプログラミング」 監修・訳 吉川邦夫　翔泳社　2021年11月
