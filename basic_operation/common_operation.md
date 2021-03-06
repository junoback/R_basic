# 常見運算

### 加減乘除

```r
> 1 + 2
[1] 3

> 1 - 2
[1] -1

> 1 * 2
[1] 2

> 1 / 2
[1] 0.5
```
### 次方、平方根、商數與餘數

```r
> 2 ^ 3  # 2 的 3 次方
[1] 8

> 2 ** 3 # 2 的 3 次方
[1] 8

> sqrt(4) # 4 的平方根
[1] 2

> 27 ^ (1/3) # 27 的立方根
[1] 3

> 11 %/% 5 # 11 除以 5 的商數
[1] 2

> 11 %% 5 # 11 除以 5 的餘數
[1] 1
```

註：# 為 R 的註解符號，並不會執行。

### sign：判斷是正、負數或 0

+ 正數回傳 1
+ 負數回傳 -1
+ 0 回傳 0

```r
> sign(10)
[1] 1

> sign(0)
[1] 0

> sign(-10)
[1] -1
```

### abs：取絕對值

```r
> abs(10)
[1] 10

> abs(0)
[1] 0

> abs(-10)
[1] 10
```

### log

```r
> log(10) # log 以 e 為底
[1] 2.302585

> log1p(9) # log(x) = log1p(x - 1)
[1] 2.302585

> log(10, 2) # 指定 log 以 2 為底
[1] 3.321928

> log2(10) # log2 代表以 2 為底
[1] 3.321928

> log10(10) # log10 代表以 10 為底
[1] 1

```

### exp

```r
> exp(10)
[1] 22026.47

> expm1(10) # expm1(x) = exp(x) - 1
[1] 22025.47
```
