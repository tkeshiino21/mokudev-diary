---
title: 恵比寿もくもく
category: "mokumoku"
cover: tokyo.jpg
author: Takeshi
---

![unsplash.com](./photo-1465070845512-2b2dbdc6df66.jpg)

## `XSSと動的サイトの脆弱性`

動的に生成されるWebサイトにおいて、
自分のスクリプトを挟み込むというハッキング技術。
その脆弱性と攻撃の両方をさす言語。
偽ページとか、偽リンクを作って情報を盗み取ることができる。

対策
・エスケープ処理

```javascript
import { createMuiTheme } from "material-ui/styles";
import Color from "color";
import colors from "./colors";
```

一方でアナログなハッキング手段もある。
社内にUSBを転がしておくとか、
ITに弱そうな人に宛ててメールを送るとか。
あるいは、お金を積むとか。
いくらセキュアーなコードを書こうと頑張ってもそういうところから漏れたら意味ないので、
社内の人の情報リテラシーを上げるために啓蒙していくこともまた
セキュリティエンジニアの仕事の1つだと仰っていた。
