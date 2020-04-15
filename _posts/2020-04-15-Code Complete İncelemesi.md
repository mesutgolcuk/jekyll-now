---
layout: post
title: Code Complete İncelemesi
---

4-5 aylık bir süreç sonunda [Code Complete](https://www.goodreads.com/book/show/4845.Code_Complete)'i bitirme fırsatına eriştim. Sektörün klasiklerinden yazılımcıların okumayı önerdiği kitaplar listelerinin değişmez kitaplardan birisi. Stackoverflow'daki [şu konuda](https://stackoverflow.com/questions/1711/what-is-the-single-most-influential-book-every-programmer-should-read) da liste başı. Öğrenciyken okumuş olmayı ve bazı alışkanlıkları belki de daha önceden kazanabilmiş olmayı dilerdim. Ancak farklı zamanlarda okudukça farklı dersler çıkarılabilecek bir kitap olduğunu düşünüyorum.

Code Complete ilk olarak 93 yılında yayınlanmış ancak benim de okumuş olduğum sürüm 2004 yılında yayınlanmış. Kendisi 914 sayfalık uzunluğuyla çok fazla konuya değiniyor. Kitabın konları güzel gruplanmış ve bölümler genel olarak birbirinden bağımsız hazırlandığı için okuması kolay olmuş. Daha sonra kendimi konuyla ilgili doğru yolda tutmak istersem ilgili bölümü açıp okumak bir sıkıntı yaratmayacaktır.

2004 yılında belki bazı standartlar henüz oturmadığından belki de hedef kitlenin mühendislik/cs derecesi almadığını düşünerek yazıldığından temel bir çok konuya da değiniliyor. Bu sebeple gözümle tarama yapıp ilgi çekici nokta arayarak atladığım bölümler de oldu. Goodreads üzerinde puanımı 5 üzerinden 4 yıldız olarak belirledim. Öncesinde okumuş olduğum ve 5 yıldız vermiş olduğum Pragmatic Programmer, Clean Code ve Coder kitaplarından biraz daha dağınık ve zayıf buldum bu sebeple.

Kitap toplamda 7 ana bölüm ve 35 alt bölümden oluşuyor. Genel olarak da yazılıma dair bir çok şey hakkında görüşünü bildiriyor. Yazılım üretiminin sürecinden başlayıp kaliteli kod ortaya koymanın yolları, yazılımdaki değişkenlerle ilişkimiz, kaliteyi sağlama metrikleri, performans iyileştirmenin nasıl yapılabileceği, testler, debug, refactor, yazılım yönetimi, yazılımcıların sahip olması gereken soft skillere kadar her konuya değiniyor. Girdiği konuların özetini ve önemli noktaları 34. bölümde de özetlemeye çalışıyor. 34. Bölüm kitaba dair önemli noktalar ve özet olarak düşünülebilir.

Bölüm 34'ün içerdiği ana başlıklar kitabın da vermek istediği mesajları oluşturuyor:
1. Conquer Complexity
2. Pick Your Process
3. Write Programs for People First, Computers Second
4. Program into Your Language, Not in it
5. Focus Your Attention with the Help of Conventions
6. Program in Terms of the Problem Domain
7. Watch for Falling Rocks
8. Iterate, Repeatedly, Again and Again
9. Thou Shalt Render Software and Religion Asunder

Ben de kendi notlarımı paylaşacak olursam: 

- Kodlamaya başlamadan önce de yeterince zaman harcayıp gökdelen inşa eder gibi detayları planlamalıyız. Gene kullanılan benzetmelerden birisi marangozların 2 kez ölç 1 kez kes prensibi. Bu prensiple tasarıma önem vermeliyiz. İyi değişken isimleri ve güzel bir üst seviye tasarımla kompleksliği azaltmalıyız.

- Standartların, disipliner yaklaşımların ve abstraction'ların önemi. Tek başına çalışma ve takım halinde çalışmada bunların ne kadar etki yapabildiği. Standartları belirleyerek düşünmek yükümüzü hafifletebilir ve özelliklere daha çok odaklanabiliriz.

-  Bir kodu yazarken harcadığımız zamandan çok sonrasında o kodu okumak için zaman harcanıyor. Bu sebeple yazdığımız kodu olabildiğince yalın, anlaşılır ve kolay okunabilir halde yazmalıyız.

- Nasıl sorusundan önce neden ve niçin sorusunu sormalıyız. Teknik çalışanlar olarak görevimizin bir parçası da teknik olmayan insanları geliştirme süreçleri hakkında eğitmek.

- Compiler uyarıları, alınmaya başlanan hatalar gibi konulara dikkat etmeliyiz. Aldığımız uyarı ve hataların altında yatan sebepleri iyi anlamaya çalışmalı ve dikkatimizi üzerlerinde tutmalıyız.

- Zayıf noktalarımızda birisi yazılımın büyüme sürecini bilinçsizce gerçekleştirmemiz. Böyle bir süreci kabullenerek kendi avantajımıza çevirebilir ve her dokunuşumuzda kodu iyileştirip gelecekte daha kolay değiştirilebilir hale getirmeliyiz. (Refactor, refactor, refactor)

- Bazen yazdığımız kodu kendi malımızmış gibi algılayabiliyoruz. Ancak kod sorumlu herkese ait ve açık olmalı. Her satır iyice incelenmeli. Yapılan bazı araştırmalarda kod okuması yaparak saatte 3.3 sorun bulunabilirken test yaparak 1.8 sorun bulunabiliyor.

- Tool'lar programcının en iyi arkadaşı. En iyi arkadaşımızı bulana kadar yıllarca onsuz çalışabiliriz. Yeni denemelere açık olmalı, alışkanlıklarımızı ara ara gözden geçirmeliyiz.

- Yorum yazmak hakkında bir çok tartışma var. Genel olarak kodun kendini dökümente eder olması gerekiyor. Bazı noktalarda özet yorumlar yazılabilir. Kötü kodu yorum yazarak açıklamaya çalışma. Tekrar yaz.

- Alçakgönüllülük, iyi iletişim, merak ve hatalı olduğunu kabul etmek sektörde sahip oluması gereken en önemli özelliklerden.

- Ortalama bir proje %100 ihtimalle planlanandan takvimine göre daha geç bitecektir. Önemli noktalardan birisi de geri kalınca yapılması gerekenler. Projenin kapsamını azaltmak genellikle atlanan en önemli tekniklerden birisi.

- Yazılımcılar ve yöneticiler insanlar. En iyi işi de kendilerine öyle davranıldığında ortaya koyarlar.

Kitaptan hoşuma giden bazı kısımlar ve özlü sözler:

> Requirements are like water. They're easier to build on when they're frozen.

> Evidence of the effect of programming languages on programmers' thinking is common. A typical story goes like this: "We were writing a new system in C++, but most of our programmers didn't have much experience in C++. They came from Fortran backgrounds. They wrote code that compiled in C++, but they were really writing disguised Fortran. They stretched C++ to emulate Fortran's bad features (such as gotos and global data) and ignored C++'s rich set of object-oriented capabilities." This phenomenon has been reported throughout the industry for many years (Hanson 1984, Yourdon 1986a).

> When I am working on a problem I never think about beauty. I think only how to solve the problem. But when I have finished, if the solution is not beautiful, I know it is wrong. — R. Buckminster Fuller

> The primary goal of design should be to minimize complexity for all the reasons just described. Avoid making "clever" designs. Clever designs are usually hard to understand. Instead make "simple" and "easy-to-understand" designs. If your design doesn't let you safely ignore most other parts of the program when you're immersed in one specific part, the design isn't doing its job.

> Continually imagine the questions a maintenance programmer would ask about the code you're writing. Think of the maintenance programmer as your audience, and then design the system to be self-explanatory.

> Get into the habit of asking "What should I hide?" You'll be surprised at how many difficult design issues dissolve before your eyes.

>  In describing the history of searching algorithms, for example, Donald Knuth pointed out that even though the first description of a binary search algorithm was published in 1946, it took another 16 years for someone to publish an algorithm that correctly searched lists of all sizes (Knuth 1998). A binary search is more elegant, but a brute-force, sequential search is often sufficient.
When in doubt, use brute force.— Butler Lampson

> Good design is iterative; the more design possibilities you try, the better your final design will be.

> You can't give a variable a name the way you give a dog a name—because it's cute or it has a good sound.

> Programs do not acquire bugs as people acquire germs, by hanging around other buggy programs. Programmers must insert them. — Harlan Mills

> Do not partially write a feature with the intent of refactoring to get it complete later. — John Manzo

>  Jackson's Rules of Optimization: Rule 1. Don't do it. Rule 2 (for experts only). Don't do it yet—that is, not until you have a perfectly clear and unoptimized solution. — M. A. Jackson

> If you're a software engineer, your basic building material is human intellect and your primary tool is you. Rather than designing a structure to the last detail and then handing the blueprints to someone else for construction, you know that once you've designed a piece of software to the last detail, it's done. The whole job of programming is building air castles—it's one of the most purely mental activities you can do.

> Your employer can't force you to be a good programmer; a lot of times your employer isn't even in a position to judge whether you're good. If you want to be great, you're responsible for making yourself great. It's a matter of your personal character.

> You can't do anything about your intelligence, so the classical wisdom goes, but you can do something about your character. And it turns out that character is the more decisive factor in the makeup of a superior programmer.

> The more you learn to compensate for your small brain, the better a programmer you'll be. The more humble you are, the faster you'll improve.

> [So Say We All!](https://www.youtube.com/watch?v=B3EzRAgjo_s)