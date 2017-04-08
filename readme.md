# Install

1. Install composer
2. Run `composer require snufkin/ConsoleTable`
3. Profit!

# Usage

```php
$table = new \Console\Helper\ConsoleTable();
$table->setHeaders(['Column 1', 'Column 2']);
$table->addRow(['data 1', 'data 2']);
$table->addRow(['data 3', 'data 4']);
$table->addRow(['data 5', 'data 6']);
echo $table->getTable();
```

# Customisations

By default all columns are aligned left. To change the alignment 
use the `0` as the first parameter in the constructor:

```php
$table = new \Console\Helper\ConsoleTable(0);
```
