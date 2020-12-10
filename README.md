# Awesome DevSecOps на русском языке [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

![DevSecOps-Russia](https://github.com/Swordfish-Security/awesome-devsecops-russia/blob/master/Awesome-DevSecOps.png)

Полная обновляемая подборка материалов по безопасной разработке, DevSecOps и SSDLC на русском языке.

# Содержание
* [Каналы](#каналы)
* [Чаты](#чаты)
* [Статьи](#статьи)
  * [Dev](#dev)
  * [Ops](#ops)
* [Доклады](#доклады)
  * [Dev](#dev-1)
  * [Ops](#ops-1)
 * [Подкасты](#подкасты)
 * [Стандарты и нормативные документы](#стандарты-и-нормативные-документы)
 * [Курсы](#курсы)
 * [Инструменты](#инструменты)
   * [Инструменты для моделирования угроз (Threat modeling)](#инструменты-для-моделирования-угроз-threat-modeling)
   * [Статические анализаторы приложений (SAST)](#статические-анализаторы-приложений-sast)
   * [Динамические анализаторы приложений (DAST)](#динамические-анализаторы-приложений-dast)
   * [Поиск секретов](#поиск-секретов)
   * [Анализаторы сторонних компонентов (SCA)](#анализаторы-сторонних-компонентов-sca)
   * [Тестирование по принципам Behaviour Driven Development](#тестирование-по-принципам-behaviour-driven-development)
   * [Сканеры Docker образов](#сканеры-docker-образов)
   * [Проверка Docker / Kubernetes на соответствие](#проверка-docker--kubernetes-на-соответствие)
   * [Безопасность Kubernetes](#безопасность-kubernetes)
   * [Container Runtime](#container-runtime)
   * [Коммерческие комплексные решения Cloud Native Security Platform](#коммерческие-комплексные-решения-cloud-native-security-platform)
   * [Runtime Security](#runtime-security)
   * [IAST](#iast)
   * [Fuzzing](#fuzzing)
   * [Vulnerability Management](#vulnerability-management)
   * [Compliance-as-code](#compliance-as-code)
   * [IAC Security](#iac-security)
   * [Безопасность AWS](#безопасность-aws)
   * [Безопасность GCP](#безопасность-gcp)
   * [Другие общие подборки по DevSecOps инструментам](#другие-общие-подборки-по-devsecops-инструментам)

## Каналы
* [DevSecOps Wine](https://t.me/sec_devops)
* [Технологический Болт Генона](https://t.me/tech_b0lt_Genona)
* [k8s (in)security](https://t.me/k8security)
* [DevSecOps Talks](https://t.me/devsecops_weekly)

## Чаты
* [DevSecOps - русскоговорящее сообщество](https://t.me/devsecops_ru)
* [DevSecOps Wine Chat](https://t.me/sec_devops_chat)

## Статьи
### Dev
*	[2020-10-01]	[Как написать правила для Checkmarx и не сойти с ума, Юрий Шабалин, Swordfish Security](https://habr.com/ru/company/swordfish_security/blog/521396/)
*	[2020-09-18]	[Pysa: как избежать проблем безопасности в коде Python,перевод Graham Bleaney, Sinan Cepel,SkillFactory](https://habr.com/ru/company/skillfactory/blog/519702/)
*	[2020-09-17]	[Строим безопасную разработку в ритейлере. Опыт одного большого проекта, Иван Старосельский, Solar Security](https://habr.com/ru/company/solarsecurity/blog/519428/)
*	[2020-09-14]	[От Threat Modeling до безопасности AWS - 50+ open-source инструментов для выстраивания безопасности DevOps, Денис Якимов, Swordfish Security](https://habr.com/ru/company/swordfish_security/blog/518758/)
*	[2020-09-10]	[DevSecOps: организация фаззинга исходного кода, Дмитрий Евдокимов,Никита Кныжов,Павел Князев, Digital Security](https://habr.com/ru/company/dsec/blog/517596/)
*	[2020-08-26]	[DevSecOps: принципы работы и сравнение SCA. Часть первая, Денис Якимов, Swordfish Security](https://habr.com/ru/company/swordfish_security/blog/516660/)
*	[2020-08-20]	[Безопасность npm пакетов, Слава Фомин, ДомКлик](https://habr.com/ru/company/domclick/blog/515848/),[2](https://habr.com/ru/company/domclick/blog/516792/),[3](https://habr.com/ru/company/domclick/blog/518502/)
*	[2020-05-28]	[(S)SDLC, или Как сделать разработку безопаснее, Ярослав Александров, Ростелеком Solar](https://habr.com/ru/company/solarsecurity/blog/497864/),[2](https://habr.com/ru/company/solarsecurity/blog/499860/)
*	[2020-05-26]	[DevOps vs DevSecOps: как это выглядело в одном банке, Техносерв](https://habr.com/ru/company/technoserv/blog/503720/)
*	[2020-04-22]	[Как сэкономить время и силы на внедрении стандартов безопасной разработки с помощью OWASP SAMM, OZON](https://habr.com/ru/company/ozontech/blog/498272/)
*	[2020-03-24]	[Используем Zap Baseline Scan для непрерывного сканирования сайта на уязвимости, Александр Тютин](https://habr.com/ru/post/493778/)
*	[2020-02-04]	[Какая разница между DevOps и DevSecOps?](https://www.viva64.com/ru/b/0710/)
*	[2020-02-04]	[Статическое тестирование безопасности опенсорсными инструментами, Александра Сватикова, Одноклассники](https://habr.com/ru/company/odnoklassniki/blog/486722/), [[доклад]](https://youtu.be/E87YkXhdxAA)
*	[2020-01-13]	[Использование сканера уязвимостей в используемых библиотеках Dependency-Check в GitlabCI, Пацев Антон](https://habr.com/ru/post/483716/)
*	[2019-12-17]	[Практические ответы на нетривиальные вопросы, или Как внедрять DevSecOps в организации со сложным IT-ландшафтом, ВТБ](https://habr.com/ru/company/vtb/blog/479082/)
*	[2019-12-12]	[«Hello, Checkmarx!». Как написать запрос для Checkmarx SAST и найти крутые уязвимости, Maxim Tyukov, DINS](https://habr.com/ru/company/dins/blog/477742/)
*	[2019-04-18]	[Страх и ненависть DevSecOps, доклад Юрия Шабалин, перевод в текст Александра Титова](https://habr.com/ru/company/oleg-bunin/blog/448488/)
*	[2018-01-11]	[Как внедрить Secure Development Lifecycle и не поседеть. Рассказ Яндекса на ZeroNights 2017, Яндекс](https://habr.com/ru/company/yandex/blog/346426/)
*	[2017-09-17]	[Мечтают ли WAF’ы о статанализаторах, Владимир Кочетков, PT](https://habr.com/ru/company/pt/blog/338110/)
*	[2016-07-08]	[Ищем уязвимости в коде: теория, практика и перспективы SAST, Владимир Кочетков, PT](https://habr.com/ru/company/pt/blog/305000/)
*	[2014-05-29]	[Об анализе исходного кода и автоматической генерации эксплоитов, Владимир Кочетков, PT](https://habr.com/ru/company/pt/blog/224547/)
### Ops
*	[2020-07-15]	[Валидация Kubernetes YAML на соответствие лучшим практикам и политикам, перевод Amit Saha, Flant](https://habr.com/ru/company/flant/blog/511018/)
*	[2020-06-10]	[Контейнеры для приложений: риски безопасности и ключевые решения по защите, Денис Якимов, КРОК](https://www.anti-malware.ru/Market_Analysis/Application-containers-security-risks-and-key-security-solutions)
*	[2020-03-10]	[Как автоматизировать безопасность контейнеров в стиле Policy as Code с помощью CRD, перевод Niteen Kole, Mail.ru](https://habr.com/ru/company/mailru/blog/490796/)
*	[2019-12-30]	[Seccomp в Kubernetes: 7 вещей, о которых надо знать с самого начала, перевод Paulo Gomes, Flant](https://habr.com/ru/company/flant/blog/481114/)
*	[2019-09-27]	[Азбука безопасности в Kubernetes: аутентификация, авторизация, аудит, Олег Вознесенский, Flant](https://habr.com/ru/company/flant/blog/468679/)
*	[2019-09-12]	[Выход за пределы pod'а в Kubernetes через монтирование логов, перевод Daniel Sagi, Flant](https://habr.com/ru/company/flant/blog/466625/)
*	[2019-08-28]	[33+ инструмента для безопасности Kubernetes, перевод статьи Mateo Burillo, Flant](https://habr.com/ru/company/flant/blog/465141/)
*	[2019-08-07]	[Безопасность Helm, доклад Александра Хаерова, Chainstack](https://habr.com/ru/company/oleg-bunin/blog/462665/), [[доклад]](https://youtu.be/_8zNTJ1_R5I)
*	[2019-07-04]	[Способы и примеры внедрения утилит для проверки безопасности Docker, Павел Канн, Swordfish Security](https://swordfishsecurity.ru/docker-security-scanning-examples)
*	[2019-06-26]	[Обзор утилит безопасности Docker, Павел Канн, Swordfish Security](https://swordfishsecurity.ru/blog/obzor-utilit-bezopasnosti-docker)
*	[2019-05-29]	[Безопасность Docker, Павел Канн, Swordfish Security](https://swordfishsecurity.ru/blog/docker_security)
*	[2019-04-29]	[Введение в сетевые политики Kubernetes для специалистов по безопасности, перевод статьи Reuven Harrison, Flant](https://habr.com/ru/company/flant/blog/443190/)
*	[2019-04-21]	[Шпаргалки по безопасности: Docker, Acribia](https://habr.com/ru/company/acribia/blog/448704/)
*	[2019-01-18]	[9 лучших практик по обеспечению безопасности в Kubernetes, Андрей Сидоров, Flant](https://habr.com/ru/company/flant/blog/436300/)
*	[2018-09-11]	[Понимаем RBAC в Kubernetes, перевод статьи Javier Salmeron, Flant](https://habr.com/ru/company/flant/blog/422801/)
*	[2018-07-25]	[11 способов (не) стать жертвой взлома в Kubernetes, перевод статьи Andrew Martin, Flant](https://habr.com/ru/company/flant/blog/417905/)
*	[2017-10-03]	[Проблемы безопасности Docker, Перевод от Игоря Олемского, Southbridge](https://habr.com/ru/company/southbridge/blog/339126/)
*	[2017-09-15]	[Обеспечение сетевой безопасности в кластере Kubernetes,перевод Ahmet Alp Balkan, Southbridge](https://habr.com/ru/company/southbridge/blog/337088/)
*	[2017-02-17]	[Контейнеры и безопасность: seccomp, Андрей Емельянов, Selectel](https://habr.com/ru/company/selectel/blog/322046/)
		
## Доклады
### Dev
*	[2020-08-26]	[SAST, борьба с потенциальными уязвимостями, Андрей Карпов, PVS-Studio](https://youtu.be/HYTizYEXmvs)
*	[2020-08-26]	[Внедрение SAST: теория vs практика, Ярослав Александров, Ростелеком-Solar](https://youtu.be/gN4SCUD3smE)
*	[2020-07-30]	[DevSecOps. Чего нам не хватает. Сергей Белов, Acronis](https://play.sonatype.com/watch/mDGzwBfMxsjX8iz7VsaFo5)
*	[2020-07-30]	[Мы начинаем DevSecOps, Юрий Шабалин, Swordfish Security](https://play.sonatype.com/watch/mDGzwBfMxsjX8iz7VsaFo5)
*	[2020-06-01]	[DevSec. Встраивание ИБ в конвейер разработки, Александр Садыков,Станислав Косарев,Антон Гаврилов, «Инфосистемы Джет»](https://youtu.be/jlOL1NkdH_U)
*	[2020-05-12]	[DevSecOps. Общее погружение, Антон Гаврилов,Александр Краснов, «Инфосистемы Джет»](https://youtu.be/BrglJmPkvNg)
*	[2019-12-25]	[DevSecOps или как встроить проверки информационной безопасности в микросервисы, Антон Башарин, Swordfish Security](https://youtu.be/0Gn8ONZnfU8)
*	[2019-12-24]	[DevOps-SecOps, Анатолий Карпенко](https://youtu.be/u4HNIa-dWKk)
*	[2019-12-24]	[DevSecOps: tips and tricks, Юрий Шабалин, Swordfish Security](https://youtu.be/l8jiV0DylRU)
*	[2019-08-23]	[AppSec как код, Антон Башарин и Юрий Шабалин, Swordfish Security](https://youtu.be/wfHJyqhTW1o)
*	[2019-07-03]	[SAST и Application Security: как бороться с уязвимостями в коде, Сергей Хренов, PVS-Studio](https://youtu.be/XnHVQBgOBM8)
*	[2019-07-03]	[Как построить безопасность SDLC без SDLC, Иван Афанасьев, BI.Zone](https://youtu.be/Lrcgb9pm6ck)
*	[2018-09-23]	[Страх и ненависть DevSecOps, Юрий Шабалин, Swordfish Security](https://youtu.be/ROH636e7Rx8), [DevOps Moscow meetup](https://www.meetup.com/DevOps-Moscow-in-Russian/), [[слайды]](https://speakerdeck.com/devopsmoscow/strakh-i-nienavist-devsecops)
*	[2018-09-23]	[Security Compliance & DevOps, Степан Носов, IPONWEB](https://youtu.be/BtFeWnR1xXE), [DevOps Moscow meetup](https://www.meetup.com/DevOps-Moscow-in-Russian/), [[слайды]](https://speakerdeck.com/devopsmoscow/security-compliance-and-devops)
*	[2018-02-24]	[Теория и практика формального моделирования уязвимостей, Владимир Кочетков, PT](https://youtu.be/h7SwURZNiWo),[слайды](https://speakerdeck.com/kochetkov/formal-noie-modielirovaniie-uiazvimostiei)
### Ops
*	[2020-12-04]	[Ломаем прил-е в Docker и строим безопасный пайплайн Gitlab, Денис Якимов, Павел Канн, Swordfish Security](https://youtu.be/0_Lb9OVxmbw)
*	[2020-11-30]	[Защита Kubernetes со всех сторон, Даниил Бельтюков, Digital Security](https://youtu.be/W3cdL7Gsey0)
*	[2020-05-27]	[Облачный пентест: Методики тестирования Amazon AWS, Вадим Шелест, Digital Security](https://youtu.be/1LjeBUOd9_Y)
*	[2020-05-27]	[Использование seccomp для защиты облачной инфраструктуры, Антон Жаболенко, Яндекс.Облако](https://youtu.be/n7ZVJarg4s8)
*	[2020-05-26]	[SecOps. Защита кластера. Юрий Семенюков, Анастасия Дитенкова, Виктор Пучков, «Инфосистемы Джет»](https://youtu.be/caaMo9alIgA)
*	[2020-04-22]	[Обеспечение безопасности микросервисной архитектуры в Kubernetes, Олег Маслеников, ЦИАН](https://youtu.be/aKUhXc1t-3o)
*	[2020-01-16]	[У вас есть кластер Kubernetes, но нет майнера на подах? Тогда мы идем к вам! Антон Булавин, Semrush](https://youtu.be/kth2QVI2PmI)
*	[2019-12-10]	[Заделываем дыры в кластере Kubernetes, Павел Селиванов, Southbridge](https://www.youtube.com/watch?v=Ik7VqbgpRiQ)
*	[2019-05-17]	[Непрерывный статический анализ, Иван Пономарев](https://www.youtube.com/watch?v=SvN7ZwWw7pM&feature=youtu.be)
*	[2019-02-27]	[Безопасность в Kubernetes, Дмитрий Лазаренко, Mail.Ru Cloud Solutions](https://youtu.be/62XWgBIYnJ8)
*	[2019-02-08]	[Управление секретами при помощи Hashicorp Vault в Авито, Сергей Носков, Авито](https://youtu.be/oDdDPU6moTs)
*	[2018-10-30]	[Мониторинг безопасности сайтов, Григорий Земсков, Ревизиум](https://youtu.be/NbN_uOxRHOo)
*	[2018-10-05]	[Безопасность в Kubernetes. Проект Kaniko. Лаборатория ПИТ](https://youtu.be/14ZI3fcc59Q)
*	[2018-07-23]	[Статический анализ: ищем ошибки... и уязвимости? Сергей Васильев, PVS-Studio](https://www.youtube.com/watch?v=ORygHFn2uJk)
*	[2017-04-22]	[Хайлоад и безопасность в мире DevOps: совместимы ли? Юрий Колесов, security-gu.ru](https://youtu.be/JAQDnTDdugo)
*	[2016-07-04]	[Проникновение в Docker с примерами, Дмитрий Столяров, Flant](https://youtu.be/hdVNKmru3LM)

## Подкасты
* [SecOps - второе пришествие, Денис Якимов, Swordfish Security](https://soundcloud.com/qaguild/s03e14)
* [Про DevSecOps, Барух Садогурский, JFrog](https://soundcloud.com/qaguild/s3e07)
* [Мобильный SSDLC, Юрий Шабалин, Swordfish Security](https://youtu.be/EGB8mstJlyA)
* [SDCast #96, Юрий Шабалин, Swordfish Security](https://sdcast.ksdaemon.ru/2019/01/sdcast-96/)

## Стандарты и нормативные документы
### Модели зрелости
* [BSIMM](https://www.bsimm.com/)
* [OWASP SAMM](https://owaspsamm.org/model/)
### Стандарты
* ["ГОСТ 58412 Разработка безопасного ПО. Угрозы безопасности информации при разработке ПО"](https://t.me/sec_devops_chat/460)
* ["ГОСТ 56939 Разработка безопасного ПО. Общие требования."](https://t.me/sec_devops_chat/460)
* [Проект стандарта "Руководство по реализации мер по разработке безопасного программного обеспечения"](https://t.me/sec_devops_chat/461)
* [ISO IEC 27034](https://t.me/sec_devops_chat/462)

## Курсы
* ["Основные сведения об обеспечении безопасности с помощью моделирования угроз", Microsoft](https://docs.microsoft.com/ru-ru/learn/paths/tm-threat-modeling-fundamentals/#)

## Инструменты
### Инструменты для моделирования угроз (Threat modeling)
Моделирование угроз в контексте Secure Development Lifecycle представляет из себя процесс анализа архитектуры ПО на предмет наличия в ней потенциальных уязвимостей и небезопасных технологий. Чтобы сократить расходы на добавление дополнительного функционала с точки зрения безопасности, решением может являться внедрение процесса проверок ИБ еще на этапе проектирования архитектуры. На этом же этапе формируются требования со стороны специалистов по безопасности приложений, которые в дальнейшем пойдут в backlog. 
#### Бесплатные / Open-source
* [OWASP Threat Dragon](https://owasp.org/www-project-threat-dragon/)
* [Pytm](https://github.com/izar/pytm)
* [Materialize threats tool](https://github.com/secmerc/materialize_threats)
* [Threatspec](https://github.com/threatspec/threatspec)
* [Raindance](https://github.com/devsecops/raindance)
* [Microsoft Threat Modeling Tool](https://docs.microsoft.com/en-gb/azure/security/develop/threat-modeling-tool)
* [Theagile](https://github.com/Threagile/threagile)
#### Коммерческие / Enterprise 
* [Irius Risks](https://iriusrisk.com/)
* [ThreatModeler](https://threatmodeler.com/)
#### Другие подборки
* [Awesome threat modeling](https://github.com/hysnsec/awesome-threat-modelling)

### Статические анализаторы приложений (SAST)
Статический анализатор кода - инструмент, сообщающий об уязвимости приложения, ориентируясь на исходные коды приложения.
#### Бесплатные / Open-source универсальные средства
* [ShiftLeft Scan](https://github.com/ShiftLeftSecurity/sast-scan)
* [Salus](https://github.com/coinbase/salus)
* [LGTM](https://semmle.com/lgtm)
* [Semgrep](https://semgrep.dev/editor%20)
#### Коммерческие / Enterprise 
* [Checkmarx](https://www.checkmarx.com/)
* [FortifySCA](https://www.microfocus.com/en-us/solutions/application-security)
* [PT AI](https://www.ptsecurity.com/ww-en/products/ai/)
* [PVS-Studio](https://www.viva64.com/ru/sast/)
* [RIPS](https://www.ripstech.com/)
* [Solar AppScreener](https://solarappscreener.com/)
* [Veracode Static Analysis](https://www.veracode.com/products/binary-static-analysis-sast)
#### Другие подборки с описанием SAST под конкретный язык
* [OWASP Source Code Analysis Tools](https://owasp.org/www-community/Source_Code_Analysis_Tools)
* [Static Analysis Tools](https://github.com/analysis-tools-dev/static-analysis)

### Динамические анализаторы приложений (DAST)
Динамический анализатор кода - инструмент, сообщающий об уязвимости приложения, ориентируясь на ответы сервера по заданным запросам.
#### Бесплатные / Open-source
* [Arachni](https://github.com/Arachni/arachni)
* [OWASP ZAP](https://github.com/zaproxy/zaproxy)
* [w3af](https://github.com/andresriancho/w3af)
* [nikto](https://github.com/sullo/nikto)
* [nerve](https://github.com/PaytmLabs/nerve)
#### Коммерческие / Enterprise 
* [PortSwigger Burp Suite](https://portswigger.net/burp)
* [NetSparker](https://www.netsparker.com/)
* [Acunetix](https://www.acunetix.com/)
* [WebInspect](https://www.microfocus.com/en-us/products/webinspect-dynamic-analysis-dast/overview)
* [PT AI](https://www.ptsecurity.com/ww-en/products/ai/)
* [Veracode Dynamic Analysis](https://www.veracode.com/products/dynamic-analysis-dast)
* [Tenable Web App Scanning](https://www.tenable.com/products/tenable-io/web-application-scanning)
#### Другие подборки
* [Awesome DAST](https://github.com/analysis-tools-dev/dynamic-analysis/)

### Поиск секретов
Инструмент для поиска чувствительной информации.
#### Бесплатные / Open-source
* [git-secrets](https://github.com/awslabs/git-secrets)
* [Gitrob](https://github.com/michenriksen/gitrob)
* [Gitleaks](https://github.com/zricethezav/gitleaks)
* [TruffleHog](https://github.com/dxa4481/truffleHog)
* [Talisman](https://github.com/thoughtworks/talisman)
* [Slack Watchman](https://github.com/PaperMtn/slack-watchman)
* [GitLab Watchman](https://github.com/PaperMtn/gitlab-watchman)
#### Коммерческие / Enterprise 
* [GitGuardian](https://www.gitguardian.com/community)

### Анализаторы сторонних компонентов (SCA) 
Анализатор сторонних компонентов - инструмент, который осуществляет поиск уязвимостей в сторонних open-source компонентах, подключенных к проекту. 
#### Бесплатные / Open-source
* [Dependency Check](https://github.com/jeremylong/DependencyCheck)
* [Dependency Track](https://dependencytrack.org/)
* [Nexus Vulnerability Scanner](https://www.sonatype.com/appscan)
* [ClearlyDefined](https://clearlydefined.io/?sortDesc=true&sort=releaseDate)
* [Renovate](https://renovate.whitesourcesoftware.com/)
* [Dependabot](https://dependabot.com/)
#### Коммерческие / Enterprise 
* [Sonatype Nexus IQ](https://www.sonatype.com/nexus/iqserver)
* [Veracode SCA](https://www.veracode.com/products/software-composition-analysis)
* [Snyk Open Source](https://snyk.io/product/open-source-security-management/)
* [WhiteSource for Developers](https://www.whitesourcesoftware.com/whitesource-for-developers/)
* [JFrog XRay](https://jfrog.com/xray/)
#### Другие подборки
* [OWASP Composition Analysis](https://owasp.org/www-community/Component_Analysis)

### Тестирование по принципам Behaviour Driven Development
Фреймворк, позволяющий описывать проверки по методологии BDD.
#### Бесплатные / Open-source
* [BDD-Security](https://github.com/iriusrisk/bdd-security)
* [Gauntlt](https://github.com/gauntlt/gauntlt)

### Сканеры Docker образов
Инструменты, направленные на поиск уязвимостей в образах контейнеров.
#### Бесплатные / Open-source
* [Clair](https://github.com/quay/clair)
* [Trivy](https://github.com/aquasecurity/trivy)
* [Anchore](https://github.com/anchore/anchore-cli)
* [AquaMicroscanner](https://github.com/aquasecurity/microscanner)
* [Dagda](https://github.com/eliasgranderubio/dagda/)
* [whalescan](https://github.com/nccgroup/whalescan)
* [grype](https://github.com/anchore/grype)
* [syft](https://github.com/anchore/syft)
#### Коммерческие / Enterprise 
* [Snyk Container](https://snyk.io/product/container-vulnerability-management/)
* [TrendMicro SmartCheck](https://www.trendmicro.com/en_us/business/products/hybrid-cloud/smart-check-image-scanning.html)
* [WhiteSource for containers](https://www.whitesourcesoftware.com/whitesource-for-containers/)
#### Другие подборки
* [29 Docker security tools compared](https://sysdig.com/blog/20-docker-security-tools/)
* [Awesome Container Security](https://github.com/kai5263499/awesome-container-security)
* [Awesome Docker Security](https://github.com/myugan/awesome-docker-security)

### Проверка Docker / Kubernetes на соответствие
Инструмент для проверки хоста/dockerd/сборки на соответствии (CIS/PCI DSS и другие).
#### Бесплатные / Open-source
* [Docker bench](https://github.com/docker/docker-bench-security)
* [Dockle](https://github.com/goodwithtech/dockle)
* [Kubebench](https://github.com/aquasecurity/kube-bench)
* [Kubernetes Auto Analyzer](https://github.com/nccgroup/kube-auto-analyzer)

### Безопасность Kubernetes
Инструмент для проверки безопасности Kubernetes.
#### Бесплатные / Open-source
* [Kubehunter](https://github.com/aquasecurity/kube-hunter)
* [KubiScan](https://github.com/cyberark/KubiScan)
* [Krane](https://github.com/appvia/krane)
* [Statboard](https://github.com/aquasecurity/starboard)
* [Kubeaudit](https://github.com/Shopify/kubeaudit)
* [Kubesec](https://github.com/controlplaneio/kubesec)
* [audit2rbac](https://github.com/liggitt/audit2rbac)
* [kubei](https://github.com/Portshift/Kubei)
#### Другие подборки
* [Awesome Kubernetes Security](https://github.com/ksoclabs/awesome-kubernetes-security)
* [Awesome k8s Security](https://github.com/magnologan/awesome-k8s-security)

### Container Runtime
Инструмент для отслеживания поведения контейнеров в Runtime.
#### Бесплатные / Open-source
* [Sysdig Falco](https://github.com/falcosecurity/falco)
* [Deepfence Runtime Threat Mapper](https://github.com/deepfence/ThreatMapper)

### Коммерческие комплексные решения Cloud Native Security Platform
* [Aqua CSP](https://www.aquasec.com/aqua-cloud-native-security-platform/)
* [Aqua CSPM](https://www.aquasec.com/products/cspm/)
* [Prisma Cloud Compute](https://www.paloaltonetworks.com/prisma/cloud)
* [NeuVector](https://neuvector.com/)
* [Sysdig](https://sysdig.com/secure-devops-platform/)
* [Tenable.io Container Security](https://www.tenable.com/products/tenable-io/container-security)
* [McAfee Container Security](https://www.mcafee.com/enterprise/en-us/products/mvision-cloud/container-security.html)
* [TrendMicro CloudOne](https://www.trendmicro.com/en_us/business/products/hybrid-cloud/cloud-one-container-image-security.html)
* [Qualys Container Security](https://www.qualys.com/apps/container-security/)

### Runtime Security 
Инструмент для проверки веб-приложений в режиме runtime
#### Бесплатные / Open-source
* [RASP](https://github.com/baidu/openrasp)
#### Коммерческие / Enterprise 
* [Sqreen](https://www.sqreen.com/platform?utm_medium=social&utm_source=blog&utm_campaign=header&utm_term=Product)

### IAST
Инструмент, совмещающий практики SAST и DAST.
#### Бесплатные / Open-source
* [Contrast](https://www.contrastsecurity.com/contrast-community-edition)
#### Коммерческие / Enterprise 
* [Checkmarx IAST](https://www.checkmarx.com/products/interactive-application-security-testing)
* [Veracode IAST](https://www.veracode.com/products/interactive-analysis-iast)
* [Synopsys IAST](https://www.synopsys.com/software-integrity/security-testing/interactive-application-security-testing.html)

### Fuzzing
Практика тестирования приложения, при которой на вход программе подаются данные, которые могут привести к неопределенному поведению.
#### Другие подборки
* [Awesome Fuzzing](https://github.com/cpuu/awesome-fuzzing#readme)
* [Fuzzing Paper Collection](https://github.com/0xricksanchez/paper_collection)
* [Fuzzing Papper](https://github.com/wcventure/FuzzingPaper)

### Vulnerability Management
Инструмент, собирающий и агрегирующий результаты проверки сторонних инструментов.
#### Бесплатные / Open-source
* [DefectDojo](https://github.com/DefectDojo/django-DefectDojo)
* [Secure code Box](https://github.com/secureCodeBox/secureCodeBox)
* [Archery](https://archerysec.github.io/archerysec/)
* [Faraday](https://github.com/infobyte/faraday)
* [VulnReport](https://github.com/salesforce/vulnreport)
#### Коммерческие / Enterprise 
* [AppSec.Hub](https://hub.appsec.global/)
* [ThreatFix](https://threadfix.it/)
* [Kenna Security](https://www.kennasecurity.com/)

### Compliance-as-code
Практика представления требований безопасности через декларативное описание в виде кода с целью дальнейшей непрерывной оценки на соответствие.
#### Бесплатные / Open-source
* [Chef InSpec](https://github.com/inspec/inspec)
* [Compliance Masonry](https://github.com/opencontrol/compliance-masonry)

### IAC Security
Практика тестирования декларативного описания инфраструктуры через конфигурационные файлы на соответствие требования безопасности.
* [Cfn Nag](https://github.com/stelligent/cfn_nag)
* [Checkov](https://github.com/bridgecrewio/checkov)
* [Terrascan](https://github.com/cesar-rodriguez/terrascan)
* [Tfsec](https://github.com/liamg/tfsec)
#### Kubernetes YAML validating
* [Kubeval](https://github.com/instrumenta/kubeval)
* [Kube-score](https://github.com/zegl/kube-score)
* [Config-lint](https://github.com/stelligent/config-lint)
* [Copper](https://github.com/cloud66-oss/copper)
* [Conftest](https://github.com/open-policy-agent/conftest)
* [Polaris](https://github.com/FairwindsOps/polaris#cli)
#### Сравнение
* [Сравнение инструментов](https://learnk8s.io/validating-kubernetes-yaml)

### Безопасность AWS
Инструменты для проверки безопасности AWS.
#### Бесплатные / Open-source
* [AWS-inventor](https://github.com/nccgroup/aws-inventory)
* [aws_key_triage_tool](https://github.com/cedowens/aws_key_triage_tool)
* [Aws-public-ips](https://github.com/arkadiyt/aws_public_ips)
* [CloudSploit](https://github.com/cloudsploit/scans)
* [AWS Security Benchmark](https://github.com/awslabs/aws-security-benchmark)
* [S3 Scan](https://github.com/bear/s3scan)
#### Другие подборки
* [My-arsenal-of-aws-security-tools](https://github.com/toniblyx/my-arsenal-of-aws-security-tools)
* [Awesome AWS S3 Tools](https://github.com/mxm0z/awesome-sec-s3)
* [Cloud Security Tools by Cloudberry Engineering](https://cloudberry.engineering/tool/)

### Безопасность GCP
Инструменты для проверки безопасности GCP.
#### Бесплатные / Open-source
* [G-Scout](https://github.com/nccgroup/G-Scout)
* [ScoutSuite](https://github.com/nccgroup/ScoutSuite)
* [gcp-audit](https://github.com/spotify/gcp-audit)
* [gcp-iam-collector](https://github.com/marcin-kolda/gcp-iam-collector)
* [gke-auditor](https://github.com/google/gke-auditor)

### Другие общие подборки по DevSecOps инструментам
* [My Arsenal of Cloud Native (Security) Tools by MARCO LANCINI](https://www.marcolancini.it/2018/blog-arsenal-cloud-native-security-tools/)
* [Security along the Container-based SDLC](https://holisticsecurity.io/2020/02/10/security-along-the-container-based-sdlc)
* [DevSecOps / Awesome DevSecOps](https://github.com/devsecops/awesome-devsecops)
* [TaptuIT / Awesome DevSecOps](https://github.com/TaptuIT/awesome-devsecops)
* [Devops-ru / Awesome DevSecOps RU](https://github.com/devops-ru/awesome-devsecops_ru)
