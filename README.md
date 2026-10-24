Proje Yazarı: Anıl çahan
# Projenin Adı: Kod-Asistan v0.1
## Projenin Amacı: 
Kullanıcılara günlük işlerinde (hesaplama, selamlama vb.) yardımcı olacak bir dijital asistan tasarlamak
## Projenin Hedefleri: 
* Güvelik önlemlerini arttırmak.
* Akıllı menüler oluşturmak.
* Veri analizleri yapmak.
## Proje kapsamı:
**KRİTİK EŞİK Sözde Kod Mantığı:**

    saat = 1
    DÖNGÜ (Sürekli / Sensör verisi akışı bitene kadar):
        su_seviyesi = Sensörden_Gelen_Değer(saat)
        
        EĞER su_seviyesi > 50 İSE
            DÖNGÜYÜ_KIR (Döngüden çık)
        DEĞİLSE
            Kapaklar KAPALI tutulsun
            saat = saat + 1
        DÖNGÜ_SONU
        
    EKRANA_YAZDIR ("Tahliye Saati:", saat)
    EKRANA_YAZDIR ("Kritik Su Seviyesi:", su_seviyesi)
BİTİR

## Kaynakça:
*gemini
*ders kitabı
