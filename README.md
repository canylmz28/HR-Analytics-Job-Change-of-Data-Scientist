# HR-Analytics-Job-Change-of-Data-Scientist

# Problem Tanımı

* Büyük Veri ve Veri Bilimi alanında faaliyet gösteren bir şirket, şirket tarafından yürütülen bazı kursları başarıyla geçen kişiler arasından veri bilimcilerini işe almak istiyor. Birçok kişi eğitimlerine kaydolur. Şirket, bu adaylardan hangisinin eğitimden sonra veya yeni bir iş aradıktan sonra gerçekten şirkette çalışmak istediğini bilmek istiyor. Çünkü bu, eğitimin kalitesinin yanı sıra eğitim kalitesinin veya kursların planlanması ve adayların sınıflandırılmasına yardımcı oluyor. Demografi, eğitim, deneyim ile ilgili bilgiler adayların kayıt ve kayıt işlemlerinden elde edilir.
* Mevcut kimlik bilgilerini, demografik bilgileri, deneyim verilerini kullanan bir model ile bir adayın yeni bir iş arama veya şirket için çalışma olasılığını tahmin etmemiz isteniyor. 

# Veri Seti Tanımı

* enrollee_id : Aday için benzersiz kimlik
* city: Şehir kodu
* city_ development _index : Şehrin gelişme endeksi
* gender: Cinsiyet
* relevent_experience: Deneyim
* enrolled_university: Varsa kayıtlı olan üniversite dersinin türü
* education_level: Eğitim düzeyi
* major_discipline: Adayın eğitim ana disiplini
* experience: Tecrübe
* company_size: İşverenin şirketinde çalışan işçi sayısı
* company_type : Şirket türü
* lastnewjob: Önceki iş ile mevcut iş arasındaki yıl farkı
* training_hours: Tamamlanan eğitim saati
* target: Hedef değişkenimiz: 0(İş değişikliği aramamak), 1(İş değişikliği aramak)

# Proje Adımları

* 1) Load and Check Data
* 2) Variable Analysis
* 3) Missing Value
* 4) Data Preprocessing
* 5) ML Model ( XGBClassifier)
