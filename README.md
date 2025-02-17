# IT Proje Yöneticiliği Kursu / meister-pm

Ön uyarı: Bu eğitimin dili Türkçe olmasına rağmen İngilizce terimler içerir. Tahmin edileceği gibi İngilizce, IT sektörünün ana dilidir. Bu yüzden bu sektörü tercih edecek kişilerin minimum B2 seviyesinde İngilizce bilmeleri oldukça kritiktir.

- Eğitim daha çok teknik konular ağırlıklı olmakla birlikte, proje yönetim biçimlerini de içeriyor. %30 - %70 gibi düşünülebilir. Bunun sebebi ise bu alanı tercih eden/edecek kişilerin en büyük yetersizliklerinin daha çok teknik anlamda olduğunu görmem.

- Burada en doğal olan şey ise sektörün henüz başındayken; hangi konulardan sorumlu olduğunuzu bilmemek, ‘nelere? ne kadar?’ hakim olacağınızı görememek. Yani bir kılavuzunuzun olmaması.
  
- Bir suya düştünüz ama burası;
	- Göl mü? Deniz mi? Okyanus mu? Her ne ise ben onun neresindeyim? Karaya çok mu yakınım? Yoksa tam ortasında, her yere uzakta mıyım? (Bunlar, benim de en başında kendime sorduğum sorulardı).

# Bu kurs neden önemli?

Öncelikle kursun verdiği şey sıralı bir liste. Bu sektördeki başarı olabilmek, kişinin kendi keşfettiği yöntemlerle karaya çıkmasına uygun değil. Uzun yıllar boyunca elde ettiğim tecrübeleri bir müfredat haline getirip, deyim yerindeyse karaya varmak isteyenlere ışık tutmasıdır.

Aşağıda göreceğiniz tüm başlıklar ve içerdikleri, yıllar içinde karaya varan bir gezginin öğrendikleri.

Eğitim içeriklerini oluştururken ben de ‘Vay be’ dedim. Umarım yeni/eski herkese faydalı olur.

# Buna neden kurs diyorum?
Aklımda video serisi çekme düşüncesi oluğundan böyle adlandırıyorum. Umarım yapabilirim.

---------------------------------

# Hepsini bilmek zorunda mısınız?
Ne kadar bilirsen, o kadar iyisin.

