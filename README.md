GeTui-PHP-Demo
================

是根据个推的PHP官方Demo整理的，个推提供的Demo简直反人类。


尽量简化操作

需要设置的项有：

>APPKEY，APPID，MASTERSECRET

基于个推提供的Demo，require个推的文件。

使用简化，比如需要给一个用户发送透传：

```php
$getui =new push();

//需要推送用户的ID
$clientid = "1234567890";

$getui -> pushMessageToSingle($getui ->TransmissionTemplate(['transmissionType'=> 1,'transmissionContent'=>'Test']),$clientid);
```
