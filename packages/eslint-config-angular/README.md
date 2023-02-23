# :whale: @Qoollo/eslint-config-angular :whale:

Предоставляет базовую конфигурацию ESLint для форматирования JS и TS файлов, используемую в компании Qoollo.
Используется как дополнение к `@vadiminator/eslint-config` для работы с Angular

## :dart: Использование

1) Установить из NPM

```bash
npm i --save-dev @vadiminator/eslint-config-angular
```

3) Создать в корне проекта файл `.eslintrc` с указанным содержимым
```bash
{
  "extends": [
    "@vadiminator/eslint-config",
    "@vadiminator/eslint-config-angular"
  ]
}
```

### :bulb: Ручной запуск

Для запуска можно использовать следующие команды

```json
{
  "lint:ts": "npx eslint src",
  "lint:js": "npx eslint **/*.js",
  "lint:ts:fix": "npx eslint --fix src",
  "lint:js:fix": "npx eslint **/*.js --fix"
}
```
