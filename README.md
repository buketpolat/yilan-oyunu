# Yılan Oyunu (Snake Game)

Bu proje, Python'ın `turtle` kütüphanesi kullanılarak oluşturulmuş bir yılan oyunu uygulamasıdır. Amaç, yılanı kontrol ederek yemi toplamak ve yılanın kendi kuyruğuna veya oyunun sınırlarına çarpmasını önlemektir.

## İçindekiler (Table of Contents)

- [Özellikler (Features)](#özellikler-features)
- [Nasıl Çalıştırılır (How to Run)](#nasıl-çalıştırılır-how-to-run)
- [Kontroller (Controls)](#kontroller-controls)
- [Nasıl Oynanır (How to Play)](#nasıl-oynanır-how-to-play)

## Özellikler (Features)

- Basit ve sezgisel oynanış.
- Artan skor ve yüksek skor takibi.
- Yılanın yemi yedikçe uzaması.
- Oyun hızının (gecikme) yılan uzadıkça artması (azalması).
- Sınırlarla ve kendi kuyruğuyla çarpışma tespiti.
- Kullanıcı dostu arayüz.
- Klavye ile kolay kontrol.

## Nasıl Çalıştırılır (How to Run)

Bu oyunu çalıştırmak için bilgisayarınızda Python kurulu olması gerekmektedir.

1.  Bu GitHub deposunu bilgisayarınıza klonlayın veya dosyayı indirin.
    ```bash
    git clone <depo_url>
    ```
2.  Proje dizinine gidin.
    ```bash
    cd <proje_dizini>
    ```
3.  Oyun dosyasını çalıştırın.
    ```bash
    python yilan_oyunu.py
    ```

## Kontroller (Controls)

Oyunu kontrol etmek için aşağıdaki klavye tuşlarını kullanabilirsiniz:

- **Yukarı:** `W` veya `Yukarı Ok` tuşu
- **Aşağı:** `S` veya `Aşağı Ok` tuşu
- **Sağ:** `D` veya `Sağ Ok` tuşu
- **Sol:** `A` veya `Sol Ok` tuşu

Yılan, en son verilen komuta göre sürekli hareket eder. Aynı anda zıt yönde hareket etmek mümkün değildir (örneğin, yukarı giderken aniden aşağı gitmek).

## Nasıl Oynanır (How to Play)

1.  Oyunu başlatın.
2.  Klavye tuşlarını kullanarak yılanı hareket ettirin.
3.  Ekranda rastgele beliren kırmızı kareleri (yem) yemeye çalışın.
4.  Yılan her yem yediğinde uzar ve skorunuz artar. Oyunun hızı da hafifçe artar.
5.  Yılanın oyunun sınırlarına (duvarlara) veya kendi kuyruğuna çarpmasından kaçının. Çarpışma durumunda oyun sona erer.
6.  Oyun sonunda, elde ettiğiniz skor ve en yüksek skor görüntülenir. Yeni bir oyuna başlamak için pencereyi kapatıp tekrar çalıştırabilirsiniz.


1.  Bu depoyu fork edin.
2.  Kendi branch'inizi oluşturun (`git checkout -b feature/yeni-ozellik`).
3.  Değişikliklerinizi commit edin (`git commit -am 'Yeni özellik eklendi'`).
4.  Branch'inizi push edin (`git push origin feature/yeni-ozellik`).
5.  Pull Request oluşturun.
