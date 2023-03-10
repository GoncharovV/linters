# :whale: Qoollo linters configurations :whale:

Монорепозиторий для конфигураций линтеров, используемых в компании Qoollo

:heavy_exclamation_mark: :heavy_exclamation_mark: `Ожидается переименование на @qoollo/...`

### Конфигурации

| **Package**                                                                                        | **Version**                                                                         | **README**                                                                                      | **Downloads**                                                                                                                         |
| -------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------- |
| [@vadiminator/eslint-config](https://npmjs.com/package/@vadiminator/eslint-config)                 | ![](https://img.shields.io/npm/v/%40vadiminator%2Feslint-config/latest.svg)         | [![](https://img.shields.io/badge/README--green.svg)](packages/eslint-config/README.md)         | [![](https://img.shields.io/npm/dw/@vadiminator/eslint-config)](https://npmjs.com/package/@vadiminator/eslint-config)                 |
| [@vadiminator/eslint-config-angular](https://npmjs.com/package/@vadiminator/eslint-config-angular) | ![](https://img.shields.io/npm/v/%40vadiminator%2Feslint-config-angular/latest.svg) | [![](https://img.shields.io/badge/README--green.svg)](packages/eslint-config-angular/README.md) | [![](https://img.shields.io/npm/dw/@vadiminator/eslint-config-angular)](https://npmjs.com/package/@vadiminator/eslint-config-angular) |
| [@vadiminator/stylelint-config](https://npmjs.com/package/@vadiminator/stylelint-config)           | ![](https://img.shields.io/npm/v/%40vadiminator%2Fstylelint-config/latest.svg)      | [![](https://img.shields.io/badge/README--green.svg)](packages/stylelint-config/README.md)      | [![](https://img.shields.io/npm/dw/@vadiminator/stylelint-config)](https://npmjs.com/package/@vadiminator/stylelint-config)           |

### Гайд что проверить при миграции в продакш репозиторий

- [ ] Поменять поле name в каждом package.json на @qoollo
- [ ] Скинуть версии всех пакетов до 1.0.0
- [ ] Заменить все вхождения vadiminator :sunglasses: на qoollo
- [ ] Проверить все ридмишки и убрать из них запись о переименовании
