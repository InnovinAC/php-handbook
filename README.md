# php-handbook
A little PHP Handbook, aimed to quickly remind one of stuff.


# Variable assigning

## By value:
```php
// By default PHP assings variables by value
$a = 1;
$b = $a;

$a = 2;
echo $b; // prints 1
```

## By Reference:
```php
$a = 1;
$b = &$a;

$a = 2;
echo $b; // prints 2
```


# Echo hacks
```php
<?php echo "Hello"; ?>
// is same as

<?php echo "Hello" ?>

// is also same as

<?= "Hello"; ?>

// is also same as

<?= "Hello" ?>

```