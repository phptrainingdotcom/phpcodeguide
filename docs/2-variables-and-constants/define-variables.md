---
layout: post
title: Define Variables
nav_order: 1
parent: Variables and Constants
has_children: false
permalink: /variables-and-constants/define-variables
---

## How to Define Variable

* Dollar (`$`) sign is used in front of the variable name to define a variable.  
* `value` could be any Data Type or Objects.
* `=` is the Assignment Operator to assign the value to Variable.
 
```php
$variable = value;
```

## Example
```php
<?php

    //$name variable is holding String value.
    $name = "John, Smith";
    echo $name . PHP_EOL; 
    
    //$age variable is holding Integer Value.
    $age = 25;
    echo $age . PHP_EOL;

    //You can assign String to Integer just like that.
    //$name now holds integer now.
    $name = $age;
    echo $name . PHP_EOL;
    
```

## Output
```
John, Smith
25
25
```

### Variable Naming Rules

You need to follow these rules while defining Variables:  

* Variable should start with `$`.
* Variable first character should alphabets or _.
* Variable name cannot start with a Integer.
* Long Variable names can be separated with _.
  
```php
<?php
    //Illegal Variable Names
    /*
    $1name = "Illegal Variable Name";
    $First Name = "Cannot Have Space in Variables.";
    $1 = "Illegal Variable Name";
    $first-name = "Only Characters, Numbers and _ is allowed. Illegal Name";
    */
    
    //These are Legal Names
    $name1 = "Legal Variable Name";
    $First_Name = "Use _ for Long names";
    $_1 = "Start with _ and then you can have anything";
    $first_name = "Always use _ to separate variable names";
    
    echo $name1 . " / " . $First_Name . " / " . $_1 . " / " . $first_name . PHP_EOL;
```

## Output
```
Legal Variable Name / Use _ for Long names / Start with _ and then you can have
anything / Always use _ to separate variable names
```
