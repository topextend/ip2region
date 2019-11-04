<<<<<<< HEAD
# ip2region
=======
#### 介绍
{**以下是码云平台说明，您可以替换此简介**
码云是 OSCHINA 推出的基于 Git 的代码托管平台（同时支持 SVN）。专为开发者提供稳定、高效、安全的云端软件开发协作平台
### ip2region 使用
```php

$ip2region = new Ip2Region();

$ip = '101.105.35.57';

$info = $ip2region->btreeSearch($ip);

var_export($info, true);

// array (
//     'city_id' => 2163,
//     'region' => '中国|华南|广东省|深圳市|鹏博士',
// )

```
>>>>>>> 第一次提交
