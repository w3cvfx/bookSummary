```
  __
 / /_
| '_ \
| (_) |
 \___/
```
# <span style="color:red;">6.Bölüm</span>
## <span style="color:green;">print()</span>
* dosyalı programlarda yazmak için kullanır.
* birden fazla parametre alabilir.
* **,** koyup yeni satra devam edilebilir.

### sep
* parametrelerin arasına yerleştirilen.
* **None** " "

### end
* sonuna yerleştirilen.
* **None** /n

### file
* çıktı dosyaya yazdırmak

```python
>>> f = open("file.txt", "w")
>>> print("Im writing Now!", file=f)
>>> f.close()
```

* **None** sys.stdout
* kapatmasına kadar tamponda bekler.

### flush
* boşaltmak durumu
* **True** dosya kapatmadan yazar.
* **False** dosya kapatmasına bekler.

### Yıldız *
* parçalara ayırarak -*öğeleri*- **Print()**'e yollar.

```python
>>> print(*"Hello")
```



## <span style="color:green">open()</span>

* dosya oluşturmak için

```python
>>> open("test.txt", "w")
```
## <span style="color:green">sys.stdout</span>
### Çıtkı dosyaya **ayarlamak**

```python
>>> f = open("profile", "w");
>>> import sys; sys.stdout=f
>>> "Ali, Muhammed"
>>> f.close()
```
* kapatmadan yazdırıyor.
* **None** <span style="color:orange">sys.stdout=sys.__ stdout __</span> *boşlukYok!*
	* sys.stdout.name
	* sys.stdout.mode
	* sys.stdout.encoding

* **eski haline döndürmek**:

```python
>>> import sys
>>> f = open("dosya.txt", "w")
>>> sys.stdout, f = f, sys.stdout 
>>> print("deneme", flush=True) 
>>> f, sys.stdout = sys.stdout, f 
>>> print("deneme")
```




## <span style="color:green;">hangi dizideyim?</span>
```python
>>> import os
>>> os.getcwd()
```

## <span style="color:green;">Tırnak Türleri?</span>
### Tek tırnak
### Çift tırnak
### Üç tırnak
* birden fazla satıra karakter dizilere kullanılır.

## <span style="color:green;">Modül</span>
* bir modül kullanmadan onu aktarmak gerekirir.