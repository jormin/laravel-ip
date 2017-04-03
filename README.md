# laravel-ip

解析IP地址，使用 [ipip.net](http://www.ipip.net/) 的服务。

## 安装

 1. 安装包文件

	``` bash
	$ composer require jormin/laravel-ip
	```

## 配置

1. 注册 ServiceProvider:
	
	```php
	Jormin\IP\IPServiceProvider::class,
	```

## 使用

1. 代码中使用
    
    ```php
    Jormin\IP\IP:ip2addr('your ip');
    ```

## License

The MIT License (MIT). Please see [License File](LICENSE.md) for more information.
