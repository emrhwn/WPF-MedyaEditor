
https://github.com/user-attachments/assets/9a687881-0dd0-4f8a-8d54-629bd492118f
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

<img width="1920" height="1080" alt="kıf" src="https://github.com/user-attachments/assets/985e7fa1-ba94-4720-bffe-f57e93fe2d01" />
<img width="720" height="1280" alt="as" src="https://github.com/user-attachments/assets/e5a327a2-51ae-4277-808a-bea691b04480" />
<img width="1920" height="1080" alt="aav" src="https://github.com/user-attachments/assets/d3b75b24-b732-4d29-8f65-6588cbd06928" />




##  Kullanılan Teknolojiler

- **C#**
- **WPF (Windows Presentation Foundation)**
- **ONNX Runtime** (`u2net.onnx`)
- **OpenCVSharp**
- **FFmpeg**
