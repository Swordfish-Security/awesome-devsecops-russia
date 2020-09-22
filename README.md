# Awesome DevSecOps на русском языке [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
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
#### Бесплатные / Open-source
* [ShiftLeft Scan](https://github.com/ShiftLeftSecurity/sast-scan)
* [Salus](https://github.com/coinbase/salus)
* [LGTM](https://semmle.com/lgtm)
* [Semgrep](https://semgrep.dev/editor%20)
#### Коммерческие / Enterprise 
* [Checkmarx](https://www.checkmarx.com/)
* [FortifySCA](https://www.microfocus.com/en-us/solutions/application-security)
* [RIPS](https://www.ripstech.com/)
* [Solar AppScreener](https://solarappscreener.com/)
* [PT AI](https://www.ptsecurity.com/ww-en/products/ai/)
* [Veracode Static Analysis](https://www.veracode.com/products/binary-static-analysis-sast)
#### Другие подборки
* [OWASP Source Code Analysis Tools](https://owasp.org/www-community/Source_Code_Analysis_Tools)
* [Static Analysis Tools](https://github.com/analysis-tools-dev/static-analysis)

### Динамические анализаторы приложений (DAST)
Динамический анализатор кода - инструмент, сообщающий об уязвимости приложения, ориентируясь на ответы сервера по заданным запросам.
#### Бесплатные / Open-source
* [Arachni](https://github.com/Arachni/arachni)
* [OWASP ZAP](https://github.com/zaproxy/zaproxy)
* [w3af](https://github.com/andresriancho/w3af)
#### Коммерческие / Enterprise 
* [NetSparker](https://www.netsparker.com/)
* [WebInspect](https://www.microfocus.com/en-us/products/webinspect-dynamic-analysis-dast/overview)
* [PT AI](https://www.ptsecurity.com/ww-en/products/ai/)
* [Veracode Dynamic Analysis](https://www.veracode.com/products/dynamic-analysis-dast)
* [Tenable Web App Scanning](https://www.tenable.com/products/tenable-io/web-application-scanning)
#### Другие подборки
* [Awesome DAST](https://github.com/analysis-tools-dev/dynamic-analysis/)

### Поиск секретов

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
#### Бесплатные / Open-source
* [BDD-Security](https://github.com/iriusrisk/bdd-security)
* [Gauntlt](https://github.com/gauntlt/gauntlt)

### Сканеры Docker образов
#### Бесплатные / Open-source
* [Clair](https://github.com/quay/clair)
* [Trivy](https://github.com/aquasecurity/trivy)
* [Anchore](https://github.com/anchore/anchore-cli)
* [AquaMicroscanner](https://github.com/aquasecurity/microscanner)
* [Dagda](https://github.com/eliasgranderubio/dagda/)
#### Коммерческие / Enterprise 
* [Snyk Container](https://snyk.io/product/container-vulnerability-management/)

#### Другие подборки
* [29 Docker security tools compared](https://sysdig.com/blog/20-docker-security-tools/)

### Проверка Docker / Kubernetes на соответствие
#### Бесплатные / Open-source
* [Docker bench](https://github.com/docker/docker-bench-security)
* [Dockle](https://github.com/goodwithtech/dockle)
* [Kubebench](https://github.com/aquasecurity/kube-bench)
* [Kubernetes Auto Analyzer](https://github.com/nccgroup/kube-auto-analyzer)

### Безопасность Kubernetes
#### Бесплатные / Open-source
* [Kubehunter](https://github.com/aquasecurity/kube-hunter)
* [KubiScan](https://github.com/cyberark/KubiScan)
* [Krane](https://github.com/appvia/krane)
* [Statboard](https://github.com/aquasecurity/starboard)
* [Kubeaudit](https://github.com/Shopify/kubeaudit)
* [Kubesec](https://github.com/controlplaneio/kubesec)
* [audit2rbac](https://github.com/liggitt/audit2rbac)

### Container Runtime
#### Бесплатные / Open-source
* [Sysdig Falco](https://github.com/falcosecurity/falco)
* [Deepfence Runtime Threat Mapper](https://github.com/deepfence/ThreatMapper)

### Коммерческие комплексные решения Cloud Native Security Platform
* [Aqua CSP](https://www.aquasec.com/aqua-cloud-native-security-platform/)
* [NeuVector](https://neuvector.com/)
* [Sysdig](https://sysdig.com/secure-devops-platform/)

### Runtime Security 
#### Бесплатные / Open-source
* [RASP](https://github.com/baidu/openrasp)

### IAST
#### Бесплатные / Open-source
* [Contrast](https://www.contrastsecurity.com/contrast-community-edition)

### Fuzzing
#### Другие подборки
* [Awesome Fuzzing](https://github.com/cpuu/awesome-fuzzing#readme)

### Vulnerability Management
#### Бесплатные / Open-source
* [DefectDojo](https://github.com/DefectDojo/django-DefectDojo)
* [Secure code Box](https://github.com/secureCodeBox/secureCodeBox)
* [Archery](https://archerysec.github.io/archerysec/)
* [Faraday](https://github.com/infobyte/faraday)
* [VulnReport](https://github.com/salesforce/vulnreport)

### Безопасность AWS
#### Бесплатные / Open-source
* [Chef InSpec](https://github.com/inspec/inspec)
* [Compliance Masonry](https://github.com/opencontrol/compliance-masonry)
### Коммерческие комплексные решения Cloud Native Security Platform
* [Aqua CSPM](https://www.aquasec.com/products/cspm/)
#### Другие подборки
* [My-arsenal-of-aws-security-tools](https://github.com/toniblyx/my-arsenal-of-aws-security-tools)

### Compliance-as-code

### Другие общие подборки по DevSecOps инструментам
* [My Arsenal of Cloud Native (Security) Tools by MARCO LANCINI](https://www.marcolancini.it/2018/blog-arsenal-cloud-native-security-tools/)
* [Security along the Container-based SDLC](https://holisticsecurity.io/2020/02/10/security-along-the-container-based-sdlc)
* [DevSecOps / Awesome DevSecOps](https://github.com/devsecops/awesome-devsecops)
* [TaptuIT / Awesome DevSecOps](https://github.com/TaptuIT/awesome-devsecops)
* [Devops-ru / Awesome DevSecOps RU](https://github.com/devops-ru/awesome-devsecops_ru)

## Статьи
### Dev
* [От Threat Modeling до безопасности AWS - 50+ open-source инструментов для выстраивания безопасности DevOps, Денис Якимов, Swordfish Security](https://habr.com/ru/company/swordfish_security/blog/518758/)
* [DevSecOps: принципы работы и сравнение SCA. Часть первая, Денис Якимов, Swordfish Security](https://habr.com/ru/company/swordfish_security/blog/516660/)
* [Практические ответы на нетривиальные вопросы, или Как внедрять DevSecOps в организации со сложным IT-ландшафтом, ВТБ](https://habr.com/ru/company/vtb/blog/479082/)
* [Страх и ненависть DevSecOps, доклад Юрия Шабалин, перевод в текст Александра Титова](https://habr.com/ru/company/oleg-bunin/blog/448488/)
* [DevOps vs DevSecOps: как это выглядело в одном банке, Техносерв](https://habr.com/ru/company/technoserv/blog/503720/)
* [Строим безопасную разработку в ритейлере. Опыт одного большого проекта, Иван Старосельский, Solar Security](https://habr.com/ru/company/solarsecurity/blog/519428/)
### Ops
* [Проблемы безопасности Docker, Перевод от Игоря Олемского, Southbridge](https://habr.com/ru/company/southbridge/blog/339126/)
* [Безопасность Docker, Павел Канн, Swordfish Security](https://swordfishsecurity.ru/blog/docker_security)
* [Обзор утилит безопасности Docker, Павел Канн, Swordfish Security](https://swordfishsecurity.ru/blog/obzor-utilit-bezopasnosti-docker)
* [Способы и примеры внедрения утилит для проверки безопасности Docker, Павел Канн, Swordfish Security](https://swordfishsecurity.ru/docker-security-scanning-examples)
* [Контейнеры и безопасность: seccomp, Андрей Емельянов, Selectel](https://habr.com/ru/users/AndreiYemelianov/)
* [9 лучших практик по обеспечению безопасности в Kubernetes, Андрей Сидоров, Flant](https://habr.com/ru/company/flant/blog/436300/)
* [Шпаргалки по безопасности: Docker Acribia](https://habr.com/ru/company/acribia/blog/448704/)
* [Контейнеры для приложений: риски безопасности и ключевые решения по защите, Денис Якимов, КРОК](https://www.anti-malware.ru/Market_Analysis/Application-containers-security-risks-and-key-security-solutions)

## Доклады
### Dev
* [Страх и ненависть DevSecOps, Юрий Шабалин, Swordfish Security](https://youtu.be/ROH636e7Rx8), [DevOps Moscow meetup](https://www.meetup.com/DevOps-Moscow-in-Russian/), [слайды](https://speakerdeck.com/devopsmoscow/strakh-i-nienavist-devsecops)
* [Security Compliance & DevOps, Степан Носов, IPONWEB](https://youtu.be/BtFeWnR1xXE), [DevOps Moscow meetup](https://www.meetup.com/DevOps-Moscow-in-Russian/), [слайды](https://speakerdeck.com/devopsmoscow/security-compliance-and-devops)
* [AppSec как код, Антон Башарин и Юрий Шабалин, Swordfish Security](https://youtu.be/wfHJyqhTW1o)
* [DevSecOps или как встроить проверки информационной безопасности в микросервисы, Антон Башарин, Swrodfish Security](https://youtu.be/0Gn8ONZnfU8)
* [DevSec. Встраивание ИБ в конвейер разработки,Александр Садыков,Станислав Косарев,Антон Гаврилов, «Инфосистемы Джет»](https://youtu.be/jlOL1NkdH_U)
* [DevSecOps. Общее погружение, Антон Гаврилов,Александр Краснов, «Инфосистемы Джет»](https://youtu.be/BrglJmPkvNg)
### Ops
* [Заделываем дыры в кластере Kubernetes",Павел Селиванов,Southbridge](https://www.youtube.com/watch?v=Ik7VqbgpRiQ)
* ["Обеспечение безопасности микросервисной архитектуры в Kubernetes", Олег Маслеников, ЦИАН](https://youtu.be/aKUhXc1t-3o)
* [Безопасность в Kubernetes. Проект Kaniko. Лаборатория ПИТ](https://youtu.be/14ZI3fcc59Q)
* [Управление секретами при помощи Hashicorp Vault в Авито, Сергей Носков, Авито](https://youtu.be/oDdDPU6moTs)
* [“Проникновение в Docker с примерами”, Дмитрий Столяров, Flant](https://youtu.be/hdVNKmru3LM)
* ["Безопасность в Kubernetes",Дмитрий Лазаренко, Mail.Ru Cloud Solutions](https://youtu.be/62XWgBIYnJ8)
* [Хайлоад и безопасность в мире DevOps: совместимы ли?, Юрий Колесов, security-gu.ru](https://youtu.be/JAQDnTDdugo)
* ["У вас есть кластер Kubernetes, но нет майнера на подах? Тогда мы идем к вам!", Антон Булавин, Semrush](https://youtu.be/kth2QVI2PmI)
* [SecOps. Защита кластера. Юрий Семенюков, Анастасия Дитенкова, Виктор Пучков, «Инфосистемы Джет»](https://youtu.be/caaMo9alIgA)

## Курсы

