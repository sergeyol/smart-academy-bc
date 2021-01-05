# Предварительные материалы для ознакомления

Перед началом академии рекомендуем вам пройти ознакомительные курсы на [Microsoft Learn](https://docs.microsoft.com/learn/). Для этого вам нужно будет завести себе профиль на этом сайте. Перед началом мы попросим вас отправить публичную ссылку на этот профиль, где будет видны все пройденные вами курсы.


Основная информация о продукте Microsoft Dynamics 365 Business Central, в том числе короткий guided tour:

https://dynamics.microsoft.com/en-us/business-central/overview/

 

### Короткий обзор функциональности:

[Introducing Microsoft Dynamics 365 Business Central](https://docs.microsoft.com/learn/modules/intro-dynamics-365-business-central/)

[Customize Microsoft Dynamics 365 Business Central](https://docs.microsoft.com/learn/modules/customize-dynamics-365-business-central/)

### Вступление в разработку:

[Get started with development in Microsoft Dynamics 365 Business Central](https://docs.microsoft.com/learn/paths/development-get-started-business-central/)


Если вы не имели опыта работы с Git, просмотрите также:

[Introduction to version control with Git](https://docs.microsoft.com/learn/paths/intro-to-vc-git/)

### Материалы "со звездочкой"

Если не будет терпеться продолжить самостоятельно изучение "наперед" :), Академию мы начнем с вот этих двух курсов:

[Discover the foundation of customizing Microsoft Dynamics 365 Business Central](https://docs.microsoft.com/learn/paths/foundation-customize-business-central/)

[Learn the application foundation with the AL programming language for Microsoft Dynamics 365 Business Central](https://docs.microsoft.com/learn/paths/application-foundation-al-language/)

# Демо-среда

Для выполнения материалов вам понадобится демо-среда, и это пожалуй самая непростая часть :) Есть два варианта:

## 1. Виртуальная машина в Microsoft Azure

Возможно, у вас уже есть студенческая подписка Azure. Если нет, можно оформить пробную подписку с кредитом в $200, этого должно хватить на несколько месяцев при экономном использовании ресурсов.

Если подписка у вас уже есть, по ссылке https://aka.ms/getbc доступен шаблон создания виртуальной машины с Business Central.

Большинство параметров можно оставить значениями по умолчанию, кроме:
 - Resource Group - создать новую ресурсную группу
 - VM Name - указать уникальное имя виртуальной машины
 - Accept EULA - указать Yes
 - Vm Size - выбрать размер поменьше, например, Standard_D2s_v3, чтобы машина потребляла меньше ресурсов
 - Password - указать пароль
 - Contact E Mail For Lets Encrypt - укажите адрес электронной почты, и тогда для виртуальной машины сгенерируется бесплатный сертификат Lets Encrypt.
 
После успешного создания машины по ее внешнему адресу, который можно посмотреть в свойствах (напр., http://acad-test.westeurope.cloudapp.azure.com/) будет доступен статус установки и, затем, все ссылки для подключения.

В свойствах виртуальной машины ее размер можно затем уменьшить до B2s или B2ms, что позволит еще уменьшить потребление кредита.

## 2. Локальная установка

Последняя на текущий момент версия продукта - 17.2 - доступна для скачивания по адресу: 
https://www.microsoft.com/en-us/download/details.aspx?id=102531

Нужен файл Dynamics.365.BC.19735.RU.DVD.zip, внутри находится DVD-образ для установки.

Инструкция по установке: https://docs.microsoft.com/en-us/dynamics365/business-central/dev-itpro/deployment/deploy-demonstration-environment