Konular:
- Agile methodlari(
    - tarihcesi, neden ortaya cikti
    - sprint nasıl yapılır, backlog, epic vs. Scrum agirlikli
    - Diger metodolojileri tanımsal olarak anlatma
    - Jira uzerinde ornek proje
- Yazilim projeleri uzerine:
    - Projeler
        - Hangi diller
        - Toollar
    - Kavramlar
        - CRM-SAP-CMS-SSO-DWH
        - Devops(detayli teorik)
            - Devops tools? 
        - CI/CD pipeline, build almak vs.
        - Monitoring
        - Load Balancing
        - Domain Kayitlari(DNS, A, TXT, MX, IP, HOST)
        - Email(SMTP)
        - IP adresleri, subnet, private IP vs.
        - WAF
        - VPN
        - SSL
        - Cloud(Azure, AWS, GCP)
        - SAAS, IAAS, PAAS
        - CDN
        - Webserver(IIS, Nginx, Apache2)
            - Dizin/dosya guvenligi(.rar, .zip, .txt)
        - GIT
        - Pozisyonlar ve gorevleri
        - Pentest
        - Loadtest(Stresstest)
        - Databaseler
        - Isletim sistemleri Windows-Linux
        - Testing - Unit, UAT, Autmated
    - Ileri duzey kavramlar
        - Message queue
        - Redis, Rabbitmq
        - Kubernetes
        - MVC nedir?
        - Docker
        - Microservices
        - VM nedir?


* Bu repository, IT Proje Yöneticiliğine sıfırdan başlayacak ve ilerlemiş olanlara da yardımcı olmak amacıyla oluşturulmuştur.

* Yasin Yiğit'e katkıları ve yardımları için ayrıca teşekkür ederim.




Harika bir eğitim planı! İşte konuların altında, anlaşılabilir örneklerle açıklamalar:

**Agile Metotları**

*   **Tarihçesi ve Neden Ortaya Çıktı:**
    *   **Tarihçe:** Geleneksel yazılım geliştirme yöntemleri (Şelale modeli gibi) uzun süreçler, katı planlar ve değişime dirençli yapısıyla projelerin başarısız olmasına neden olabiliyordu. 2001'de bir grup yazılımcı bir araya gelerek daha esnek, işbirliğine dayalı ve müşteri odaklı bir yaklaşım olan Agile Manifestosu'nu yayınladı. Bu manifesto, Agile'ın temel prensiplerini belirledi.
    *   **Neden Ortaya Çıktı:** Müşteri ihtiyaçlarının sürekli değişmesi, rekabetin artması ve yazılım geliştirme süreçlerinin hızlanması gerekliliği Agile'ın ortaya çıkış nedenlerindendir. Agile, değişime hızlı adapte olabilen, sürekli değer sunan ve müşteri memnuniyetini ön planda tutan bir yaklaşım sunar.
*   **Sprint Nasıl Yapılır, Backlog, Epic vs. (Scrum Ağırlıklı):**
    *   **Sprint:** Belirli bir zaman dilimi (genellikle 2-4 hafta) içinde tamamlanması hedeflenen işlerin planlandığı ve geliştirildiği döngüdür.
        *   **Örnek:** Bir e-ticaret sitesi geliştiriyorsunuz. Bir sprint'iniz, "Sepete ürün ekleme özelliğinin geliştirilmesi" olabilir.
    *   **Backlog:** Üründe olması gereken tüm özelliklerin, iyileştirmelerin ve hataların listelendiği yerdir.
        *   **Örnek:** E-ticaret sitesi için backlog'da şunlar olabilir: "Ürün arama filtresi eklenmeli", "Ödeme yöntemleri çeşitlendirilmeli", "Mobil uygulama performansı iyileştirilmeli".
    *   **Epic:** Büyük, genel iş kalemleridir. Daha küçük parçalara (User Story'lere) ayrılırlar.
        *   **Örnek:** "E-ticaret sitesine kullanıcı yorumları ve değerlendirme özelliği eklenmesi" bir epic olabilir.
    *   **User Story:** Bir kullanıcının gözünden, bir özelliğin ne işe yaradığını ve neden istendiğini anlatan kısa tanımlardır.
        *   **Örnek:** "Bir kullanıcı olarak, ürünleri değerlendirebilmek ve yorum yazabilmek istiyorum, böylece diğer kullanıcılar ürün hakkında daha fazla bilgi edinebilirler."
    *   **Scrum:** Agile'ın en popüler çerçevesidir. Sprint'ler, daily scrum (günlük toplantılar), sprint review (sprint değerlendirme toplantısı) ve sprint retrospective (sprint iyileştirme toplantısı) gibi belirli rolleri ve etkinlikleri içerir.
*   **Diğer Metodolojileri Tanımsal Olarak Anlatma:**
    *   **Kanban:** İş akışını görselleştirmeye ve işlerin sürekli akışını sağlamaya odaklanır.
        *   **Örnek:** Bir destek ekibi, talepleri "Yeni", "İnceleniyor", "Geliştiriliyor", "Test Ediliyor", "Tamamlandı" gibi sütunlara ayırarak Kanban panosu kullanabilir.
    *   **XP (Extreme Programming):** Yazılım kalitesini ve müşteri memnuniyetini artırmak için bir dizi pratik kuralı bir araya getirir. Sürekli entegrasyon, test güdümlü geliştirme (TDD) ve çift programlama gibi teknikleri içerir.
    *   **Lean:** İsrafı azaltmaya ve değeri en üst düzeye çıkarmaya odaklanır.
*   **Jira Üzerinde Örnek Proje:**
    *   Jira, proje yönetimi ve hata takibi için kullanılan popüler bir araçtır.
    *   **Örnek:** Jira'da bir "E-ticaret Sitesi Geliştirme" projesi oluşturulabilir. Bu projede, epic'ler (kullanıcı yorumları, ödeme sistemleri), user story'ler (ürünleri değerlendirme, farklı kredi kartlarıyla ödeme yapma) ve görevler (veritabanı şemasını tasarlama, arayüzü geliştirme) oluşturulabilir. Sprint'ler planlanabilir, görevler kişilere atanabilir ve ilerleme takip edilebilir.

**Yazılım Projeleri Üzerine**

*   **Projeler:**
    *   **Web Uygulaması:** E-ticaret sitesi, sosyal medya platformu, blog sitesi
    *   **Mobil Uygulama:** Bankacılık uygulaması, oyun, fitness uygulaması
    *   **Masaüstü Uygulaması:** Ofis uygulaması (Word, Excel), grafik tasarım programı (Photoshop)
    *   **Gömülü Sistemler:** Akıllı ev cihazları, otomotiv sistemleri
*   **Hangi Diller:**
    *   **Web:** HTML, CSS, JavaScript, Python, Java, PHP, C#
    *   **Mobil:** Swift (iOS), Kotlin (Android), React Native, Flutter
    *   **Masaüstü:** C++, C#, Java, Python
    *   **Veritabanı:** SQL, PL/SQL
*   **Toollar:**
    *   **IDE:** Visual Studio Code, IntelliJ IDEA, Eclipse
    *   **Versiyon Kontrol:** Git
    *   **Proje Yönetimi:** Jira, Trello
    *   **Test:** Selenium, JUnit
*   **Kavramlar:**
    *   **API (Application Programming Interface):** Uygulamaların birbirleriyle iletişim kurmasını sağlayan arayüz.
    *   **Veritabanı:** Verilerin saklandığı ve yönetildiği sistem.
    *   **Algoritma:** Bir problemi çözmek için izlenen adımlar dizisi.
    *   **Veri Yapıları:** Verilerin düzenlenmesi ve saklanması için kullanılan yapılar (diziler, listeler, ağaçlar).
*   **CRM-SAP-CMS-SSO-DWH:**
    *   **CRM (Customer Relationship Management):** Müşteri ilişkilerini yönetmek için kullanılan sistem.
        *   **Örnek:** Salesforce, bir şirketin müşteri verilerini takip etmesine, satış süreçlerini yönetmesine ve müşteri hizmetleri sağlamasına yardımcı olur.
    *   **SAP (Systems, Applications & Products in Data Processing):** İş süreçlerini yönetmek için kullanılan kurumsal kaynak planlama (ERP) sistemi.
        *   **Örnek:** Bir üretim şirketi, SAP kullanarak malzeme yönetimini, üretim planlamasını, finansal muhasebeyi ve insan kaynaklarını entegre bir şekilde yönetebilir.
    *   **CMS (Content Management System):** İçerik oluşturma, düzenleme ve yayınlama süreçlerini kolaylaştıran sistem.
        *   **Örnek:** WordPress, bir blog veya web sitesi oluşturmak ve yönetmek için kullanılan popüler bir CMS'dir.
    *   **SSO (Single Sign-On):** Kullanıcıların tek bir kimlik bilgisiyle birden fazla uygulamaya erişmesini sağlayan sistem.
        *   **Örnek:** Bir şirket, çalışanlarının şirket içi tüm uygulamalara (e-posta, CRM, proje yönetimi) tek bir kullanıcı adı ve şifreyle erişmesini sağlamak için SSO kullanabilir.
    *   **DWH (Data Warehouse):** Farklı kaynaklardan gelen verileri bir araya getirerek analiz ve raporlama için kullanılan sistem.
        *   **Örnek:** Bir perakende şirketi, satış verilerini, müşteri verilerini ve pazarlama verilerini bir DWH'de birleştirerek satış trendlerini analiz edebilir, müşteri segmentlerini belirleyebilir ve pazarlama stratejilerini optimize edebilir.

**DevOps**

*   **DevOps (Detaylı Teorik):**
    *   **Tanım:** Yazılım geliştirme (Development) ve operasyon (Operations) ekiplerinin işbirliğini ve otomasyonunu teşvik eden bir kültür, felsefe ve bir dizi uygulamadır. Amaç, yazılım geliştirme süreçlerini hızlandırmak, güvenilirliği artırmak ve daha sık ve daha hızlı yazılım yayınlamaktır.
    *   **Temel İlkeler:**
        *   **Kültür:** İşbirliği, şeffaflık, güven ve sürekli öğrenme.
        *   **Otomasyon:** Tekrarlayan görevlerin otomatikleştirilmesi.
        *   **Ölçme:** Performansı izlemek ve iyileştirmek için metriklerin kullanılması.
        *   **Paylaşım:** Bilgi ve deneyimlerin ekipler arasında paylaşılması.
*   **DevOps Tools:**
    *   **Versiyon Kontrol:** Git, SVN
    *   **Sürekli Entegrasyon:** Jenkins, GitLab CI, CircleCI
    *   **Sürekli Teslimat:** Spinnaker, Argo CD
    *   **Configuration Management:** Ansible, Puppet, Chef
    *   **Containerization:** Docker, Kubernetes
    *   **Monitoring:** Prometheus, Grafana, ELK Stack
*   **CI/CD Pipeline, Build Almak vs.:**
    *   **CI/CD (Continuous Integration/Continuous Delivery):** Yazılım değişikliklerinin otomatik olarak test edildiği, derlendiği ve yayınlandığı bir süreçtir.
        *   **CI (Continuous Integration):** Geliştiricilerin kod değişikliklerini sık sık (genellikle günde birkaç kez) merkezi bir depoya entegre etmelerini ve otomatik testlerin çalıştırılmasını sağlar.
        *   **CD (Continuous Delivery/Deployment):** Kod değişikliklerinin otomatik olarak test ortamlarına veya üretim ortamlarına yayınlanmasını sağlar.
    *   **Build Almak:** Kaynak kodunun derlenerek çalıştırılabilir bir hale getirilmesi işlemidir.
        *   **Örnek:** Java kodunu .jar dosyasına, C# kodunu .exe dosyasına dönüştürmek.
*   **Monitoring:**
    *   Sistemlerin ve uygulamaların performansını, sağlığını ve güvenliğini sürekli olarak izleme işlemidir.
    *   **Örnek:** CPU kullanımı, bellek kullanımı, disk alanı, ağ trafiği, hata oranları gibi metriklerin izlenmesi.
*   **Load Balancing:**
    *   Gelen ağ trafiğini birden fazla sunucuya dağıtarak performansı artırma ve yükü dengeleme işlemidir.
    *   **Örnek:** Bir web sitesinin trafiği çok arttığında, load balancer trafiği birden fazla web sunucusuna dağıtarak sitenin çökmesini önler.

**Domain Kayıtları**

*   **Domain Kayıtları (DNS, A, TXT, MX, IP, HOST):**
    *   **DNS (Domain Name System):** Alan adlarını IP adreslerine çeviren sistemdir.
        *   **Örnek:** `www.example.com` alan adının IP adresi `192.0.2.1` ise, DNS bu çeviriyi yapar.
    *   **A Kaydı:** Bir alan adını bir IP adresine yönlendirir.
        *   **Örnek:** `www.example.com` için bir A kaydı, `192.0.2.1` IP adresini işaret edebilir.
    *   **TXT Kaydı:** Alan adı hakkında metin tabanlı bilgiler içerir. Genellikle e-posta doğrulaması (SPF, DKIM) veya alan adı sahipliğini kanıtlamak için kullanılır.
    *   **MX Kaydı:** Alan adının e-posta trafiğini hangi posta sunucusuna yönlendireceğini belirtir.
        *   **Örnek:** `example.com` alan adının MX kaydı, e-postaların `mail.example.com` posta sunucusuna yönlendirilmesini sağlar.
    *   **IP (Internet Protocol) Adresi:** Bir cihazın internet üzerindeki benzersiz adresidir.
    *   **HOST Dosyası:** DNS sunucularına başvurmadan alan adlarını IP adresleriyle eşleştirmek için kullanılan yerel bir dosyadır. Genellikle test amaçlı kullanılır.

**Email**

*   **Email (SMTP):**
    *   **SMTP (Simple Mail Transfer Protocol):** E-posta göndermek için kullanılan protokoldür.
        *   **Örnek:** Bir e-posta istemcisi (Outlook, Gmail), e-postaları bir SMTP sunucusuna gönderir. SMTP sunucusu, e-postayı alıcının posta sunucusuna iletir.

**IP Adresleri**

*   **IP Adresleri, Subnet, Private IP vs.:**
    *   **Subnet (Alt Ağ):** Bir ağın daha küçük parçalara bölünmesidir. Alt ağlar, ağ trafiğini yönetmeyi ve güvenliği artırmayı kolaylaştırır.
    *   **Private IP (Özel IP) Adresi:** Yalnızca yerel ağlarda kullanılan IP adresleridir. İnternet üzerinde doğrudan erişilemezler.
        *   **Örnek:** `192.168.1.1`, `10.0.0.1` gibi adresler özel IP adresleridir.

**WAF**

*   **WAF (Web Application Firewall):** Web uygulamalarını zararlı trafiğe karşı koruyan bir güvenlik duvarıdır.
    *   **Örnek:** SQL injection, cross-site scripting (XSS) gibi saldırıları engeller.

**VPN**

*   **VPN (Virtual Private Network):** İnternet üzerinde şifreli bir bağlantı oluşturarak güvenli ve özel bir ağ bağlantısı sağlar.
    *   **Örnek:** Evden çalışan bir çalışan, şirket ağına güvenli bir şekilde erişmek için VPN kullanabilir.

**SSL**

*   **SSL (Secure Sockets Layer):** İki cihaz arasında güvenli ve şifreli bir bağlantı kuran bir protokoldür. Artık TLS (Transport Layer Security) olarak adlandırılır.
    *   **Örnek:** Bir web sitesinin SSL sertifikası varsa, tarayıcı ile sunucu arasındaki iletişim şifrelenir ve hassas verilerin (kredi kartı bilgileri, şifreler) güvenliği sağlanır.

**Cloud**

*   **Cloud (Azure, AWS, GCP):**
    *   **Bulut Bilişim:** Bilgisayar kaynaklarının (sunucular, depolama, veritabanları, yazılımlar) internet üzerinden sağlanmasıdır.
    *   **Azure (Microsoft Azure):** Microsoft'un bulut platformudur.
    *   **AWS (Amazon Web Services):** Amazon'un bulut platformudur.
    *   **GCP (Google Cloud Platform):** Google'ın bulut platformudur.
*   **SAAS, IAAS, PAAS:**
    *   **SaaS (Software as a Service):** Yazılımın internet üzerinden hizmet olarak sunulmasıdır.
        *   **Örnek:** Gmail, Salesforce, Dropbox
    *   **IaaS (Infrastructure as a Service):** Sanal sunucular, depolama, ağ gibi altyapı kaynaklarının internet üzerinden sunulmasıdır.
        *   **Örnek:** AWS EC2, Azure Virtual Machines, Google Compute Engine
    *   **PaaS (Platform as a Service):** Uygulama geliştirmek, çalıştırmak ve yönetmek için kullanılan bir platformun internet üzerinden sunulmasıdır.
        *   **Örnek:** Heroku, Google App Engine, AWS Elastic Beanstalk
*   **CDN (Content Delivery Network):**
    *   İnternet içeriğini (resimler, videolar, web sayfaları) kullanıcılara daha hızlı ve verimli bir şekilde ulaştırmak için kullanılan dağıtık sunucu ağıdır.
    *   **Örnek:** Bir web sitesinin CDN kullanması, kullanıcıların dünyanın neresinde olursa olsun web sitesine daha hızlı erişmesini sağlar.

**Webserver**

*   **Webserver (IIS, Nginx, Apache2):**
    *   **Web Sunucusu:** İstemcilerden (tarayıcılar) gelen HTTP isteklerini işleyerek web sayfalarını ve diğer kaynakları sunan yazılımdır.
    *   **IIS (Internet Information Services):** Microsoft'un web sunucusudur.
    *   **Nginx:** Popüler bir açık kaynaklı web sunucusudur.
    *   **Apache2:** Popüler bir açık kaynaklı web sunucusudur.

**Dizin/Dosya Güvenliği**

*   **Dizin/Dosya Güvenliği (.rar, .zip, .txt):**
    *   **Dizin ve dosya güvenliği,** hassas verilerin yetkisiz erişime, değiştirilmeye veya silinmeye karşı korunmasıdır.
    *   **Önlemler:**
        *   **Erişim Kontrolü:** Kullanıcıların yalnızca yetkili oldukları dizinlere ve dosyalara erişebilmesini sağlamak.
        *   **Şifreleme:** Hassas verileri şifreleyerek yetkisiz erişimi engellemek.
        *   **Güncel Tutma:** İşletim sistemlerini ve yazılımları güncel tutarak güvenlik açıklarını kapatmak.
        *   **.rar, .zip, .txt gibi dosya türleri:** Bu dosyaların içeriğinin kötü amaçlı yazılım içermediğinden emin olmak önemlidir. Güvenilmeyen kaynaklardan gelen dosyalar açılmamalı veya taranmalıdır.

**GIT**

*   **GIT:**
    *   Dağıtık bir versiyon kontrol sistemidir. Yazılım projelerinde yapılan değişiklikleri takip etmek ve yönetmek için kullanılır.
    *   **Temel Kavramlar:**
        *   **Repository (Depo):** Proje dosyalarının ve değişiklik geçmişinin saklandığı yer.
        *   **Commit:** Yapılan değişikliklerin kaydedilmesi.
        *   **Branch (Dal):** Projenin farklı versiyonlarını geliştirmek için kullanılan paralel geliştirme hattı.
        *   **Merge (Birleştirme):** Farklı dallarda yapılan değişiklikleri bir araya getirme.

**Pozisyonlar ve Görevleri**

*   **Yazılım Geliştirici (Software Developer):** Kod yazma, test etme ve bakımını yapma.
*   **Sistem Yöneticisi (System Administrator):** Sunucuları ve altyapıyı yönetme.
*   **Veritabanı Yöneticisi (Database Administrator):** Veritabanlarını yönetme ve optimize etme.
*   **Ağ Mühendisi (Network Engineer):** Ağ altyapısını tasarlama, kurma ve yönetme.
*   **DevOps Mühendisi (DevOps Engineer):** Yazılım geliştirme ve operasyon süreçlerini otomatikleştirmek ve iyileştirmek.
*   **Güvenlik Uzmanı (Security Specialist):** Sistemleri ve ağları güvenlik tehditlerine karşı koruma.
*   **Proje Yöneticisi (Project Manager):** Projeleri planlama, yürütme ve takip etme.
*   **İş Analisti (Business Analyst):** İş gereksinimlerini analiz etme ve yazılım gereksinimlerine dönüştürme.
*   **Test Uzmanı (Test Specialist):** Yazılımı test etme ve hataları bulma.

**Pentest**

*   **Pentest (Penetration Testing):**
    *   Bir sistemin, ağın veya uygulamanın güvenlik açıklarını bulmak ve istismar etmek için yapılan yetkili bir saldırı simülasyonudur.

**Loadtest (Stresstest)**

*   **Loadtest (Stresstest):**
    *   Bir sistemin belirli bir yük altında nasıl performans gösterdiğini test etmek için yapılan bir test türüdür. Amaç, sistemin sınırlarını belirlemek ve performans sorunlarını tespit etmektir.

**Databaseler**

*   **Databaseler:**
    *   **SQL (Structured Query Language) Veritabanları:**
        *   **Örnek:** MySQL, PostgreSQL, Microsoft SQL Server, Oracle
    *   **NoSQL (Not Only SQL) Veritabanları:**
        *   **Örnek:** MongoDB, Cassandra, Redis

**İşletim Sistemleri**

*   **İşletim Sistemleri Windows-Linux:**
    *   **Windows:** Microsoft tarafından geliştirilen bir işletim sistemidir.
    *   **Linux:** Açık kaynaklı bir işletim sistemidir.
        *   **Dağıtımlar:** Ubuntu, Debian, Fedora, CentOS

**Testing**

*   **Testing - Unit, UAT, Automated:**
    *   **Unit Test (Birim Testi):** Kodun en küçük birimlerinin (fonksiyonlar, metotlar) doğru çalışıp çalışmadığını test etmek.
    *   **UAT (User Acceptance Testing) (Kullanıcı Kabul Testi):** Son kullanıcıların uygulamayı test ederek iş gereksinimlerini karşılayıp karşılamadığını doğrulaması.
    *   **Automated Testing (Otomatik Test):** Test senaryolarının otomatik olarak çalıştırılması.

**İleri Düzey Kavramlar**

*   **Message Queue:**
    *   Uygulamalar arasında asenkron iletişim sağlamak için kullanılan bir kuyruk sistemidir.
*   **Redis, Rabbitmq:**
    *   **Redis:** Bellek içi veri yapısı deposu olarak kullanılan açık kaynaklı bir NoSQL veritabanıdır.
    *   **RabbitMQ:** Açık kaynaklı bir mesaj kuyruğu yazılımıdır.
*   **Kubernetes:**
    *   Container'ize edilmiş uygulamaların dağıtımını, ölçeklenmesini ve yönetimini otomatikleştiren bir container orkestrasyon platformudur.

**MVC Nedir?**

*   **MVC (Model-View-Controller):**
    *   Bir yazılım tasarım modelidir. Uygulamayı üç ana bileşene ayırır:
        *   **Model:** Uygulamanın verilerini ve iş mantığını temsil eder.
        *   **View:** Kullanıcı arayüzünü (UI) temsil eder.
        *   **Controller:** Kullanıcının girdilerini alır, modeli günceller ve view'i günceller.

**Docker**

*   **Docker:**
    *   Uygulamaları ve bağımlılıklarını bir araya getirerek container'lar içinde paketlemeyi ve çalıştırmayı sağlayan bir platformdur.

**Microservices**

*   **Microservices:**
    *   Bir uygulamayı küçük, bağımsız ve ölçeklenebilir hizmetlere bölme yaklaşımıdır.

**VM Nedir?**

*   **VM (Virtual Machine):**
    *   Fiziksel bir bilgisayar üzerinde çalışan sanal bir bilgisayardır.


