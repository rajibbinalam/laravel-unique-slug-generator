# laravel-unique-slug-generator

```sh
composer require rajib/laravel-slug-generator
```
### Generating a unique slug
```php
//SlugGenerator::generate($model, '$title', '$db_field_name');
SlugGenerator::generate(User::class, 'Hello World', 'slug');
```
 
### Separating a slug with '-'. Default Separated with '-'. It's changable. In config/SlugGenerator
```php
'separator' => '-',
```
### Also we can change the number of slugs make from same title. config/SlugGenerator
```php
'max_count' => '100',
```
