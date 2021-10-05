# EduBot
## EduBot Nedir?

EduBot, her okulda sıkça sorulan soruları cevaplamayı hedefler. Okulunuzun kurumsal iletişim bilgilerini, misyon ve vizyonunu, ücretler ve burslar ile ilgili bilgileri, mezun başarılarınızı, yurtdışı imkanlarınızı ve daha pek çok konuyu bu asistanınız ile cevaplayabilirsiniz.




## [Gereksinimler](#edubotu-nasıl-kullanabilirim-gereksinimler)
*EduBot'u kullanabilmeniz için gerekli servisler.*

1. [Azure Hesabı](#1-azure-hesabı-oluşturma)
2. [Bot Composer](#2-bot-composer-kurulum)
3. [Language Understanding Service (LUIS)](#3-language-understanding-service-luis)
4. [QnA Maker](#4-qna-maker)



## [Kurulum](#edubotu-nasıl-kullanabilirim--kurulum)
*EduBot kurulum aşamaları.*
1. [EduBot'u Kurun!](#1-edubotu-kurun)
2. [EduBot'u Publish Edin](#2-edubotu-publish-edin)



# EduBot'u Nasıl Kullanabilirim: Gereksinimler

## 1. Azure Hesabı Oluşturma
Ücretsiz [Azure hesabı](https://azure.microsoft.com/en-us/free/cognitive-services/) oluşturun.

## 2. Bot Composer Kurulum
Size uygun işletim sistemini seçerek [Bot Composer](https://docs.microsoft.com/en-us/composer/install-composer?tabs=windows)'ı indirmek için önce [Node.js LTS 14.x](https://nodejs.org/)'i npm ile birlikte ve [.NET Core SDK](https://dotnet.microsoft.com/download/dotnet-core/3.1)'ı indirmelisiniz.

Daha sonra Bot Composer'ı indirip kurabilirsiniz.

<img src="https://raw.githubusercontent.com/msft-ai-demos/MICO-BOT/main/Additional/ss1.png" width=25% height=25%>

### 2.1. Node.js ve npm
Node.js JavaScript platformunu ve npm paketini yüklemeniz Composer'ın Node.js modellerini çalıştırabilmesine imkan tanır. [Node.js LTS 14.x](https://nodejs.org/)'i npm ile birlikte indirin. Bu Composer'ı kullanabilmek için zorunlu bir servistir.

### 2.2. .NET Core SDK
[.NET Core SDK](https://dotnet.microsoft.com/download/dotnet-core/3.1)'ı indirin. C# dilini kullanarak botunuzu oluşturabilmeniz için bu servis gereklidir.

Bot Composer'ı çalıştırın.

<img src="https://raw.githubusercontent.com/msft-ai-demos/MICO-BOT/main/Additional/ss2.png" width=50% height=50%>

## 3. Language Understanding Service (LUIS)
Language Understanding (LUIS), kullanıcıların doğal dil kullanarak uygulamalarınız, botlarınız ve IoT cihazlarınızla etkileşim kurmasına olanak sağlayan bir doğal dil anlama (NLU) yapay zeka hizmetidir. [LUIS](https://docs.microsoft.com/en-us/azure/cognitive-services/luis/sign-in-luis-portal) hizmetini kullanmaya başlayın.

## 4. QnA Maker 
Soru-Cevap Oluşturma Servisi, bilgileri kategorilere ayırarak konuşma bağlamında kullanılabilen ve kolayca bulunabilen yanıtlar elde edilmesini sağlar. [Soru-Cevap Oluşturma Servisini](https://docs.microsoft.com/en-us/azure/cognitive-services/QnAMaker/how-to/set-up-qnamaker-service-azure?tabs=v1) kullanmaya başlayın.




# EduBot'u Nasıl Kullanabilirim : Kurulum

## 1. EduBot'u Kurun!
Bot Composer'ı başarılı bir şekilde indirdikten ve gerekli sevisleri oluşturduktan sonra, artık EduBot'u kurmak ve çalıştırmak için yapmanız gerekenlere başlayabilirsiniz.
İlk olarak bu repository'de yer alan Edu-Bot isimli Bot klasörünü lokalinize indirin veya bu repository'yi klonlayın.

Extract ettiğiniz bot dosyasını composerı açarak, composer içerisinden seçip bulun.

Daha Sonra EduBot'u Bot Composer içerisinden açabilmelisiniz.

<img src="https://raw.githubusercontent.com/YagmurKirarslan/EduBot/main/Screenshots/Kurulum/ss0.png" width=80% height=80%>


## 2. EduBot'u Publish Edin

EduBot'u publish edebilmek için yapmanız gereken ilk şey, bir Publishing Profile oluşturmak. Bu adımı tamamen composer içerisinden tamamlayabilirsiniz.

![image](https://raw.githubusercontent.com/YagmurKirarslan/EduBot/main/Screenshots/Kurulum/ss1.png)


