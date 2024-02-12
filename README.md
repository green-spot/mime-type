```shellscript
$ composer require green-spot/mime-type
```

```php
use GreenSpot\Utils\MimeType;

MimeType::get("photo.jpg");
// => image/jpeg

MimeType::get("jpg");
// => image/jpeg

MimeType::toExtension("image/jpeg");
// => jpg
```
