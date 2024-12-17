
## 🎉 **Hayvan Türleri Sınıflandırma Projesi** 🐾

Merhaba! Biz **Aslı Şemşimoğlu** ve **Rabia Durgut**. Bu projede, derin öğrenme ve **Transfer Learning** tekniklerini kullanarak **hayvan türlerini sınıflandırmak** için güçlü bir model geliştirdik. 🚀

----------

### 📌 **Proje Hakkında**

Bu proje kapsamında, **10 farklı hayvan türünü** sınıflandırmak için **VGG16** tabanlı bir **Transfer Learning** modeli kullanılmış ve ince ayar (**Fine-Tuning**) uygulanmıştır.

**Hayvan Türleri**:

-   Collie 🐶
-   Dolphin 🐬
-   Elephant 🐘
-   Fox 🦊
-   Moose 🦌
-   Rabbit 🐇
-   Sheep 🐑
-   Squirrel 🐿️
-   Giant Panda 🐼
-   Polar Bear 🐻‍❄️

----------

### 🌟 **Proje Adımları**

1.  **Veri Setinin Hazırlanması** 🗂️
    
    -   10 farklı sınıf seçilerek her sınıftan **650 görüntü** kullanıldı.
    -   Görseller **128x128** boyutuna yeniden boyutlandırıldı ve normalize edildi.
    -   Veri seti, **%70 eğitim - %30 test** olarak ayrıldı.
2.  **Veri Görselleştirme** 🖼️
    
    -   Veri setinden örnek görseller gösterildi.
    -   **Veri artırma (Augmentation)** sonrası görüntüler incelendi.
3.  **Modelin Oluşturulması** 🧠
    
    -   **VGG16** modeli kullanılarak **Transfer Learning** uygulandı.
    -   Modelin son katmanlarına **Dense**, **Dropout** ve **Softmax** katmanları eklendi.
    -   **Sınıf ağırlıkları (Class Weights)** hesaplanarak dengesiz sınıf problemleri giderildi.
4.  **Modelin Eğitilmesi ve Fine-Tuning** 🎯
    
    -   İlk olarak temel katmanlar dondurularak **Transfer Learning** eğitimi gerçekleştirildi.
    -   Ardından, son katmanlar açılarak **Fine-Tuning** işlemi uygulandı.
    -   Eğitim, **Early Stopping** ve **Learning Rate Scheduler** kullanılarak optimize edildi.
5.  **Modelin Değerlendirilmesi** 📊
    
    -   Model, test veri setinde **%95+ doğruluk oranı** elde etti.
    -   Eğitim ve doğrulama süreçleri grafikleriyle analiz edildi.
6.  **Modelin Kaydedilmesi** 💾
    
    -   Nihai model **`final_vgg16_model.h5`** formatında kaydedildi.

----------

### 🚀 **Proje Teknolojileri**

-   **Python** 🐍
-   **TensorFlow / Keras** 🧠
-   **NumPy, Pandas** 📊
-   **Matplotlib** 📈
-   **OpenCV** 🖼️

----------

### 📈 **Sonuçlar**

Bu proje kapsamında, Transfer Learning ve Fine-Tuning kullanarak **hayvan türlerini sınıflandırma** problemini başarıyla çözdük. Modelimiz, test setinde **%95+ doğruluk oranı** ile etkili sonuçlar vermiştir.

----------


### 🔗 **Bizi Takip Edin!**

Projelerimizi ve çalışmalarımızı takip etmek veya bizimle iletişime geçmek isterseniz aşağıdaki bağlantılardan ulaşabilirsiniz:

### **Aslı Şemşimoğlu** ✨

-   💻 **[Kaggle](https://www.kaggle.com/aslemimolu)**
-   💼 **[LinkedIn](https://linkedin.com/in/aslisemsimoglu)**
-   📊 **[GitHub](https://github.com/aslisemsimoglu)**

### **Rabia Durgut** ✨

-   💻 **[Kaggle](https://www.kaggle.com/rabiadurgut)**
-   💼 **[LinkedIn](https://www.linkedin.com/in/rabiadurgut/)**
-   📊 **[GitHub](https://github.com/rabiadurgt)**

----------

### 💬 **Geri Bildirimleriniz Önemli!**

Bu proje ile ilgili görüşlerinizi, sorularınızı veya önerilerinizi paylaşmaktan mutluluk duyarız. 📩

**Teşekkür ederiz ve bir sonraki projelerde görüşmek üzere!** 👋✨

🚀 **İyi çalışmalar dileriz!** 💻
