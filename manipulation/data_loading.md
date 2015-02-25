# さまざまなデータの読み込み

## Excelシートを読み込む

パッケージを使うことで、excelファイルのシートを扱うことができるようになります。

`XLConnect`, `openxlsx`, `xlsx`

```r
# XLConnect
test <- readWorksheetFromFile("test.xls", sheet = 1)
```
