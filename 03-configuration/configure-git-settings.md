# Конфигурация параметров Git

Кроме глобальных настроек, вы также можете настраивать параметры конкретного репозитория.

## 1. Просмотр локальных настроек репозитория

```bash
git config --local --list
```

## 2. Изменение настроек только для текущего репозитория

```bash
git config --local параметр "значение"
```

Пример:

```bash
git config --local core.ignorecase true
```

<div style="text-align: right;">

  [![Перейти к основному файлу](../img/Back-button.png)](../README.md)

</div>