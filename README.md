# Gerzhan | My Cheapiano2 keymap

Моя персональная раскладка (keymap) для клавиатуры [Cheapino2](https://github.com/gerzhan/cheapino-keyboard)

Клавиатура на 36 клавиш, но раскладка на 34 клавиши с целью последующего перхода на Ferris. 

> Мотивация -> [You Won’t Believe How Effective This Keyboard Layout Is](https://www.youtube.com/watch?v=8wZ8FRwOzhU) 

Для принятия решения по формированию раскладки были проанализаированы следующие источник информации и примеры:

- [My 34-key Keyboard Layout](https://mattstenback.com/journal/my-34-key-keyboard-layout/)
  - https://github.com/mattstenback/qmk_firmware/tree/5fb7c234f4319aeab10434ea349a5a8933b80cfe/keyboards/controllerworks/mini36/keymaps/mattstenback
- [github.com/antonioxdias](https://github.com/antonioxdias/qmk_firmware/blob/master/keyboards/crkbd/keymaps/antonioxdias/keymap.c)
- [github.com/jporter-dev/qmk_firmware/keyboards/ferris](https://github.com/jporter-dev/qmk_firmware/blob/bbd60758a9c88f98c8485087f9dd9ef89edfe3e0/keyboards/ferris/keymaps/via/keymap.c)

## Обоснование выбора Cheapino

- более низкая цена среди раздельных клавиатур
- наиболее удобное расположение кнопок для большого пальца
- возможность пренастройки раскладки без прошики через web интерфейс
- возможность "горячей" замены свичей ("hotswap")
- возможность освоения использвание 34-keys

## Раскладка и слои 

Для отладки и наглядной визуализации использован инструмент [keymap-drawer](https://keymap-drawer.streamlit.app/)

Для ручной настройки без перепрошивки использован web интерфейс [Vial](https://vial.rocks/ )

## Инструкции

### Формирование файла keymap.json 

- взять за основу пример раскладки [qmk_firmware/blob/cheapino/keyboards/cheapino/keymaps/](https://github.com/tompi/qmk_firmware/blob/cheapino/keyboards/cheapino/keymaps/lars/keymap.json)
- 

## TODO (PLANS)

- реализовать собственную прошику (qmk)
  - video [How To Program Your Keyboard With Code Instead Of QMK Configurator](https://www.youtube.com/watch?v=AA8fw2MbpYg)  
- реализовать модификацию версии на основании личного опыта
- использовать раскладку на беспроводной клавиатуре (типа Ferris)
