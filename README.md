# Email CSS Inliner

---

Automatically converts CSS in emails to inline styles

---

## Installation

Just place require new package for your laravel installation via composer.json

    "c4studio/email-css-inliner": "1.0.*"

Then simply ```composer update```

### Registering to use it with laravel

Add following lines to ```app/config/app.php```

ServiceProvider array

```php
C4studio\EmailCssInliner\EmailCssInlinerServiceProvider::class,
```