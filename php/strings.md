# strings 
## single quote
Single quoted string literals returns the string as it is:
```php
$name = "saurav";
echo 'hello $name';
```

## double quote
Double quoted string literals perform operations for special characters:
```php
$name = "saurav";
echo "hello $name";
```

## `strlen()`
```php
echo strlen("saurav");
```

## `str_word_count()`
```php
echo str_word_count("saurav ganguly");
```