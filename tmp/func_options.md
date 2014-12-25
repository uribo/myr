# options関数

`options関数`はRを操作するうえの出力形式などを確認したり、変更する関数です。


```r
options
$add.smooth
[1] TRUE

$bitmapType
[1] "quartz"

...
```

設定できる項目は`?options`でも確認できます。また現在の設定は`options()`とすれば一覧が出力されます。

## 便利なもの

コンソールでの出力の長さを変更する

```r
options(width = N) # 10...10000
```

```r
options(digits = 7) # 数字の表示桁数
```
