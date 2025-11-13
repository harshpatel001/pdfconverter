# 🔄 PDF Converter

<div align="center">

![Python](https://img.shields.io/badge/Python-3.7+-blue.svg)
![License](https://img.shields.io/badge/License-MIT-green.svg)
![Platform](https://img.shields.io/badge/Platform-Windows%20%7C%20macOS%20%7C%20Linux-lightgrey.svg)
![Version](https://img.shields.io/badge/Version-1.0-orange.svg)

**A powerful and easy-to-use tool for converting multiple file formats to PDF**

[English](#english) | [Türkçe](#turkish)

</div>

---

<a name="english"></a>
## 🇬🇧 English

### 📖 Overview

PDF Converter is a cross-platform desktop application that allows you to convert various document and image formats into PDF files. With its intuitive GUI interface, you can easily convert single or multiple files and merge them into one PDF document.

### ✨ Features

- 🖼️ **Image to PDF**: Convert PNG, JPG, JPEG, BMP, GIF images to PDF
- 📄 **Document to PDF**: Convert DOC, DOCX, XLS, XLSX, PPT, PPTX, ODT, and more via LibreOffice
- 🔗 **Multi-file Merge**: Combine multiple files into a single PDF
- 💻 **Cross-platform**: Works on Windows, macOS, and Linux
- 🎯 **Simple Interface**: Easy-to-use GUI with file picker
- 📥 **Desktop Output**: Automatically saves to your desktop
- 🌐 **Turkish Interface**: Built-in Turkish language support

### 🚀 Installation

#### Prerequisites

1. **Python 3.7 or higher**
2. **LibreOffice** (for document conversion)
   - Windows: Download from [LibreOffice.org](https://www.libreoffice.org/)
   - macOS: `brew install --cask libreoffice`
   - Linux: `sudo apt-get install libreoffice` (Ubuntu/Debian)

#### Install Dependencies

```bash
# Clone the repository
git clone https://github.com/emillvl/pdfconverter.git
cd pdfconverter

# Install required Python packages
pip install Pillow PyPDF2
```

### 📝 Usage

```bash
python converter.py
```

**Steps:**
1. Run the script
2. Click "OK" on the welcome message
3. Select one or more files to convert
4. Enter a name for your PDF file
5. Find your converted PDF on the desktop!

### 📦 Supported Formats

#### Images
- PNG, JPG, JPEG, BMP, GIF

#### Documents (requires LibreOffice)
- Microsoft Office: DOC, DOCX, XLS, XLSX, PPT, PPTX
- OpenDocument: ODT, ODS, ODP
- Rich Text: RTF
- And many more formats supported by LibreOffice

### 🛠️ Requirements

```
Python >= 3.7
Pillow >= 8.0.0
PyPDF2 >= 2.0.0
tkinter (usually included with Python)
LibreOffice (for non-image files)
```

### 💡 Examples

**Convert multiple images to one PDF:**
```
Select: image1.png, image2.jpg, image3.png
Output: MyPhotos.pdf (on desktop)
```

**Convert Word documents:**
```
Select: report.docx, presentation.pptx
Output: Documents.pdf (merged into one)
```

### 🐛 Troubleshooting

**"LibreOffice not found" error:**
- Make sure LibreOffice is installed
- Windows: Check if installed in `C:\Program Files\LibreOffice`
- macOS: Check if installed in `/Applications/LibreOffice.app`
- Linux: Run `which soffice` to verify installation

**"PyPDF2 required" warning:**
- Install PyPDF2: `pip install PyPDF2`
- Required only for merging multiple non-image files

### 📄 License

Copyright © 2025 Emil Veliyev. All rights reserved.

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

### 👨‍💻 Author

**Emil Veliyev** - [@emillvl](https://github.com/emillvl)

### 🤝 Contributing

Contributions, issues, and feature requests are welcome!

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

### ⭐ Show Your Support

Give a ⭐ if this project helped you!

---

<a name="turkish"></a>
## 🇹🇷 Türkçe

### 📖 Genel Bakış

PDF Dönüştürücü, çeşitli belge ve resim formatlarını PDF dosyalarına dönüştürmenizi sağlayan platformlar arası bir masaüstü uygulamasıdır. Sezgisel GUI arayüzü ile tek veya birden fazla dosyayı kolayca dönüştürebilir ve bunları tek bir PDF belgesinde birleştirebilirsiniz.

### ✨ Özellikler

- 🖼️ **Resimden PDF'e**: PNG, JPG, JPEG, BMP, GIF resimlerini PDF'e dönüştürün
- 📄 **Belgeden PDF'e**: DOC, DOCX, XLS, XLSX, PPT, PPTX, ODT ve daha fazlasını LibreOffice ile dönüştürün
- 🔗 **Çoklu Dosya Birleştirme**: Birden fazla dosyayı tek bir PDF'de birleştirin
- 💻 **Platformlar Arası**: Windows, macOS ve Linux'ta çalışır
- 🎯 **Basit Arayüz**: Dosya seçici ile kullanımı kolay GUI
- 📥 **Masaüstü Çıktısı**: Otomatik olarak masaüstüne kaydeder
- 🌐 **Türkçe Arayüz**: Yerleşik Türkçe dil desteği

### 🚀 Kurulum

#### Ön Gereksinimler

1. **Python 3.7 veya üzeri**
2. **LibreOffice** (belge dönüştürme için)
   - Windows: [LibreOffice.org](https://tr.libreoffice.org/)'dan indirin
   - macOS: `brew install --cask libreoffice`
   - Linux: `sudo apt-get install libreoffice` (Ubuntu/Debian)

#### Bağımlılıkları Yükleyin

```bash
# Depoyu klonlayın
git clone https://github.com/emillvl/pdfconverter.git
cd pdfconverter

# Gerekli Python paketlerini yükleyin
pip install Pillow PyPDF2
```

### 📝 Kullanım

```bash
python converter.py
```

**Adımlar:**
1. Betiği çalıştırın
2. Hoş geldiniz mesajında "Tamam"a tıklayın
3. Dönüştürülecek bir veya daha fazla dosya seçin
4. PDF dosyanız için bir isim girin
5. Dönüştürülmüş PDF'inizi masaüstünde bulun!

### 📦 Desteklenen Formatlar

#### Resimler
- PNG, JPG, JPEG, BMP, GIF

#### Belgeler (LibreOffice gerektirir)
- Microsoft Office: DOC, DOCX, XLS, XLSX, PPT, PPTX
- OpenDocument: ODT, ODS, ODP
- Zengin Metin: RTF
- LibreOffice tarafından desteklenen daha birçok format

### 🛠️ Gereksinimler

```
Python >= 3.7
Pillow >= 8.0.0
PyPDF2 >= 2.0.0
tkinter (genellikle Python ile birlikte gelir)
LibreOffice (resim olmayan dosyalar için)
```

### 💡 Örnekler

**Birden fazla resmi tek PDF'e dönüştürme:**
```
Seçim: resim1.png, resim2.jpg, resim3.png
Çıktı: Fotograflarim.pdf (masaüstünde)
```

**Word belgelerini dönüştürme:**
```
Seçim: rapor.docx, sunum.pptx
Çıktı: Belgeler.pdf (tek dosyada birleştirilmiş)
```

### 🐛 Sorun Giderme

**"LibreOffice Bulunamadı" hatası:**
- LibreOffice'in yüklü olduğundan emin olun
- Windows: `C:\Program Files\LibreOffice` konumunu kontrol edin
- macOS: `/Applications/LibreOffice.app` konumunu kontrol edin
- Linux: Kurulumu doğrulamak için `which soffice` komutunu çalıştırın

**"PyPDF2 Gerekli" uyarısı:**
- PyPDF2'yi yükleyin: `pip install PyPDF2`
- Yalnızca birden fazla belge dosyasını birleştirmek için gereklidir

### 📄 Lisans

Telif Hakkı © 2025 Emil Veliyev. Tüm hakları saklıdır.

Bu proje MIT Lisansı altında lisanslanmıştır - detaylar için [LICENSE](LICENSE) dosyasına bakın.

### 👨‍💻 Yazar

**Emil Veliyev** - [@emillvl](https://github.com/emillvl)

### 🤝 Katkıda Bulunma

Katkılar, sorunlar ve özellik istekleri memnuniyetle karşılanır!

1. Projeyi fork'layın
2. Özellik dalınızı oluşturun (`git checkout -b feature/HarikaOzellik`)
3. Değişikliklerinizi commit edin (`git commit -m 'Harika bir özellik ekle'`)
4. Dalınıza push yapın (`git push origin feature/HarikaOzellik`)
5. Bir Pull Request açın

### ⭐ Desteğinizi Gösterin

Bu proje size yardımcı olduysa bir ⭐ verin!

---

<div align="center">

**Made with ❤️ by Emil Veliyev**

[![GitHub](https://img.shields.io/badge/GitHub-emillvl-181717?style=for-the-badge&logo=github)](https://github.com/emillvl)

</div>
