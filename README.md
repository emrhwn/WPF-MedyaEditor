

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





<img width="1920" height="1080" alt="s" src="https://github.com/user-attachments/assets/078ea51b-b18a-4027-a967-b128197572d0" />
<img width="1920" height="1080" alt="kıf" src="https://github.com/user-attachments/assets/d1a509d2-179c-4456-ac2a-3340f118a5b2" />
<img width="1920" height="1080" alt="aav" src="https://github.com/user-attachments/assets/118ebec4-046b-40d8-9214-78a916daf033" />

##  Kullanılan Teknolojiler

- **C#**
- **WPF (Windows Presentation Foundation)**
- **ONNX Runtime** (`u2net.onnx`)
- **OpenCVSharp**
- **FFmpeg**
