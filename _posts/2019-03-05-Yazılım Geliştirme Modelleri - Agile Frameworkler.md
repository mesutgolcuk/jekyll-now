---
layout: post
title: Yazılım Geliştirme Modelleri - Agile Framework'ler
---

Bu yazımda Coursera'da bulunan [Software Development Processes and Methodologies](https://www.coursera.org/learn/software-processes) dersinin 4. haftasının Agile Frameworks başlığındaki konulardan tuttuğum notları ve kendi öğrendiklerimi paylaşacağım.

## Agile Framework'ler

Agile'ın bir düşünce yöntemi olduğunu öğrendiğimize göre bir de agile'ı nasıl uygulayabileceğimize bakmalıyız. Düşünce yöntemini uygulayabileceğimiz bir çok framework var ancak her duruma ve herkese uyan tek bir yöntem yok. Bu sebeple bu yöntemleri takımın ve projenin ihtiyaçlarına göre şekillendirmek gerekebiliyor.

Agile şemsiyesi altında en popüler yöntemleri sıralayacak olursak: 
* Scrum
* Kanban
* Scrumban
* XP - Extreme Programming
* Scrum XP Hybrid
* Lean Startup

Framework'lerin uygulamaları ve ritüellerine kendimizi boğarak agile düşüncenin temelinde yatanları unutmamalıyız.

### Scrum

Scrum 1-4 hafta arası sprint adı verilen ürünün bir kısmının ele alındığı sorunun belirlendiği tasarlandığı geliştirildiği ve test edildiği aşamalardan oluşuyor. Bu aşamalar sonunda da ürün paydaşlara gösterilerek ihtiyaca yönelik düzenlemelerle aynı aşamalar tekrarlanıyor.

Scrum'da belirlenmiş 3 rol mevcut. 

1. si neye ihtiyaç olduğunu neyin hangi sırayla yapılacağını belirleyen **product owner**.

Bir diğer rol ise takımın scrum prensiplerine bağlı kalmasını sağlayan ve takımın önündeki engelleri kaldırmaya çalışan **scrum master**.

Son olarak ise kendi kendini yönetebilen yazılım çoğunluğunu üreten **takım**.

Örnek bir çalışma yürütecek olursak öncelikle product owner müşterileri, paydaşları, yöneticileri ve takımı dinleyerek aldığı dönüşlere göre neyin hangi öncelikte olduğunu ve neyin yapılacağını içeren **product backlog** u hazırlar. Product backlog kapsam dökümanından çok farklı bir döküman ve zaman içerisinde değişebilir.

Takım sprint için hazır olduğunda **Sprint Planlama Toplantısında** tüm takım bir araya toplanır. Bu toplantıda çalışabilecekleri özellikleri seçerler. Product owner bu özellikleri takımla birlikte değerlendirir ve açık olmayan noktaları aydınlatmaya çalışır.

Ardından takım tekrar bir araya gelir ve **Sprint Backlog**'u oluşturur. Burada yazılımı geliştirmek için tam olarak ne yapılması gerektiği kararlaştırılır. 

Sprint'i planladıktan ve sprint'te yapılması gerekenleri planladıktan sonra takım bu işleri bu sprint içerisinde bitireceğini ilan eder. Bu aşama 1-4 hafta arası sürer. Ancak her gün takım bir araya gelip **günlük scrum toplantısı** yapar. Bu toplantıda ayakta dün ne yaptığından bugün ne yapacağından ve önünde bir engel olup olmadığından bahseder.

Sprint sonunda bitmiş bir iş ortaya çıkarılır. Sprint'te yapılanları değerlendirmek için tüm takımın paydaşlarla ve müşterilerle bir araya geldiği **Sprint Review** toplantıları yapılır. Bu toplantıda yapılanlar gösterilip yorumlar alınır.

Sprint sonunda yapılan toplantılardan bir diğeri ise **retrospective toplantıları**. Bu toplantılarda ise üründen değil süreçten bahsedilir. Nasıl bir yöntemle daha iyi yapabilirdik gibi sorulara cevap aranır. Neyin iyi gittiği neyin kötü gittiği konuşulur.

Sprint'in nasıl gittiğini takip etmek için takım **burndown/up** grafiklerini kullanır. Bu grafikler sprint'in kalan günlerini ve kalan işleri gösterir.

Scrum'ın agile'ı nasıl desteklediğini inceleyecek olursak da: 
* İteratif olarak geliştirme yapıyoruz. Bu sebeple değişimi destekliyor.
* Müşterilerle takım üyeleri arasında bir çok toplantı ile iş birliğini destekliyor.
* Retrospective ile sürekli iyileşmeyi destekliyor.

## Kanban

Scrum'da 1-4 haftalık iterasyonlar ile ilerleniyor. Ancak Kanban sabit bir iterasyon ya da yeni bir yöntem tariflemiyor. Sadece yazılım geliştirme sürecini devamlı bir akış haline getirmeye çalışan prensipler ve özellikler sunuyor.

Kanban'ın önerdiği ilk şey iş akışını görselleştir. Bunu gerçekleştirmek için de ilk olarak fiziksel ya da elektronik bir alan oluşturulur. Yazılım geliştirme aşamaları sütunlara bölünür. Backlog da bulunan yapılacak işler durumuna göre ilgili sütunlara taşınır. Örneğin backlog, analiz, geliştirme, test, üretime taşıma aşamalarından oluşan bir tahta düşünülebilir. 

Oluşturulan aşamalardan test aşamasında yığılma ve dar boğaz olduğunu düşünelim. Bu yazılımın teslimatını geciktirecektir. Kanban bunu çözmek için belirli bir sütunda bulunabilecek iş sayısını kısıtlamayı öneriyor. Bu sayede bir aşama tıkandığında herkes oraya yardım ederek çözüme kavuşmasını sağlayabilir.

Kanban'ın önerdiği başka bir aşama ise işin bitiş tanımının yapılmasını sağlamak. Bu sayede takımdaki herkes ne zaman bir işi sonraki sütuna taşıyacağından emin olabilir.

## Agile ve Lean Genel Özet

* Agile bir düşünce biçimi. Bir model değil.
* Artırımlı ve iteratif.
* Kısa geliştirme döngüleri.

++ Değişime uyumu çok iyi.

++ Doğru ürünü geliştiriyor olma şnsı daha yüksek.

++ Marketteki değişime uyumu iyi 

-- Üretilen baştan kesin çizgilerle belirli olmadığı için aynı işin birden çok kere yapılması gerekebilir. 

-- Müşterilerden de aynı iş birliği ve yakın ilişkinin sağlanması bekleniyor.

Gereksinimlerin değişebileceği ve takımın bilgisinin az olduğu teknolojileri kullandığı projelerde kullanılması avantajlıdır.

Ek olarak Eric Ries'in 2011 yılında yazdığı bir kitapla tanıttığı lean startup modeli üzerinde duruldu. Lean Startup modeli genel olarak üründen çok markete odaklanan ve onun ihtiyaçlarını anlayıp ona göre ürün çıkarmaya odaklanan bir model. Kitaba [buradan](https://www.goodreads.com/book/show/30668740-yal-n-yeni-giri-im) erişebilirsiniz.

> So Say We All!