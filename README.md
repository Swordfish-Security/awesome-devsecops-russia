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

#### Другие подборки
* [Awesome threat modeling](https://github.com/hysnsec/awesome-threat-modelling)
### Статические анализаторы приложений (SAST)
Статический анализатор кода - инструмент, сообщающий об уязвимости приложения, ориентируясь на исходные коды приложения.
#### Бесплатные / Open-source
* [ShiftLeft Scan](https://github.com/ShiftLeftSecurity/sast-scan)
* [Salus](https://github.com/coinbase/salus)
* [LGTM](https://semmle.com/lgtm)
* [Semgrep](https://semgrep.dev/editor%20)
#### Другие подборки
* [OWASP Source Code Analysis Tools](https://owasp.org/www-community/Source_Code_Analysis_Tools)
* [Static Analysis Tools](https://github.com/analysis-tools-dev/static-analysis)
### Динамические анализаторы приложений (DAST)
Динамический анализатор кода - инструмент, сообщающий об уязвимости приложения, ориентируясь на ответы сервера по заданным запросам.
#### Бесплатные / Open-source
* [Arachni](https://github.com/Arachni/arachni)
* [OWASP ZAP](https://github.com/zaproxy/zaproxy)
* [w3af](https://github.com/andresriancho/w3af)
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
#### Другие подборки
* [OWASP Composition Analysis](https://owasp.org/www-community/Component_Analysis)
### Сканеры Docker образов
#### Бесплатные / Open-source
* [Clair](https://github.com/quay/clair)
* [Trivy](https://github.com/aquasecurity/trivy)
* [Anchore](https://github.com/anchore/anchore-cli)
* [AquaMicroscanner](https://github.com/aquasecurity/microscanner)
* [Dagda](https://github.com/eliasgranderubio/dagda/)
### Проверка Docker / Kubernetes на соответствие
* [Docker bench](https://github.com/docker/docker-bench-security)
* [Dockle](https://github.com/goodwithtech/dockle)
* [Kubebench](https://github.com/aquasecurity/kube-bench)
* [Kubernetes Auto Analyzer](https://github.com/nccgroup/kube-auto-analyzer)
### Безопасность Kubernetes
* [Kubehunter](https://github.com/aquasecurity/kube-hunter)
* [KubiScan](https://github.com/cyberark/KubiScan)
* [Krane](https://github.com/appvia/krane)
* [Statboard](https://github.com/aquasecurity/starboard)
* [Kubeaudit](https://github.com/Shopify/kubeaudit)
* [Kubesec](https://github.com/controlplaneio/kubesec)
## Статьи
### Dev
### Ops
  * [Безопасность Docker, Павел Канн, Swordfish Security](https://swordfishsecurity.ru/blog/docker_security)
  * [Обзор утилит безопасности Docker, Павел Канн, Swordfish Security](https://swordfishsecurity.ru/blog/obzor-utilit-bezopasnosti-docker)
  * [Способы и примеры внедрения утилит для проверки безопасности Docker, Павел Канн, Swordfish Security](https://swordfishsecurity.ru/docker-security-scanning-examples)
## Доклады
### Ops
* [“Проникновение в Docker с примерами”, Дмитрий Столяров, Flant](https://youtu.be/hdVNKmru3LM)
* ["Безопасность в Kubernetes",Дмитрий Лазаренко, Mail.Ru Cloud Solutions](https://youtu.be/62XWgBIYnJ8)
## Курсы
