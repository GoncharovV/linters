# @vadiminator/eslint-config
:heavy_exclamation_mark: :heavy_exclamation_mark: ```Ожидается переименование на @qoollo/eslint-config```

Предоставляет базовую конфигурацию ESLint для форматирования JS и TS файлов, используемую в компании Qoollo.
Как правило, используется в связке с `@vadiminator/eslint-config-angular`

## Использование

1) Установить из NPM

```bash
npm i --save-dev @vadiminator/eslint-config
```

2) Создать в корне проекта файл `.eslintrc` с указанным содержимым
```bash
{
  "extends": ["@vadiminator/eslint-config"]
}
```

## Обратите внимание
Данный пакет уже включает в себя `eslint` и набор плагинов для него,
так что эти зависимости следует убрать из `package.json` проекта,
в который подключается данный пакет. 

## Используемые дополнения

`@vadiminator/eslint-config` включает:

- `eslint-plugin-import` - поддержка импортов ES6
- `eslint-plugin-jsdoc` - правила линтинга для JSDOC
- `eslint-plugin-node` - дополнительные правила для NodeJS
- `eslint-plugin-prefer-arrow` - правила для стрелочных функций
- `eslint-plugin-promise` - правила для работы с Promise
- `eslint-plugin-sort-imports-es6-autofix` - автоматическая сортировка импортов
- `eslint-plugin-unicorn` - дополнительные правила линтинга
