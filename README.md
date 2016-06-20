#  Yii2 Base Project Template
> An Improved Yii 2 Basic Project Template

**Features**
- [Yii framework](http://www.yiiframework.com/) as the PHP MVC framework.
- Security - It sets some headers that projects applications against click-jacking and XSS.
- Assets version - This fixes issue with updates to js and css files and cached browser files
- New Relic - Ensures that the proper routes so up in the new relic monitoring dashboard

## Install

Via Composer

``` bash
$ composer require cottacush/yii2-base-template
```


## Virtual Host Setup

*Windows*
[Link 1](http://foundationphp.com/tutorials/apache_vhosts.php)
[Link 2](https://www.kristengrote.com/blog/articles/how-to-set-up-virtual-hosts-using-wamp)

*Mac*
[Link 1](http://coolestguidesontheplanet.com/set-virtual-hosts-apache-mac-osx-10-9-mavericks-osx-10-8-mountain-lion/)
[Link 2](http://coolestguidesontheplanet.com/set-virtual-hosts-apache-mac-osx-10-10-yosemite/)

*Debian Linux*
[Link 1](https://www.digitalocean.com/community/tutorials/how-to-set-up-apache-virtual-hosts-on-ubuntu-14-04-lts)
[Link 2](http://www.unixmen.com/setup-apache-virtual-hosts-on-ubuntu-15-04/)

Sample Virtual Host Config for Apache
```apache
<VirtualHost *:80>
    ServerAdmin admin@example.com
    DocumentRoot "<WebServer Root Dir>/yii2-base-template/web"
    ServerName local.yii2-base-template.com
    <Directory <WebServer Root Dir>/yii2-base-template/web>
       AllowOverride all
       Options -MultiViews
      Require all granted
    </Directory>
</VirtualHost>
```

## Environment Variables
Make a copy of `.env.sample` to `.env` in the env directory.

## Change log

Please see [CHANGELOG](CHANGELOG.md) for more information what has changed recently.

## Security

If you discover any security related issues, please email developers@cottacush.com instead of using the issue tracker.

## Contributors

- Adegoke Obasa <goke@cottacush.com>
- [All Contributors](https://github.com/CottaCush/yii2-base-template/graphs/contributors)

## License

The MIT License (MIT). Please see [License File](LICENSE.md) for more information.