```
 ____
| ___|
|___ \
 ___) |
|____/
```
# <span style="color:red;font-weight:bold;">5.Bölüm</span>

* <span style="color:blue">**interactive shell**</span> (etkileşimli kabuk)
	* çıkmak için:
	```python
	>>> quit();
	>>> import sys; sys.exit();
	```
	* __*son işlem*__ _
* **parametre**: fonksiyonların parantezleri içinde belirtilen değerlerdir.

* **Veri tipi sorgulamak**:
```python
>>> type("string")
```

* **String**
    * *birleştirmek*
    ```python
    >>> "ben " + "insanım"
    >>> "ben " "insanım"
    ```
    * *Tekrarlamak*
    ```python
    >>> "w" * 3
    ```
* **Number**
	* **öncelik sırası** kurallını
geçerlidir.
	* kare bulmak için değeri kendisiyle çarpıyoruz.
	```python
	>>> kare * kare
	>>> a * a * ...
	```
	* 2     : *int*
	* 2.3   : *float*
	* 10+2j : *complex*
	* **Power** *(kuvvet)*
	* **
	```python
	>>> 12 ** 2
	144
	```
	* pow
	```python
	>>> pow(12, 2, 2)
	```
	> 144 sayısına böl, bölme işleminin kalanı 0'dır. yani 144 sayısı 2'ye tam bölünür.


* **String uzunluğu**
```python
len("Muhammed")
```

* **Variables**
	* harf veya **_** işaretiyle başlamalı
	* türkçe kullanabiliriz.
	* yasaklı kelimeler
	```python
	>>> import keyword
	>>> keyword.kwlist
	```
	* dilin fonksiyon adları kullanırsak o fonksiyon çalışmaz.
		* *geri*:
		```python
		>>> del type
		```
	* adı kısa ve betimleyici olmalı
	* **aynı** değere sahip değişkenler
```python
>>> a=b=7
```
* **Takas Etme**
```python
x, y = y, x
```

