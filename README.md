# MeanShift
# Yüz Takip Sistemi (MeanShift ile)

Bu proje, OpenCV kullanarak bir kamera görüntüsünde yüz algılama ve takip işlemini gerçekleştiren bir sistemdir. **Haar Cascade Classifier** ile yüz algılama yapılır ve **MeanShift** algoritması kullanılarak seçilen yüz video akışı boyunca takip edilir.

## Gereksinimler ve Kurulum
Projeyi çalıştırmak için aşağıdaki yazılımlar ve kütüphaneler gereklidir:
- Python 3.x
- OpenCV (`pip install opencv-python`)
- NumPy (`pip install numpy`)

Kurulum için:
1. Proje dosyasını indirin:
   ```bash
   git clone https://github.com/kullanıcı_adı/yuz-takip-sistemi.git
Gerekli kütüphaneleri yükleyin:
pip install opencv-python numpy

Kamera açıldığında sistem yüz algılama yapacak ve tespit edilen yüzü takip etmeye başlayacaktır.
Takip edilen yüz, ekranda bir dikdörtgenle gösterilecektir.
Programdan çıkmak için q tuşuna basın.
Proje Özeti
Yüz Algılama: İlk karede yüz algılama yapılır ve ilgi bölgesi (ROI) tanımlanır.
Histogram Hesaplama: Takip edilecek yüzün HSV histogramı oluşturulur.
MeanShift Takibi: Video boyunca yüz, MeanShift algoritması ile takip edilir.
Gerçek Zamanlı Görüntüleme: Ekranda takip edilen yüz canlı olarak gösterilir.
Bilinen Sorunlar
Yüz algılanamazsa program sonlanır.
Kötü aydınlatma koşulları veya düşük çözünürlüklü kameralar takip performansını olumsuz etkileyebilir.
