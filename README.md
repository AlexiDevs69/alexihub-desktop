# AlexiHub Desktop

Готова мінімальна Tauri 2 оболонка для:

https://basedate.onrender.com/community

## Як завантажити в GitHub

1. Розпакуй ZIP.
2. Відкрий свій порожній репозиторій.
3. Натисни **Add file → Upload files**.
4. Перетягни ВСІ файли та папки з розпакованої папки:
   - `.github`
   - `src-tauri`
   - `.gitignore`
   - `package.json`
   - `README.md`
5. Натисни **Commit changes**.

Важливо: завантажуй не сам ZIP, а його розпакований вміст.

## Як зібрати EXE

1. Відкрий вкладку **Actions**.
2. Зліва вибери **Build AlexiHub for Windows**.
3. Натисни **Run workflow → Run workflow**.
4. Дочекайся зеленої галочки.
5. Відкрий завершений запуск.
6. Унизу в **Artifacts** скачай **AlexiHub-Windows-Installer**.
7. Розпакуй скачаний ZIP — усередині буде `AlexiHub_1.0.0_x64-setup.exe`.

## Що вже налаштовано

- Назва: AlexiHub
- Версія: 1.0.0
- URL: https://basedate.onrender.com/community
- Windows x64 NSIS installer
- WebView2 bootstrapper
- Мінімальна безпечна Tauri-конфігурація без доступу сайту до файлів або команд ОС

Перший інсталятор не має цифрового підпису, тому Windows SmartScreen може показати попередження.
