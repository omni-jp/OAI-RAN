## OAI RAN向けConfig一覧
Open Mobile Network Infra Meetup 2の発表「OAI Master v1.2.2にスマホにつないだ結果」で使用した修正パッチになります．

- パッチの適用方法
```
openairinterface5g配下にパッチを格納
patch -p 1 < "パッチファイル名"
通常通りコンパイル
```

- BladeRF用のCompile error修正パッチ

BladeRF_compile.diff

- LimeSDR用のCompile error修正パッチ

LMSSDR_compile.diff

