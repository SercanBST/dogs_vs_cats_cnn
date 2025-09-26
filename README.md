# dogs_vs_cats_cnn
Bu proje Akbank Derin Öğrenmeye Giriş Bootcamp i kapsamında hazırladığım bir projedir.
Kediler ve Köpekler için Konvolüsyonel Sinir Ağı (CNN)
Bu proje, Kaggle'da bulunan "Asirra: cat vs dogs" veri kümesini kullanarak kedi ve köpek görüntülerini sınıflandırmak için sıfırdan oluşturulmuş bir Konvolüsyonel Sinir Ağı (CNN) modelinin geliştirilmesini ve değerlendirilmesini amaçlamaktadır.

**Teknolojiler**
Python

TensorFlow / Keras

Numpy

Matplotlib

scikit-learn

# Veri Kümesi
Bu çalışma için kullanılan veri kümesi, Asirra (Cats vs Dogs) yarışmasından alınmıştır. Veri kümesi, eğitim, doğrulama ve test aşamalarında kullanılmak üzere kedi ve köpek görüntülerini içermektedir.

# Model Mimarisi
Model, görüntü sınıflandırma için tipik bir CNN mimarisine sahiptir ve aşağıdaki katmanları içermektedir:

Evrişim (Convolutional) Katmanları: Görüntülerdeki özellikleri çıkarmak için.

Havuzlama (Pooling) Katmanları: Boyut küçültme ve aşırı uyumu azaltmak için.

Yoğun (Dense) Katmanlar: Sınıflandırma işlemini gerçekleştirmek için.

Dropout ve Batch Normalization: Modelin daha iyi genelleme yapmasını ve eğitimini hızlandırmak için.

# Sonuçlar
Eğitim süreci sonunda modelin performansı aşağıdaki gibidir:

Eğitim Doğruluğu: %98.59

Doğrulama (Validation) Doğruluğu: %88.00

Test Doğruluğu: %70.45

Eğitim ve test doğruluğu arasındaki bu fark, modelin eğitim verilerine aşırı uyum (overfitting) eğilimi gösterdiğine işaret edebilir. Yine de, bu proje bir başlangıç çalışması olarak oldukça başarılıdır ve bir CNN modelinin temel işleyişini göstermektedir.

# Proje Nasıl Çalıştırılır?

1-Projeyi kendi ortamınızda çalıştırmak için aşağıdaki adımları takip edebilirsiniz:

2-Gerekli kütüphaneleri kurun:

pip install tensorflow numpy matplotlib scikit-learn
cnn-rnek-dogs-vs-cats.ipynb dosyasını Jupyter Notebook veya Google Colab üzerinde açın.

3-Dosyadaki tüm hücreleri sırayla çalıştırın.

# kaggle linki
https://www.kaggle.com/code/sercanhoglu/cnn-ornek-dogs-vs-cats/edit 
