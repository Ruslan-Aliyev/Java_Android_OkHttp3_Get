# Android-OkHttpGet

Server

```php
<?php
$res = array();
$res["test_one"] =  array('subject' => "test_1", 'info' => "test_info_1");
$res["test_two"] =  array('subject' => "test_2", 'info' => "test_info_2");
header('Content-Type: application/json');
echo json_encode($res[ $_GET["test_name"] ]);
?>
```
