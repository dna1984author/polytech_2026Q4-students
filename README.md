# Политех · Блок 5 · Студенческий практикум

**Windows x64. Python 3.12 и JupyterLab уже внутри. Установка Python, Conda и интернет для готовых примеров не нужны.**

## Скачать и запустить

1. [Скачайте студенческий ZIP](https://github.com/dna1984author/polytech_2026Q4-students/releases/latest/download/Polytech_Block5_student_windows_x64.zip). Аккаунт GitHub не нужен.
2. Распакуйте **весь ZIP** в локальную папку, например `C:\Polytech`.
3. Дважды щёлкните **RUN_NOTEBOOK.cmd**. На первом запуске дождитесь автоматической подготовки встроенного окружения.
4. В JupyterLab откройте `Teaching_Block5.ipynb` и выберите **Kernel → Restart Kernel and Run All Cells**.

По умолчанию: `CASE = "scooters"`, `MODE = "offline"`, `SENTIMENT_MODE = "frozen"`, `SHOW_INSTRUCTOR = False`.
Для второго корпуса измените только `CASE = "yandex"`, перезапустите ядро и выполните все ячейки.

Не запускайте файлы внутри ZIP. После первого запуска не переносите распакованную папку: для нового места распакуйте исходный ZIP заново.
Нужен файл **Polytech_Block5_student_windows_x64.zip**, а не автоматически создаваемые GitHub архивы «Source code».

## Проверка

Пакет проверен на Windows с использованием встроенного Python: JupyterLab запускается, все ячейки проходят для обоих корпусов с сетевыми вызовами блокнота, заблокированными на время теста.
Самокаты: 2 199 комментариев; Яндекс: 5 000 комментариев.
Проверка на отдельной чистой Windows без установленного Python/Conda и с отключённой сетью пока не выполнена.

[Все файлы выпуска и контрольные суммы](https://github.com/dna1984author/polytech_2026Q4-students/releases/latest).
