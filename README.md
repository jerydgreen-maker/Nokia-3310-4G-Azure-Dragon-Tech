# English version

## What is RetroShell?

**RetroShell is an experimental replacement-board project for the original Nokia 3310 electronics.** The goal is to retain the stock enclosure, keypad, and familiar classic-phone experience while introducing modern hardware capabilities and custom firmware.

The project is part of **Azure Dragon Tech**. In the longer term, the concept may evolve into a modular electronics platform for other devices. The phone version and future specialised applications will be developed as separate use cases.

> **Current status: design / pre-prototype.** The board has not yet been manufactured or subjected to initial hardware testing. The features listed here are development goals, not verified capabilities of a finished device.

## Board concept

- The first target model is the **Nokia 3310**.
- The design aims to fit the original enclosure without permanent case modifications.
- In phone configuration, no external peripheral connectors are planned; the device should remain as close as possible to the stock phone in appearance and everyday use.
- Mechanical fit and compatibility with the display, keypad, power system, and other components must be checked on a prototype.

### Planned features

- **4G LTE:** cellular connectivity using a suitable modem, antenna, and compatible network configuration.
- **Bluetooth headset:** Bluetooth is intended for phone calls through a compatible headset; it is not presented as a universal peripheral interface.
- **Controllable colour backlight:** colour selection and event-based colour changes, such as for incoming calls, SMS messages, game events, and other notifications, subject to hardware implementation.
- **Custom firmware:** independently written code intended to reproduce the original Nokia 3310 interface and behaviour as closely as practical. The project does not rely on modifying Nokia's original firmware code.
- **System sounds:** a custom sound system instead of the original system sounds.
- **Snake and Tamagotchi:** integration of Snake and a virtual-pet game. Tamagotchi is intended to run in the background and update its state while the user uses other phone features.

Each feature will be considered confirmed only after implementation and testing.

## Concept images

### PCB layout

| PCB layout — side A | PCB layout — side B |
|---|---|
| ![PCB layout, side A](images/pcb-layout-front.png) | ![PCB layout, side B](images/pcb-layout-back.png) |

### 3D PCB renders

| Front side | Back side |
|---|---|
| ![3D render of PCB front](images/pcb-render-front.png) | ![3D render of PCB back](images/pcb-render-back.png) |

### Firmware interface concept

The following images illustrate the proposed interface concept. They do not demonstrate firmware running on a physical prototype.

| Home screen | Phonebook |
|---|---|
| ![Home screen concept](images/ui-home-screen.png) | ![Phonebook concept](images/ui-phonebook.png) |

| Incoming call — blue theme | Incoming call — red theme |
|---|---|
| ![Incoming call concept, blue theme](images/ui-incoming-call-blue-theme.png) | ![Incoming call concept, red theme](images/ui-incoming-call-red-theme.png) |

## Transformer concept and future applications

Outside the original phone enclosure, the platform could become the basis for specialised devices. Such applications may require different enclosures, external connectors, additional modules, and separate hardware variants.

Potential areas of exploration include:

- robotics and drone-related electronics;
- wireless diagnostics and research tools;
- GSM/LTE devices, gateways, and experimental communications systems;
- sensors, microcontrollers, and other peripheral hardware.

These are long-term concepts. Interfaces, electrical limits, safety requirements, and applicable regulations must be assessed separately. Cellular operation depends on the modem, antennas, supported bands, carrier requirements, and local regulations.

## Other phone models

Future models are separate projects and are **not intended to be compatible with the Nokia 3310 board**:

- **Nokia 3410:** a separate board and firmware; use of the 3410 enclosure is being considered and requires validation.
- **Nokia 3210, Nokia 3510, and Nokia 3510i:** separate hardware projects with their own boards and software.

Each model requires its own assessment of mechanical geometry, display, keypad, power, and hardware interfaces.

## Roadmap

- [x] Initial concept and preliminary visualisations.
- [ ] Review circuitry and component choices.
- [ ] Manufacture the first prototype.
- [ ] Check fit in the Nokia 3310 enclosure.
- [ ] Test display, keypad, power, and backlight.
- [ ] Develop and test firmware.
- [ ] Validate Bluetooth headset and cellular connectivity.
- [ ] Document test results and limitations.

## Contributions and support

The project is at an early stage. Discussion, constructive suggestions, and help reviewing the architecture are welcome. Manufacturing partnerships and support can be considered once the technical scope has been agreed.

Schematics, native PCB design files, Gerber files, and the bill of materials are not being published at this stage.

## Disclaimer

RetroShell is an independent experimental project by Azure Dragon Tech. It is not affiliated with or endorsed by Nokia. Nokia and phone model names are used to identify target devices and intended compatibility. All features remain planned until verified through testing.


# RetroShell — Nokia 3310 Replacement Board & Transformer Platform
### Проект Azure Dragon Tech · Azure Dragon Tech project

