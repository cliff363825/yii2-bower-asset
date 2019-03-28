# yii2-bower-asset
----
1. 由于国内访问 [Asset Packagist](https://asset-packagist.org) 太慢，故将Yii2所依赖的静态资源进行整合。
2. 使用方法：
    1. `composer require cliff363825/yii2-bower-asset:* -vvv`
    2. 在项目配置文件中，查找 `@bower` 配置：
        ```
        'aliases' => [
            // ...
            '@bower' => '@vendor/bower-asset',
            // ...
        ],
        ```
    3. 将其修改为
        ```
        'aliases' => [
            // ...
            '@bower' => '@vendor/cliff363825/yii2-bower-asset',
            // ...
        ],
        ```
