# Обход блокировки Discord и Youtube на Windows | Android | Ios

## Способ: Использование WARP для обхода блокировки

Этот способ использует туннелирования через WARP для обхода блокировки Discord и YouTube. Перед началом убедитесь, что вы выключили VPN, GoodbyeDPI и любые другие ускоряющие сервисы , так как они могут конфликтовать с данным способом.

### Шаги:

1. **Выключите VPN и GoodbyeDPI:**
   - Перед выполнением последующих шагов убедитесь, что все сторонние сервисы ускорения отключены.
2. **Перейдите в консоль Google:**
   - Откройте [Google Cloud Console](https://console.cloud.google.com/)
   - или Codespace [Codespace](https://github.com/codespaces/)
   - для Codespace в разделе Blank нажмите кнопку Use this template
3. **Выполните команду в консоли:**
   - Вставьте следующую команду в консоль:
     ```bash
     curl -sSL https://raw.githubusercontent.com/ImMALWARE/bash-warp-generator/main/warp_generator.sh | bash
     ```
4. **Получите файл `WARP.conf`:**
   - После выполнения команды в консоли появится ссылка. Перейдите по этой ссылке и скачайте файл `WARP.conf`.
5. **Скачайте и установите программу для туннелирования:**
   - Скачайте программу для туннелирования по [этой ссылке](https://github.com/amnezia-vpn/amneziawg-windows-client/releases/download/1.0.0/amneziawg-amd64-1.0.0.msi/).
   - Для андроид [этой ссылке](https://play.google.com/store/apps/details?id=org.amnezia.awg&hl=en_SG&gl=US&pli=1/)
   - Для ios [этой ссылке](https://apps.apple.com/ru/app/amneziawg/id6478942365/)
6. **Добавьте туннель:**
   - Откройте установленную программу, нажмите «Добавить туннель», и выберите файл `WARP.conf`, который вы скачали ранее.
7. **Подключитесь к туннелю:**
   - Нажмите кнопку «Подключить» в программе и проследите, чтобы трафик начал идти через туннель.
