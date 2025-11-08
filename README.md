##README

BST_Hafta_7_Kod_1.ipynb
# 🧾 Yüz Tespiti – OpenCV ile Haar Cascade Kullanımı

*(Face Detection using OpenCV Haar Cascade)*

---

## 🇹🇷 **Türkçe Açıklama**

Bu proje, **OpenCV** kütüphanesi kullanılarak bir görüntü üzerinde **insan yüzü tespiti** yapılmasını göstermektedir.
Kod, OpenCV’nin önceden eğitilmiş **Haar Cascade** modelini kullanarak yüzleri algılar ve dikdörtgenlerle işaretler.

---

### 🚀 İçerik

* `cv2.CascadeClassifier` ile Haar Cascade modeli yükleme
* Gri seviye (grayscale) görüntü ile yüz tespiti
* `detectMultiScale()` fonksiyonunun temel parametreleri:

  * `scaleFactor`: Görüntü yakınlaştırma oranı
  * `minNeighbors`: Yanlış pozitifleri azaltmak için komşu sayısı
  * `minSize`: Tespit edilecek minimum yüz boyutu
* `cv2.rectangle()` ile yüzlerin etrafına dikdörtgen çizimi
* `cv2.imshow()` ile sonuç görüntüsünün ekrana getirilmesi

---

### 🧠 Kullanılan Teknolojiler

* Python
* OpenCV (`cv2`)
* NumPy

---

### 📂 Çalıştırma

```bash
pip install opencv-python numpy
jupyter notebook BST_Hafta_7_Kod_2.ipynb
```

veya `.ipynb` dosyasını doğrudan Jupyter Notebook ortamında açarak hücreleri çalıştırabilirsiniz.

---

### 🖼️ Örnek Çıktı

Kod, `deneme.jpg` adlı bir görseldeki yüzleri **yeşil dikdörtgenler** ile vurgular.

---

### 🎯 Öğrenme Kazanımları

Bu çalışmayla birlikte:

* Görüntü işleme temellerini,
* Haar Cascade sınıflandırıcılarının çalışma prensibini,
* OpenCV ile yüz tespit algoritmalarının nasıl uygulandığını öğrenebilirsiniz.

---

## 🇬🇧 **English Explanation**

This project demonstrates **human face detection** using the **OpenCV** library.
It utilizes OpenCV’s pre-trained **Haar Cascade** classifier to identify and highlight faces in an image.

---

### 🚀 Contents

* Loading the Haar Cascade model using `cv2.CascadeClassifier`
* Performing face detection on grayscale images
* Understanding `detectMultiScale()` parameters:

  * `scaleFactor`: Image scaling step
  * `minNeighbors`: Number of neighbors to reduce false positives
  * `minSize`: Minimum detected face size
* Drawing bounding boxes with `cv2.rectangle()`
* Displaying results with `cv2.imshow()`

---

### 🧠 Technologies Used

* Python
* OpenCV (`cv2`)
* NumPy

---

### 📂 Running the Project

```bash
pip install opencv-python numpy
jupyter notebook BST_Hafta_7_Kod_2.ipynb
```

or open the notebook in **Jupyter** and run each cell step by step.

---

### 🖼️ Example Output

The code highlights faces in `deneme.jpg` with **green rectangles**.

---

### 🎯 Learning Outcomes

With this example, you’ll learn:

* The fundamentals of digital image processing
* How Haar Cascade classifiers work
* How to implement basic face detection using OpenCV


-----------------------------------------------------------------------------------------------
BST_Hafta_7_Kod_2.ipynb
# 🧾 Yüz Tespiti – OpenCV ile Haar Cascade Kullanımı  
*(Face Detection using OpenCV Haar Cascade)*

---

## 🇹🇷 **Türkçe Açıklama**

Bu proje, **OpenCV** kütüphanesi kullanılarak bir görüntü üzerinde **insan yüzü tespiti** yapılmasını göstermektedir.  
Kod, OpenCV’nin önceden eğitilmiş **Haar Cascade** modelini kullanarak yüzleri algılar ve dikdörtgenlerle işaretler.

---

### 🚀 İçerik  

- `cv2.CascadeClassifier` ile Haar Cascade modelini yükleme  
- Gri seviye (grayscale) görüntü üzerinde yüz tespiti  
- `detectMultiScale()` fonksiyonunun parametreleri:  
  - `scaleFactor`: Görüntü yakınlaştırma oranı  
  - `minNeighbors`: Yanlış pozitifleri azaltmak için komşu sayısı  
  - `minSize`: Tespit edilecek minimum yüz boyutu  
- `cv2.rectangle()` ile tespit edilen yüzlerin etrafına dikdörtgen çizimi  
- `cv2.imshow()` ile sonuçların ekranda gösterilmesi  

---

### 🧠 Kullanılan Teknolojiler  

- Python  
- OpenCV (`cv2`)  
- NumPy  

---

### 📂 Çalıştırma  

