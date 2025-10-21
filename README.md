## 🇹🇷 Türkçe Açıklama

Bu Jupyter Notebook, **OpenCV**, **NumPy** ve **Matplotlib** kütüphaneleri kullanılarak hazırlanmış bir **görüntü işleme (image processing)** çalışmasıdır.

### 🔍 Amaç
Bu çalışma, temel görüntü işleme tekniklerini (bulanıklaştırma, kenar tespiti, renk dönüşümü vb.) deneysel olarak göstermek amacıyla oluşturulmuştur.

### 🧩 Kullanılan Kütüphaneler
- **OpenCV (cv2):** Görüntüleri okuma, dönüştürme ve filtreleme işlemleri için.
- **NumPy:** Görüntü pikselleri üzerinde matematiksel işlemler yapmak için.
- **Matplotlib:** İşlenen görüntüleri grafiksel olarak göstermek için.

### ⚙️ Kodun İşleyiş Adımları
1. **Görüntü Yükleme:** `cv2.imread()` ile bir resim dosyası yüklenir.  
2. **Renk Dönüşümü:** `cv2.cvtColor()` ile BGR → RGB veya gri ton (grayscale) dönüşümü yapılır.  
3. **Filtreleme / Dönüşümler:**  
   - `cv2.GaussianBlur()` → Bulanıklaştırma  
   - `cv2.Canny()` → Kenar tespiti  
   - Histogram işlemleri ve diğer dönüşümler  
4. **Sonuçların Görselleştirilmesi:** `matplotlib.pyplot` ile orijinal ve işlenmiş görüntüler yan yana gösterilir.

### 📸 Sonuç
Bu notebook, temel düzeyde **görüntü iyileştirme, kenar bulma ve renk filtreleme** uygulamalarını içeren öğretici bir örnektir.


---

## 🇬🇧 English Description

This Jupyter Notebook is an **image processing project** built using **OpenCV**, **NumPy**, and **Matplotlib** libraries.

### 🔍 Purpose
The project demonstrates basic image processing techniques such as blurring, edge detection, and color conversion.

### 🧩 Libraries Used
- **OpenCV (cv2):** For reading, transforming, and filtering images.  
- **NumPy:** For numerical operations on image pixels.  
- **Matplotlib:** For visualizing processed images and results.

### ⚙️ Code Workflow
1. **Image Loading:** Using `cv2.imread()` to import an image file.  
2. **Color Conversion:** With `cv2.cvtColor()` to convert BGR → RGB or grayscale.  
3. **Filtering / Transformations:**  
   - `cv2.GaussianBlur()` → Blurring  
   - `cv2.Canny()` → Edge detection  
   - Histogram analysis and other transformations  
4. **Visualization:** Using `matplotlib.pyplot` to display original and processed images side by side.
