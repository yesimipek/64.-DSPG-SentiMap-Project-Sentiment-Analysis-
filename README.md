# 64.-DSPG-SentiMap-Project-Sentiment-Analysis-
Keras Model with Bert Features for predicting sentiment of citizens in each İstanbul Counties.

TR // Proje ismi: Sentimap

Proje takımı:

Yeşim İpek: İstanbul Teknik Üniversitesi  - İşletme Mühendisliği

Didar Tutan: Koç Üniversitesi Felsefe ve Uluslararası İlişkiler (Lisans), Karşılaştırmalı Tarih ve Toplum Çalışmaları (Yüksek Lisans)

Ege Zeytun: Boğaziçi Üniversitesi Siyaset Bilimi ve Uluslararası İlişkiler (Lisans), George Washington  Üniversitesi Siyaset Bilimi (Yüksek Lisans)

Büşra Öner: İstanbul Üniversitesi - İngilizce İşletme, Marmara Üniversitesi - Üretim Yönetimi ve Pazarlama (Yüksek Lisans)
 
Amaç: Verilerin duygu analizi modelleri ile işlenerek, İstanbulluların ilçelere göre belediye hizmetlerine yönelik tutumlarının ölçülmesi amaçlanmıştır. Vatandaşların mesajlardaki değişen duygularına göre, belediyenin o ilçedeki hizmet kaynaklarını bir an önce genişletmesi ve daha iyi sosyal politikalar oluşturması hedeflendi.

Proje süreci ve sonuç:
Proje sürecinde veri incelemesi ve temizlenmesi yapılır. Metindeki yazım hataları düzeltilen ve özel isimlerden arındırılan veri modele hazır edilir. Duygu analizi modelinin veri ile eğitimleri tamamlandıktan sonra Çağrı Merkezi başvurularının duygusu negatif, pozitif, nötr olacak şekilde tahmin edilir. Çıktılar ilçe bazlı duygu skorlarının haritalaştırılması sonucu SentiMap’i oluşturur.

EN//
Project name: Sentimap

Team: 

Yeşim İpek: Istanbul Technical University  - Management Engineering

Didar Tutan: Koç University Philosophy and International Relations, Comparative History and Society Studies (Master)

Ege Zeytun: Boğaziçi University  Political Science and International Relations (Bachelor), George Washington University Political Science (Master)

Büşra Öner: İstanbul University - Business Administration, Marmara University - Production Management and Marketing (Master)

Goal: It was aimed to measure the attitudes of Istanbul residents district by district towards municipal services by processing the data with sentiment analysis models. According to the changing feelings of the citizens in the messages, it was aimed that the municipality could immediately expand its service resources in that district and create better social policies.

About the project and results: 
During the project process, data analysis and cleaning is done. Corrected typos in the text and stripped of proper names, the data is ready for the model. After the training of sentiment analysis model with data is completed, the emotion of the Call Center applications is estimated to be negative, positive, and neutral. Outputs create SentiMap as a result of mapping district-based emotion scores.

Model Accuracy : %79 avg recall ( Successful compared to Multimonial Naive Bayes Base Model Accuracy (%68) )
