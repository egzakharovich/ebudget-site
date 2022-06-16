В случае, если у вас не получается активировать Континент TLS-клиент с помощью онлайн-регистрации, например, если в вашей организации ограничен доступ в интернет или возникают ошибки в процессе регистрации, есть способ принудительно активировать программу.

Процесс активации:

1. Найти в архиве эталонной конфигурации, рядом с файлом конфигурации, файл

    - `PublicConfig.json` - Для 2.0.1440.0
    - `RegistrationConfig.json` - Для 2.0.1482.0

2. Закройте программу Континент TLS-клиент, осуществив Выход из неё.

    **2.0.1444.0**:

   ![Скриншот Континент TLS-клиент 2.0.1440.0 Выход](../../assets/common-images/Continent_TlsClient/2.0.1440.0/Continent_TlsClient-2.0.1440.0-Exit.png)

    **2.0.1482.0**:

   ![Скриншот Континент TLS-клиент 2.0.1482.0 Выход](../../assets/common-images/Continent_TlsClient/2.0.1482.0/Continent_TlsClient-2.0.1482.0-Exit.png)

3. Скопируйте с принудительной заменой полученный файл `PublicConfig.json` или `RegistrationConfig.json` в директорию `C:\Users\Public\ContinentTLSClient\` на вашем компьютере.

    Чтобы быстро открыть директорию, нажмите <kbd>Win</kbd>+<kbd>R</kbd> и вставьте `%PUBLIC%\ContinentTlsClient\` в поле Выполнить, нажмите <kbd>Enter</kbd>.

4. Запустите Континент TLS-клиент. Он больше не станет требовать регистрации.


<!--
Для расширения Modelines
https://marketplace.visualstudio.com/items?itemName=chrislajoie.vscode-modelines

// code: language=markdown insertSpaces=true tabSize=4
-->