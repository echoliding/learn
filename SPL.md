### 1.ArrayIteratoer

```php
$a = array[ 
    'name'=> 'liding', 
    'age' => '26', 
    'city'=> 'beijing' 
];
$b = new ArrayIterator($a); 
$b->append(array[ 
                'home' => 'china', 
                'work' => 'developer' 
           ]); 
$c = $b->getArrayCopy(); 
print_r($b); 
print_r($c);  
```
