```
 ____
| ___|
|___ \
 ___) |
|____/
```
# <span style="color:red;">5.Bölüm</span>

## <span style="color:green;font-weight:bold;">İnteractive Shell</span>
### çıkmak:
```python
>>> quit();
>>> import sys; sys.exit();
```
### son işlem
```python
>>> _
```
* **parametre**: fonksiyonların parantezleri içinde belirtilen değerlerdir.

## <span style="color:green;font-weight:bold;">Functions</span>
* **type()** verinin tipi.
* **len()** verinin uzunluğu.

## <span style="color:green;font-weight:bold;">String</span>
### birleşme
* **+** kullanmadan birleşebiliriz.

```python
>>> "ben " + "insanım"
>>> "ben " "insanım"
```
### tekrarlama:
```python
>>> "w" * 3
```
## <span style="color:green;">Number</span>

* **öncelik sırası** geçerlidir.

### Tipler
* **int**      : 2     
* **float**    : 2.3   
* **comples**  : 10+2j

### Kuvvet/Power
* kare bulmak için değeri kendisiyle çarpıyoruz.
```python
>>> x * x
```

#### ** işleci
```python
>>> 12 ** 2
```
#### pow()
```python
>>> pow(12, 2, 2)
```
* 3. parametre sonucuyla böler.


## <span style="color:green;">Variables</span>
* harf veya **_** işaretiyle başlamalı
* türkçe kullanabiliriz.
* adı kısa ve betimleyici olmalı

### yasaklı kelimeler
```python
>>> import keyword
>>> keyword.kwlist
```

### dilin fonksiyon adları kullanırsak o fonksiyon çalışmaz.
* *geri*:

```python
>>> del type
```

### aynı değer

```python
>>> a=b=7
```

### Takas Etme
```python
x, y = y, x
```

