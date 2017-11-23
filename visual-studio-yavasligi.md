# Visual Studio hayvan gibi yavaşladığı zaman yapılacaklar

Aşağıdaki dizinlerin içini boşalt ve Visual Studio'yu yeniden başlat:

```
C:\Users\%USERNAME%\AppData\Local\Microsoft\WebSiteCache
C:\Users\%USERNAME%\AppData\Local\Temp\Temporary ASP.NET Files
```

Solution dizinindeki `.vs` dizinini silmenin de faydası olabiliyor.

**Dikkat:** `.vs` dizini silinince solution'daki açık dosyalar, projelerin collapsed/expanded olma durumu, loaded/unloaded projeler, region'ların collapsed/expanded olma durumları gibi biçimsel bilgiler de uçuyor.
