# Rot and freshness classification of fruits

A dataset of images of apples, oranges and bananas, both rotten and fresh, was used in the study. A convolutional neural network (CNN) model, a deep feed-forward artificial neural network, was developed to analyze the images. The model utilizes Keras and Tensorflow infrastructure. 

We used a sequential model with a simple model architecture consisting of two Conv2D convolutional layers and three dense layers. The activation function used for the convolutional layers is ReLU. Each convolutional layer has an associated pooling layer of type MaxPooling2D. The pooling layers are meant to reduce training time, reduce overfitting and reduce the dimensionality of the model. There is a flatten layer between the convolutional and dense layers. The activation function of two of the dense layers is ReLu while the last one is Softmax.

********

Çalışmada, çürük ve taze olmak üzere Elma, portakal ve muz görüntülerinin bulunduğu bir veri seti kullanıldı. Görüntülerin analiz edilmesi için bir derin ileri beslemeli yapay sinir ağı olan evrişimli sinir ağı (CNN) modeli geliştirilmiştir. Geliştirilen model Keras ve Tensorflow altyapısını kullanmaktadır. 

İki Conv2D konvolüsyonel katmanından ve üç dense katmanından oluşan basit bir model mimarisine sahip ardışık bir model kullanıldı. Konvolüsyonel katmanlar için kullanılan aktivasyon fonksiyonu ReLU'dur. Her bir evrişimsel katman, MaxPooling2D tipinde ilişkili bir havuzlama katmanına sahiptir. Havuzlama katmanları, eğitim süresini kısaltmak, aşırı uyumu azaltmak ve modelin boyutluluğunu azaltmak içindir. Konvolüsyonel ve dense katmanları arasında bir flatten katmanı mevcuttur. Dense katmanlarının iksinin aktivasyon fonksiyonu ReLu iken sonuncusunun Softmax seçilmiştir. 


Dataset : https://www.kaggle.com/datasets/sriramr/fruits-fresh-and-rotten-for-classification
