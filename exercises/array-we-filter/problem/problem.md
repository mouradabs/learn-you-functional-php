Write a program that prints the text "Hello someone" to the console with a callable function where someone is the name given as the first argument.

----------------------------------------------------------------------
## HINTS

You can get the arguments using the $argv array.

Note that the first argument is always the name of the executed script.

A callable function in PHP with arguments can be used as that :

```php
$argument = "Foo";

$var = function() use ($argument){
   echo "Argument is ".$argument;
};

$var();
```

Documentation on the `SplFileObject` class can be found by pointing your browser here:
  [http://php.net/manual/en/class.splfileobject.php]()

----------------------------------------------------------------------