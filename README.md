# Güç Seçenekleri Menüsü

![GucMenu](https://telegra.ph/file/1f89ce73f462ecc4e8548.png)

## Kurulum

> Görsellerle anlatım için [buraya](https://telegra.ph/G%C3%BC%C3%A7-Men%C3%BC-v10-01-16)

1. Rar'ın içindeki **psshutdown.exe** dosyasını `C:\Windows\System32` içine at.

2. Windows Arama yerine gel.

3. **Sistem ortam değişkenlerini düzenleyin** bunu arat ve gir.

4. **"Ortam Değişkenleri..."** yazan butona tıkla.

5. **Sistem değişkenleri** altındaki **Path** ifadesine tıkla ve **Düzenle** butonuna bas.

6. **Yeni** butonuna basarak `%SystemRoot%\System32\psshutdown.exe` ifadesini ekle ve **Tamam**'lara basarak her şeyi kapat.

7. Özelliği eklemek için **installer.reg** dosyasına çift tıkla ve her şeye **Evet** de.

8. İşlem tamamlandı. Herhangi bir yerde fare ile sağ tıkladığında **Güç Seçenekleri** yazan kısma gelip istediğin seçeneği seçebilirsin.
    - <ins>**Kapat:**</ins> Bilgisayarı kapatır.
    - <ins>**Uyku:**</ins> Bilgisayarı UYKU moduna alır.
    - <ins>**Yeniden Başlat:**</ins> Bilgisayarı yeniden başlatır.
    - <ins>**Yeniden Başlat (Gelişmiş Seçenekler):**</ins> Windows'un Gelişmiş Seçenekler kısmını açar.
    - <ins>**Oturumu Kapat:**</ins> Mevcut kullanıcının oturumunu kapatır.
    - <ins>**Hazırda Beklet:**</ins> Bilgisayarı HAZIRDA BEKLET moduna alır. Uykudan farkı daha az güç harcar ve bilgisayarı tamamen kapatır.
> Daha fazla bilgi için **Hazırda Beklet Nedir?** ifadesini Google'layın.

9. Güç Menü özelliğini kullanmak istemediğinizde **uninstaller.reg** dosyasına çift tıklayıp her şeye **Evet** de. Yeniden başlatmana gerek yok.
