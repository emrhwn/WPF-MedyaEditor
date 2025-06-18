# WPF-MedyaEditor

 C# ve WPF kullanılarak geliştirilen bir masaüstü medya düzenleyici uygulaması. Kullanıcılar hem **videoları** hem de **fotoğrafları** düzenleyebilir; arka plan kaldırma, kırpma, segmentasyon gibi işlemleri gerçekleştirebilir.

##  Özellikler

-  **Fotoğraf düzenleme**:
  - Arka plan silme (U²-Net ONNX modeliyle)
  - Kırpma ve segmentasyon

-  **Video düzenleme**:
  - Videodan arka plan kaldırma (U²-Net ile)
  - Kesme/kırpma
  - Videoları birleştirme
  - Dışa aktarma (FFmpeg ile)

##  Kullanılan Teknolojiler

- **C#**
- **WPF (Windows Presentation Foundation)**
- **ONNX Runtime** (`u2net.onnx`)
- **OpenCVSharp**
- **FFmpeg**