```bash
pip install opencv-python numpy
jupyter notebook BST_Hafta_7_Kod_2.ipynb
````

veya `.ipynb` dosyasını doğrudan **Jupyter Notebook** ortamında açarak hücreleri sırasıyla çalıştırabilirsiniz.

---

### 🖼️ Örnek Çıktı

Kod, `deneme.jpg` adlı bir görseldeki yüzleri **yeşil dikdörtgenlerle** vurgular.

---

### 🎯 Öğrenme Kazanımları

Bu çalışmayla birlikte:

* Görüntü işleme temellerini,
* Haar Cascade sınıflandırıcılarının çalışma prensibini,
* OpenCV ile yüz tespit algoritmalarının nasıl uygulandığını öğrenebilirsiniz.

---

## 🇬🇧 **English Explanation**

This project demonstrates **human face detection** using the **OpenCV** library.
It utilizes OpenCV’s pre-trained **Haar Cascade** classifier to identify and highlight faces in an image.

---

### 🚀 Contents

* Loading the Haar Cascade model with `cv2.CascadeClassifier`
* Performing face detection on grayscale images
* Understanding `detectMultiScale()` parameters:

  * `scaleFactor`: Image scaling step
  * `minNeighbors`: Number of neighbors to reduce false positives
  * `minSize`: Minimum detected face size
* Drawing rectangles with `cv2.rectangle()`
* Displaying results using `cv2.imshow()`

---

### 🧠 Technologies Used

* Python
* OpenCV (`cv2`)
* NumPy

---

### 📂 Running the Project

```bash
pip install opencv-python numpy
jupyter notebook BST_Hafta_7_Kod_2.ipynb
```

or open the notebook in **Jupyter** and run each cell step by step.

---

### 🖼️ Example Output

The code highlights faces in `deneme.jpg` using **green rectangles**.

---

### 🎯 Learning Outcomes

Through this example, you’ll learn:

* The fundamentals of digital image processing
* How Haar Cascade classifiers work
* How to implement face detection with OpenCV

_________________________________________________________________________________________________________________________________
BST_Hafta_7_Kod_3.ipynb

# ✂️ Siyah Kenarları Otomatik Kırpma – OpenCV ile Görüntü Ön İşleme  
*(Automatic Black Border Cropping using OpenCV)*

---

## 🇹🇷 **Türkçe Açıklama**

Bu proje, **OpenCV** kullanarak siyah arka planlı görüntülerdeki nesneleri otomatik olarak tespit eder ve  
**siyah kenarları kırparak** yalnızca ilgilenilen nesneyi elde etmeyi gösterir.  

Kod, kontur bulma (`cv2.findContours`) ve eşikleme (`thresholding`) yöntemlerini kullanarak  
arka plan ile nesneyi ayırır, ardından `cv2.boundingRect()` ile nesnenin sınırlarını belirler  
ve görüntüyü kırpar.

---

### 🚀 İçerik  

- Görüntü okuma (`cv2.imread`)  
- Gri seviye dönüştürme (`cv2.cvtColor`)  
- Morfolojik işlemler (`cv2.morphologyEx`)  
- Kontur bulma (`cv2.findContours`)  
- Dikdörtgen sınırlama (`cv2.boundingRect`)  
- Otomatik kırpma fonksiyonu (`cropped_black_borders`)  

---

### 🧠 Kullanılan Teknolojiler  

- Python  
- OpenCV (`cv2`)  
- NumPy  

---

### ⚙️ Fonksiyon Özellikleri  

```python
cropped_black_borders(img, thr=12, pad=0)
````

* **img:** Girdi görüntüsü (renkli veya gri seviye)
* **thr:** Eşik değeri (arka planın ne kadar “siyah” olduğunu belirler)
* **pad:** Kırpma sonrası kenarlarda bırakılacak boşluk miktarı (piksel cinsinden)

---

### 📂 Çalıştırma

```bash
pip install opencv-python numpy
jupyter notebook BST_Hafta_7_Kod_3.ipynb
```

veya `.ipynb` dosyasını **Jupyter Notebook** ortamında açarak hücreleri sırayla çalıştırabilirsiniz.

---

### 🖼️ Örnek Çıktı

Kod, `yeni1.png` adlı bir görseldeki siyah kenarları kaldırarak yalnızca nesneyi gösterir.

---

### 🎯 Öğrenme Kazanımları

Bu çalışma ile:

* Görüntü ön işleme aşamalarını,
* Kontur tabanlı nesne tespit yöntemlerini,
* Görüntü kırpma (cropping) tekniklerini,
* Morfolojik işlemlerle gürültü temizlemeyi öğrenebilirsiniz.

---

## 🇬🇧 **English Explanation**

This project demonstrates how to **automatically crop black borders** around objects in an image using **OpenCV**.
It detects non-black areas by applying **thresholding** and **contour detection**,
then uses `cv2.boundingRect()` to crop the region of interest.

---

### 🚀 Contents

* Image reading (`cv2.imread`)
* Grayscale conversion (`cv2.cvtColor`)
* Morphological operations (`cv2.morphologyEx`)
* Contour detection (`cv2.findContours`)
* Bounding box generation (`cv2.boundingRect`)
* Automatic cropping function (`cropped_black_borders`)

---

### ⚙️ Function Definition

```python
cropped_black_borders(img, thr=12, pad=0)
```

* **img:** Input image (color or grayscale)
* **thr:** Threshold value to separate black background
* **pad:** Padding pixels to keep around the cropped object

---

### 🧠 Technologies Used

* Python
* OpenCV (`cv2`)
* NumPy

---

### 📂 How to Run

```bash
pip install opencv-python numpy
jupyter notebook BST_Hafta_7_Kod_3.ipynb
```

or open the notebook in **Jupyter Notebook** and execute the cells step by step.

---

### 🖼️ Example Output

The script removes black borders from `yeni1.png` and displays only the main object.

---

### 🎯 Learning Outcomes

Through this project, you’ll learn:

* Image preprocessing fundamentals
* Contour-based object extraction
* Cropping and bounding box logic
* Morphological operations for noise reduction




