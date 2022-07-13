# Применение пути сертификации

В архиве с эталонной конфигурацией в директории `certification-path` вы найдёте копию Gist по [ссылке](https://gist.github.com/egzakharovich/95b9361bdebe937576f04b9ad6791664).

Примените эти reg-файлы от имени администратора. В gist находится пакетный файл `import.bat`, который поможет в случае, если вы в замешательстве. В файле README от Gist есть подробное описание, как эти файлы были изготовлены.

Эти reg-файлы установят в нужные хранилища сертификации необходимые для работы с ГИИС ЭБ сертификаты, так называемый путь сертификации.

В состав входят:

- [Сертификаты ГУЦ (Корневые)](https://e-trust.gosuslugi.ru/#/portal/mainca)
  - [Минкомсвязи России от 2018 г.](https://e-trust.gosuslugi.ru/app/scc/portal/api/v1/portal/ca/download/4BC6DC14D97010C41A26E058AD851F81C842415A)
  - [Минцифры России от 2022 г.](https://e-trust.gosuslugi.ru/app/scc/portal/api/v1/portal/ca/download/2F0CB09BE3550EF17EC4F29C90ABD18BFCAAD63A)
- [Сертификаты УЦ (Промежуточные ЦС) Федерального Казначейства/Казначейства России](https://e-trust.gosuslugi.ru/#/portal/accreditation/accreditedcadetails/1047797019830)
  - [Федеральное казначейство от 2018 г.](https://e-trust.gosuslugi.ru/app/scc/portal/api/v1/portal/ca/download/AB0E24E9A206877AB7DC4625DFCCEB9C18B0CB0D)
  - [Федеральное казначейство от 2020 г.](https://e-trust.gosuslugi.ru/app/scc/portal/api/v1/portal/ca/download/34D46AFD0CB2A6530926BA5F5E6A058365F09969)
  - [Федеральное казначейство от 2021 г.](https://e-trust.gosuslugi.ru/app/scc/portal/api/v1/portal/ca/download/63C41988B32303D6ECF9915699FC34D07D155B01)
  - [Казначейство России от 2022 г.](https://e-trust.gosuslugi.ru/app/scc/portal/api/v1/portal/ca/download/0B48B8D07D142A5B45E9B0E8C52186687D75E58E)
- Сертификаты серверов TLS
  - В соответствии со списком устанавливаемых ресурсов

<!-- // code: language=markdown insertSpaces=true tabSize=2 -->