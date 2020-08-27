# Information / Информация

Интеграция тега кода `SRC` в статью.

## Install / Установка

1. Загрузите папки и файлы в директорию `extensions/MW_EXT_Src`.
2. В самый низ файла `LocalSettings.php` добавьте строку:

```php
wfLoadExtension( 'MW_EXT_Src' );
```

## Syntax / Синтаксис

```html
<src type="[TYPE]" lang="[LANGUAGE]">[CONTENT]</src>
```

Где `[TYPE]` это:
- `block` - блочное форматирование кода;
- `inline` - строчное форматирование кода.

## Donations / Пожертвования

- [Donation Form](https://donation-form.github.io/)
