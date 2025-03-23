GRU Tabanlı Duygu Analizi Modeli
Bu proje, GRU (Gated Recurrent Unit) tabanlı bir sinir ağı modeli kullanarak metin verileri üzerinde duygu analizi yapmaktadır. Model, verilen metinleri sınıflandırarak hangi duygu kategorisine ait olduğunu belirler.

Proje İçeriği
Veri Seti: Metinlerden ve bunlara ait duygu etiketlerinden oluşan bir veri seti kullanılmıştır.

Veri Önişleme: Metin verileri modelin anlayabileceği formata dönüştürülmek için tokenizasyon, padding ve indeksleme işlemlerinden geçirilmiştir.

Model Yapısı:

Kelimeleri vektörlere dönüştüren göm embedding katmanı

Üç katmanlı GRU ağı ile derin öğrenme modeli

Modelin kararlılığını artırmak için batch normalization

Son aşamada tahmin yapan tam bağlı (dense) katman

Model Eğitimi: Model, belirlenen eğitim verisi üzerinde belirli sayıda epoch boyunca eğitilmiş, doğrulama verisi ile test edilerek performansı değerlendirilmişti



ChatGPT:
GRU-Based Sentiment Analysis Model
This project utilizes a GRU (Gated Recurrent Unit)-based neural network model to perform sentiment analysis on text data. The model classifies given texts into their respective sentiment categories.

Project Content
Dataset: A dataset consisting of text samples and their corresponding sentiment labels has been used.

Data Preprocessing: Text data has been processed into a format understandable by the model through tokenization, padding, and indexing.

Model Structure
An embedding layer that converts words into vectors

A three-layer GRU network for deep learning

Batch normalization to enhance model stability

A fully connected (dense) layer for final predictions

Model Training
The model was trained on a specified dataset for a certain number of epochs and evaluated using validation data to assess its performance.