```
 ____
| ___|
|___ \
 ___) |
|____/
```
# 5.Bölüm

* <span style="color:blue">**interactive shell**</span> (etkileşimli kabuk)
   * çıkmak için:
```python
>>> quit();
>>> import sys; sys.exit();
```
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
	* 2     : *int*
	* 2.3   : *float*
	* 10+2j : *complex*

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
* Takas Etme 
```python
x, y = y, x
```

