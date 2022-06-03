# AprilTag Object Detection

AprilTag kütüphanesi kullanılarak geliştirilmiş python nesne tanıma uygulamasıdır. pupil-apriltags isimli python binding ve opencv kütüphanesi kullanılmıştır.

## Gereklilikler
-> Python 3.6 ve üzeri sürümleri
Proje ilk klonlandığından itibaren dosya dizinindeki terminale aşağıdaki komutları girerek gerekli paketleri indirebilirsiniz.

1.```pip install opencv-python```

2.```pip install pupil-apriltags```
        
Gerekli paketler başarıyla indirildikten sonra projeyi çalıştırmak için;

```python detection.py```

## Önemli Not
AprilTag binding veri seti sınırlı olduğu için sadece 'tag36h11' ailesini tanıyabilmektedir. Gerekli dosya pdf isimli klasörün içerisindedir.
