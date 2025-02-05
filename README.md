# Стенд МК+ПЛИС

Проектирование стенда МК/ПЛИС, предназначеного для разработки и отладки встраиваемых систем на основе микроконтроллеров (МК) и/или программируемых логических интегральных схем (ПЛИС). Предоставляет единую платформу, оснащенную всеми необходимыми компонентами для учебных целей.

Благодаря возможности смены модулей МК и ПЛИС, стенд будет обеспечивать гибкость в разработке.


  ![](https://github.com/l1sok/MCU_PLD/blob/main/MCU_PLD.png)

На общей платформе расположены следующие компоненты:
*	Разъемы для подключения модулей МК/ПЛИС
*	программатор МК
*	программатор ПЛИС 
* PLD-80 (для возможности взаимодействия МК-ПЛИС)
*	PLT-120 (GPIO)
*	Периферия
    * Переключатели (8 шт)
    *  Светодиоды (8 шт)
    *  RGB светодиоды (2 шт)
    *  Семисегментный индикатор (1 шт)
    *  Дисплей (1 шт)
    *  Кнопки (5 шт)
    *  Фоторезистор (1 шт)

Возможность смены модулей  [МК](https://github.com/l1sok/MCU_PLD/tree/main/%5BMK%5D) и [ПЛИС](https://github.com/l1sok/MCU_PLD/tree/main/%5B%D0%9F%D0%9B%D0%98%D0%A1%5D).

Готовые модули: 
|МК| ПЛИС| 
|:---:|:---:|
|STM32F103CBT6| EMP240T100C5N|
|STM32F103RBT6|
|STM32F103VBT6|
  

![Снимок экрана 2025-02-05 004817](https://github.com/user-attachments/assets/12ac02c2-e26f-482d-b85b-af64f856cf69)

![image](https://github.com/user-attachments/assets/205254a8-f388-46a9-8227-dbaa42e48319)

На данный момент осталось доработать схему формирования питания, блоки программирования.
