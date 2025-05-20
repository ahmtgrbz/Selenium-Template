# Selenium ile Test Otomasyonu - Template Projesi Kurulum Rehberi

Bu döküman, Selenium ile test otomasyonu eğitimine katılacak arkadaşlar için base projenin kurulum adımlarını içermektedir.

***Önemli Not***: Kurulumu yapabilmek ve paketleri indirebilmek için aşağıdaki adımları takip ederken bağlı olduğunuz ağdan [mvnrepository](https://mvnrepository.com/) adresine adresine erişebiliyor olmanız gerekmetedir. Kişisel ağınıza bağlanıp aşağıdaki kurulumu takip edip paketleri tek seferliğe mahsus indirebilir daha sonrasında kullanabilirsiniz.
   

## İçindekiler

1.  [Gerekli yüklemeler ](#Gerekli-yüklemeler)
2.  [Kurulum Adımları](#kurulum-adımları)
    1.  [Projeyi GitHub'dan İndirme](#1-projeyi-githubdan-i̇ndirme)
    2.  [Projeyi IntelliJ IDEA ile Açma](#2-projeyi-intellij-idea-ile-açma)
    3.  [Maven Bağımlılıklarının Yüklenmesi](#3-maven-bağımlılıklarının-yüklenmesi)
    4.  [Yüklemenin Kontrol Edilmesi ve Projeye Başlama](#4-yüklemenin-kontrol-edilmesi-ve-projeye-başlama)

---

## Gerekli yüklemeler

Bu eğitime katılacak arkadaşların temel Java bilgilerinin olması gerekmekte.

Bunun dışında cihazlarında aşağıdaki yazılım ve araçların kurulu olması beklenmektedir:

*   **Java Development Kit (JDK)**: Java 23 (örn: OpenJDK 23)
    *   İndirme linki: [Oracle JDK 23 Arşivi](https://www.oracle.com/java/technologies/javase/jdk23-archive-downloads.html)
*   **IntelliJ IDEA Community Edition**:
    *   İndirme linki: [JetBrains IntelliJ IDEA](https://www.jetbrains.com/idea/download/)
*   **Web Tarayıcıları**:
    *   Google Chrome (Güncel versiyon)
    *   Mozilla Firefox (Güncel versiyon)
*   **Selenium IDE Uzantısı**: (Chrome için önerilir)
    *   İndirme linki: [Selenium IDE](https://www.selenium.dev/selenium-ide/)
*   **ChromeDriver**: Kendi cihazınızdaki Chrome versiyonuna uygun WebDriver.
    *   İndirme linki: [Chrome for Testing](https://googlechromelabs.github.io/chrome-for-testing/)
    *   _Not: Proje içerisinde WebDriverManager kütüphanesi kullanıldığı için bu adımı manuel yapmak yerine, projenin kendisinin uygun driver'ı indirmesini de sağlayabiliriz. Ancak yedek olarak veya belirli bir versiyonu kullanmak isterseniz bu linkten indirebilirsiniz._
*   **Maven Bilgisi ve Paket Yönetimi**: Proje yapımızı kurabilmeleri ve eğitim içinde beni takip edebilmeleri için Maven ile de paket indirebiliyor olmaları gerekmekte. Projemiz `pom.xml` dosyası aracılığıyla aşağıdaki temel Maven bağımlılıklarını kullanacaktır (IntelliJ IDEA bunları aşağıdaki kurulumu yaptığınızda otomatik olarak indirecektir):
    *   Selenium Java ([mvnrepository](https://mvnrepository.com/artifact/org.seleniumhq.selenium/selenium-java))
    *   WebDriverManager ([mvnrepository](https://mvnrepository.com/artifact/io.github.bonigarcia/webdrivermanager))
    *   TestNG ([mvnrepository](https://mvnrepository.com/artifact/org.testng/testng))
    *   JUnit Jupiter API ([mvnrepository](https://mvnrepository.com/artifact/org.junit.jupiter/junit-jupiter-api))

---



Eğitimi takip etmek istediğiniz cihaza bu projeyi indirip aşağıdaki adımları uygulayabilirsiniz:

## Kurulum Adımları

### 1. Projeyi GitHub'dan İndirme

![image](https://drive.google.com/uc?export=view&id=1EQNdzhebyjHaZKJ3iKBb3uiRV2fWTVI5)

### 2. Projeyi IntelliJ IDEA ile Açma

![image](https://drive.google.com/uc?export=view&id=1Y7o43IpPa6rZTjfh40N91OciFmKguRhX)

### 3. Maven Bağımlılıklarının Yüklenmesi

Proje IntelliJ IDEA'da açıldıktan sonra, Maven projenin ihtiyaç duyduğu kütüphaneleri (bağımlılıkları) otomatik olarak indirmeye çalışacaktır. Ancak indermediyse bu süreci kontrol edebilir ve manuel olarak tetikleyebilirsiniz:

![image](https://drive.google.com/uc?export=view&id=11XTTb8YuObHDGGUSsIJ7KboWgLExlhNK)

**Alternatif Maven Senkronizasyon Yöntemi:**

![image](https://drive.google.com/uc?export=view&id=1E-va_0I51Vj7kQmskrR7w_Sf_MpIOtLI)

### 4. Yüklemenin Kontrol Edilmesi ve Projeye Başlama

![image](https://drive.google.com/uc?export=view&id=1hnW6nUCV-9vwQQeBZM32mm0pszvU6Ak-)

---

Artık Selenium test otomasyon projeniz eğitime başlamak için hazır! Herhangi bir sorunla karşılaşırsanız, yukarıdaki adımları tekrar gözden geçirin veya eğitmeninizle iletişime geçin.
