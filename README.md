# Live Speech Translator: плагин для OBS Studio

Плагин переводит вашу русскую речь на английский прямо во время стрима или записи. Вы говорите в микрофон, и каждое предложение после паузы появляется на экране английскими субтитрами. Можно показывать оригинал и перевод вместе.

- **Работает локально.** Нейросеть Whisper работает на вашем компьютере, без интернета, подписок и ключей API.
- **Быстро.** На видеокарте (NVIDIA, AMD, Intel через Vulkan) фраза переводится за доли секунды. Без видеокарты плагин работает на процессоре, но медленнее.
- **Красивые субтитры.** Источник «Live Subtitles (animated)» выводит слова по одному с плавной анимацией, в рамке с настраиваемыми шрифтом, цветами и иконками.
- **Цензура мата** включается одной галочкой.
- Скрытые субтитры (CC) для Twitch и YouTube, вывод в обычный текстовый источник и в файл.

## Скачать

**[Последняя версия →](../../releases/latest)**: файл `LiveSpeechTranslator-full.zip`, в который уже входят модели.

## Установка

1. Закройте OBS.
2. Откройте папку OBS. Обычно это `C:\Program Files\obs-studio`, в ней лежат папки `bin`, `data` и `obs-plugins`.
3. Распакуйте архив в эту папку и согласитесь на объединение папок.
4. Запустите OBS. У микрофона откройте **Фильтры** → **+** → **Live Speech Translator** и выберите язык, на котором говорите.
5. Добавьте в сцену источник **Live Subtitles (animated)**.

**Требования:** Windows 10/11 64-bit и OBS Studio 30 или новее. Для быстрой работы нужна видеокарта со свежими драйверами.

## Лицензия

GPL-2.0. В плагине используются whisper.cpp и Silero VAD (MIT) и модели Whisper от OpenAI (MIT). Исходный код можно получить по запросу.

---

# Live Speech Translator for OBS Studio (English)

Translates your speech into English subtitles in real time, fully offline, using Whisper on your GPU (Vulkan). Download the zip from [Releases](../../releases/latest), close OBS, and extract it into the OBS folder. Then add the **Live Speech Translator** filter to your microphone and the **Live Subtitles (animated)** source to your scene.
