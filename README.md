# 1

Continuous Integration (CI) - непрерывная интеграция, из-за частого слияния в главную ветку и выполнения частых автоматизированных сборок проекта дает быстро выявить ошибки и среагировать на них.
Continuous Delivery - непрерывная доставка подразумевает доставку изменений маленькими порциями, которые легко изменить или откатить.
Перед деплоем в Production пайплайн останавится и будет ожидать ручного подтвержения.  
При Continuous Deployment - доставка пройдет и на Production в т.ч.

Основополагающим принципом IaaC является идемпотентность - свойство, при котором разовое или многократное повторное применение операции к объекту приведет к тому же результату, что и в первый раз.

# 2

Преимущества Ansible:

* легкий попрог входа, быстрая и легкая установка и настройка
* легче в управлении, по сравнению сдругими системами
* не требует установки агента на узлы-агенты, управляет по SSH
* есть репозиторий с дополнительными модулями
* написан Python, что позволяет при необходимости разработать собственный модуль
* работает в режимах Pull и Push

Преимуществом метода Push является отсутствие необходимости установки агента на управляемый сервер, простота автоматизации, при этом недостатком может являться скорость выполнения и проблемы при отсутствии связи.
Преимуществом метода Pull является автоматическое применение конфигураций самими управляемыми серверами, простота управления большим количеством серверов, т.к. большая часть работы выполняется самим агентом.
Минусы - требуется установка агента.

# 3

![VirtualBox](https://github.com/alllexk/DEVSYS23-IAAC_Principles-Kozlovsky-Alexander/blob/562ea1630f1d60502328e3a62cdf072eb6c619c9/images/VirtualBox.png)