# warning : french localization only for personnal use

#### A Nova field to replace BelongsTo field for on the go resource creation.

Form Field 
![Screenshot Field](https://github.com/yelles/nova-create-or-add/raw/master/nova-create-or-add-form.png)
Form Expanded
![Screenshot Form Open](https://github.com/yelles/nova-create-or-add/raw/master/nova-create-or-add-form-open.png)

#### Installation

You can install the package in to a Laravel app that uses [Nova](https://nova.laravel.com) via composer:

```bash
composer require yelles/nova-create-or-add
```
#### Usage

```php
// in Resource File
use Yelles\NovaCreateOrAdd\NovaCreateOrAdd;

// ...

NovaCreateOrAdd::make('Manufacturer')
  ->searchable()
  ->prepopulate()
  ->rules('required'),
```

Original Credit to [Abhi0725](https://github.com/shivanshrajpoot/nova-create-or-add)
