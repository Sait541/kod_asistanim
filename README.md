Proje Yazarı: Muhammed Said Toruk
# Projenin adı: Kod-Asistan v0.1

## Projenin Amacı: 
Kullanıcılara günlük işlerinde (hesaplama, selamlama vb.) yardımcı olacak bir dijital asistan tasarlamak.

## Projenin Hedefleri:
* **v0.1:** Temel selamlama, kullanıcı adı alma ve basit matematiksel hesaplama işlemlerini gerçekleştiren konsol altyapısının kurulması.
* **v0.5:** Kullanıcıdan gelen girdileri analiz ederek farklı modüllere yönlendiren dinamik komut işleme mekanizmasının eklenmesi.
* **v1.0 (Akıllı Menü):** Kullanıcının sık kullandığı işlemlere tek tuşla ulaşmasını sağlayan gelişmiş bir akıllı menü sisteminin entegre edilmesi.
* **v2.0 (Veri Saklama):** Yapılan işlemlerin ve kullanıcı tercihlerinin harici bir dosyada veya veritabanında kalıcı olarak saklanması (veri kalıcılığı).

## Projenin Kapsamı (Algoritma Adımları):
* **Adım 1:** Başla.
* **Adım 2:** Ekrana "Kod-Asistan v0.1 Hoş Geldiniz" mesajını yazdır.
* **Adım 3:** Kullanıcıdan adını girmesini iste (KullaniciAdi).
* **Adım 4:** Eğer KullaniciAdi boş ise KullaniciAdi = "Misafir" yap.
* **Adım 5:** Kullanıcıya ana menü seçeneklerini göster:
  1. Hesaplama Yap
  2. Selamla
  3. Çıkış
* **Adım 6:** Kullanıcıdan bir seçim al (Secim).
* **Adım 7:** Eğer Secim == 1 ise:
  * Kullanıcıdan iki sayı ve işlem türünü al.
  * İşlemi yap ve sonucu ekrana yazdır.
  * Adım 5'e dön.
* **Adım 8:** Eğer Secim == 2 ise:
  * Ekrana "Merhaba " + KullaniciAdi + ", harika bir gün dilerim!" yazdır.
  * Adım 5'e dön.
* **Adım 9:** Eğer Secim == 3 ise:
  * Ekrana "Çıkış yapılıyor..." yazdır.
  * Adım 11'e git.
* **Adım 10:** Eğer Secim geçersiz ise:
  * Ekrana "Hatalı seçim yaptınız, tekrar deneyiniz!" yazdır.
  * Adım 5'e dön.
* **Adım 11:** Bitir.

---

## Kaynakça
1. Millî Eğitim Bakanlığı, *Bilişim Teknolojileri Alanı - Programlama Temelleri Ders Kitabı*, Ankara.
2. MEGEP, *Bilişim Teknolojileri Modülleri ve Bireysel Öğrenme Materyalleri*, T.C. Millî Eğitim Bakanlığı.
