# STRING (matn)

- \t - bo'shliq tashlaydi.
- \n - yangi qatordan boshlaydi.

## STRING METODLARI

**upper( )** - metodi mathdagi har bir harfni katta harfga o'zgartiradi.

```
ism = 'Ahad'
familya = 'Qayum'
ism_sharif = f"{ism} {familya}"
print(ism_sharif.upper())
```

**lower( )** - metodi matndagi har bir so'zning birinchi harfni katta harf bilan yozadi.

```
ism = 'Ahad'
familya = 'Qayum'
ism_sharif = f"{ism} {familya}"
print(ism_sharif.lower())
```

**title( )** - metodi matndagi har bir so'zning birinchi harfini katta harf bilan yozadi.

```
ism_sharif = 'james bond'
print(ism_sharif.title( ))
```

**capitalize( )** - esa faqatgina eng birinchi so'zning birinchi harfini katta bilan yozadi.

```
ism_sharif = 'james bond'
print(ism_sharif.capitalize())
```

- LSTIP( ) matn boshidagi bo'shliqnI
- RSTRIP( ) matn oxiridagi bo'shliqni,
- STRIP( ) matn boshi va oxiridagi bo'shliqlarni olib tashlaydi

```
meva = " olma "
print("Men " + meva.lstrip() + " yaxshi ko'raman")
print("Men " + meva.rstrip() + " yaxshi ko'raman")
print("Men " + meva.strip() + " yaxshi ko'raman")
print("Men " + meva + " yaxshi ko'raman")
```
