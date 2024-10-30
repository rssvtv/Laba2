### Лабораторная работа №2. Основы верстки
## Выполнила: Лепехина А.Д. ИСП-211о

## 1. Функции приложения
Приложение состоит из 4 экранов:
"Меню" (MainActivity) и "Экран 2" (MainActivity2).
<p align="center">
    <img src="https://github.com/user-attachments/assets/283776f8-1bf7-4c32-95f5-e24d84ae0ffe" width="250">
    <img src="https://github.com/user-attachments/assets/f5091be1-1843-478e-91dd-7208ff23a864" width="250">

</p>

"Экран 3" (MainActivity3) и "Экран 4" (MainActivity4).
<p align="center">
    <img src="https://github.com/user-attachments/assets/6843e418-19dd-426d-a1f9-f7c1abbd9c9c" width="250">
    <img src="https://github.com/user-attachments/assets/5a705468-1ddc-407b-82d5-dabfd10e6754" width="250">

</p>

## 2. Меню
Меню состоит из 4х кнопок:
- "1" (при нажатии открывается MainActivity2).
- "2" (при нажатии открывается MainActivity3).
- "3"(при нажатии открывается MainActivity4).
- "Exit" (при нажатии происходит выход из приложения).

## 3. 2-й экран
Второй экран сверстан с использованием `LinearLayout`.
Он состоит из 7 кнопок:
- 3 расположены в верхней части экрана
  `android:layout_gravity="top"`
- 2 расположены по центру
  `android:layout_gravity="center"`
- 3 расположены в нижней части экрана
  `android:layout_gravity="bottom"`

## 4. 3-й экран
Третий экран сверстан с использованием `RelativeLayout`.
Он состоит из 6 кнопок:
- 2 расположены в верхней части экрана и занимают по половине экрана
  `android:layout_toLeftOf = "@+id/view"`
- `android:layout_toRightOf="@+id/view"`
- 3 расположены по центру
  `android:layout_centerInParent="true"`
  `android:layout_toLeftOf="@+id/button15"`
  `android:layout_toRightOf="@+id/button15"`
- 1 расположена в нижней части экрана

## 4-й экран
На четвертом экране расположена 1 кнопка, на которой написано "Нажми на меня". При нажатии на кнопку ее цвет должен изменяться на красный. После чего происходит выход из приложения.
<p align="center">
     <img src="https://github.com/user-attachments/assets/a2e5248a-bbaa-473d-ae3a-d08336283048" width="250">
     <img src="https://github.com/user-attachments/assets/de8e1873-05df-410b-87f7-2c4dba7f00d6" width="250">

</p>

Внутри папки `drawable` был создан файл `my_button` для того, чтобы кнопка приобрела данные функции.

## Инструкция использования
1. Сохраните репозиторий на свой компьютер:
2. Откройте проект в Android Studio.
3. Подключите устройство или запустите эмулятор.
4. Нажмите кнопку **Run** в Android Studio для сборки и запуска приложения.
