# Clang-format-for-cgTribe

Для того что бы применить clang-format для проекта, скиньте clang-format.clang-format в корневую папку вашего проекта.

Далее скачайте  clang-format-XXX.exe с офф сайта по адресу https://llvm.org/builds/ или возмите версию из этого репозитория.

Далее в MVS зайдите в Tools -> Options -> Text Editor -> C/C++ -> Code Style -> Formatting Выствляем опции как на картинке. ![1-21-2022 11-12-13 AM](https://user-images.githubusercontent.com/60007719/150482808-751d9e7b-79c7-4287-9896-d84d1c2a358f.png)

В Use custom clang-format.exe file указываем путь до clang-format-XXX.exe

Для того что бы применить оформление кода нажимаем Ctrl+K,Ctrl+D либо ПКМ по проекту Analyze and Code Cleanup Run code analyse $(PrjcetName)
