### [Products Array](code.zip)

`{{ page.path | replace:'README.md','' }}code/src/products.php`:

```php
{% include_relative code/src/products.php %}
```

`{{ page.path | replace:'README.md','' }}code/print/products.print.php`:

```php
{% include_relative code/print/products.print.php %}
```

> [Response](response/src/products.php)

> Tips:<br>
> Use `array_reduce`
