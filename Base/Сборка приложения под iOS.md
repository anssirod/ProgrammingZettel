# Сборка приложения под iOS
1. Открыть Xcode -> нажать в левом верхнем углу по названию -> Preferences
2. В окне настроек открыть вкладку Accounts -> в левом нижнем углу "+" -> Apple ID -> зайти с аккаунта на котором есть аккаунт разработчика **с подвязанным** iOS устройством
3. Нажать на аккаунт - проверить сертификаты
4. Открыть терминал - flutter build ios --release
5. После того как сблизилось успешно - открвыаем iOS/Runner.xcworkspace
6. Заходим в Xcode -> вкладка General - устанавливаем значения Build 
7.  Нажимаем на Runner -> Edit scheme -> проверяем, что build config стоит Release
8.  Справа сверху от Runner смотрим что стоит Any iOS Device
11. Далее Product -> Archive
12. Как сборка архивируется открывается Organizer (если его случайно закрыли - Window -> Organizer)
13. Выбираем нужный архив по номеру сборки -> Validate
14. На 1 шаге валидация оставляем галочки как есть (автоматов выбрана 2 и 3, 1 недоступна) -> Next -> Automatically manage signing -> Validate

---

# Решение возможных проблем

1. Проверь, что работаешь с .xcworkspace, а не с .xcodeproj

2. [Проблема с сертификатами](https://stackoverflow.com/questions/39568005/xcode-8-shows-error-that-provisioning-profile-doesnt-include-signing-certificat)

---
### Связанные заметки:
- 

---
**Источники**: 
- 

`ID:` 202201210942