[Русская версия](#русская-версия) | [English version](#english-version)

---

# Русская версия

## Что такое RetroShell?

**RetroShell — экспериментальный проект платы на замену оригинальной электроники Nokia 3310.** Цель — сохранить штатный корпус, кнопки и привычный опыт использования классического телефона, добавив современные аппаратные возможности и собственную прошивку.

Проект является частью инженерной инициативы **Azure Dragon Tech**. В перспективе концепция может развиться в модульную электронную платформу для других устройств, но версия для телефона и будущие специализированные применения будут разрабатываться отдельно.

> **Текущий статус: проектирование / до создания прототипа.** Плата ещё не изготовлена и не прошла первичные испытания. Указанные функции являются целями разработки, а не подтверждёнными возможностями готового устройства.

## Концепция платы

- Целевая модель первой версии — **Nokia 3310**.
- Предполагается установка в оригинальный корпус без необратимых изменений его конструкции.
- В режиме телефона не планируется добавлять внешние разъёмы для периферии: устройство должно выглядеть и использоваться максимально близко к штатному телефону.
- Аппаратная конструкция и совместимость с дисплеем, клавиатурой, питанием и другими компонентами требуют проверки на прототипе.

### Планируемые функции

- **4G LTE:** мобильная связь через подходящий сотовый модем, антенну и совместимую сетевую конфигурацию.
- **Bluetooth-гарнитура:** Bluetooth планируется использовать для телефонных разговоров через совместимую гарнитуру; это не заявляется как универсальный интерфейс периферии.
- **Цветная управляемая подсветка:** выбор цвета и смена цвета при событиях — например, входящем звонке, SMS, игровых событиях и других уведомлениях, если это будет поддержано аппаратной реализацией.
- **Собственная прошивка:** разработка собственного кода с целью максимально точно воспроизвести интерфейс и поведение оригинальной Nokia 3310. Проект не предполагает модификацию оригинального кода Nokia.
- **Системные звуки:** собственная система звуков вместо оригинальных системных звуков.
- **«Змейка» и тамагочи:** планируется интеграция игры «Змейка» и игры с виртуальным питомцем. Тамагочи задумано как фоновая функция, продолжающая обновлять состояние, пока пользователь работает с другими функциями телефона.

Фактическая поддержка каждой функции будет подтверждена только после реализации и испытаний.

## Концептуальные изображения

### Разводка платы

| Вид платы — сторона A | Вид платы — сторона B |
|---|---|
| ![Разводка платы, сторона A](images/pcb-layout-front.png) | ![Разводка платы, сторона B](images/pcb-layout-back.png) |

### 3D-визуализация платы

| Лицевая сторона | Обратная сторона |
|---|---|
| ![3D-визуализация лицевой стороны платы](images/pcb-render-front.png) | ![3D-визуализация обратной стороны платы](images/pcb-render-back.png) |

### Концепция интерфейса прошивки

Следующие изображения показывают концепцию интерфейса. Они не являются доказательством работы прошивки на физическом прототипе.

| Главный экран | Телефонная книга |
|---|---|
| ![Концепция главного экрана](images/ui-home-screen.png) | ![Концепция телефонной книги](images/ui-phonebook.png) |

| Входящий звонок — синяя тема | Входящий звонок — красная тема |
|---|---|
| ![Концепция входящего звонка, синяя тема](images/ui-incoming-call-blue-theme.png) | ![Концепция входящего звонка, красная тема](images/ui-incoming-call-red-theme.png) |

## Концепция трансформера и будущие применения

Вне корпуса телефона платформа может стать основой для специализированных устройств. В таких проектах могут понадобиться другие корпуса, внешние разъёмы, дополнительные модули и отдельные версии аппаратной части.

Возможные направления исследований:

- робототехника и электронные системы для дронов;
- инструменты диагностики и исследования беспроводных технологий;
- GSM/LTE-устройства, шлюзы и экспериментальные системы связи;
- подключение датчиков, микроконтроллеров и другой периферии.

Эти применения относятся к долгосрочной концепции. Необходимо отдельно определить интерфейсы, электрические параметры, безопасность и применимые нормативные требования. В частности, работа в сотовых сетях зависит от модема, антенн, поддерживаемых частот, операторских требований и местного законодательства.

## Другие модели телефонов

Будущие проекты рассматриваются отдельно и **не предполагаются совместимыми с платой Nokia 3310**:

- **Nokia 3410:** отдельная версия платы и отдельная прошивка; рассматривается возможность использования корпуса 3410, что требует проверки.
- **Nokia 3210, Nokia 3510 и Nokia 3510i:** отдельные аппаратные проекты с собственными платами и программным обеспечением.

Каждая модель потребует отдельной оценки геометрии, дисплея, клавиатуры, питания и других аппаратных интерфейсов.

## Дорожная карта

- [x] Подготовка концепции и предварительных визуализаций.
- [ ] Проверка схемотехники и компонентов.
- [ ] Изготовление первого прототипа.
- [ ] Проверка посадки в корпус Nokia 3310.
- [ ] Испытания дисплея, клавиатуры, питания и подсветки.
- [ ] Разработка и тестирование прошивки.
- [ ] Проверка Bluetooth-гарнитуры и мобильной связи.
- [ ] Документирование результатов и ограничений.

## Участие и поддержка

Проект находится на раннем этапе. Обсуждения, конструктивные предложения и помощь в проверке архитектуры приветствуются. Производственное партнёрство и поддержка могут быть рассмотрены после согласования технического объёма работ.

Пока не публикуются схемы, исходный проект PCB, Gerber-файлы или спецификация компонентов.

## Важное замечание

RetroShell — независимый экспериментальный проект Azure Dragon Tech. Проект не связан с Nokia и не одобрен Nokia. Названия Nokia и моделей телефонов используются для обозначения целевых устройств и предполагаемой совместимости. Все характеристики и функции остаются планируемыми до подтверждения испытаниями.

---
