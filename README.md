<p align="center"><img width="260px" src="[https://chaz6chez.cn/images/workbunny-logo.png](https://cdn.nine1120.cn/logo-i.png)" alt="sunsgne"></p>
**<p align="center">sunsgne/hyperf-captcha</p>**

**<p align="center">🐬 Verification code generator based on hyperf high-performance coroutine framework 🐬</p>**

<div align="center">

[![Latest Stable Version](http://poser.pugx.org/sunsgne/hyperf-captcha/v)](https://packagist.org/packages/sunsgne/hyperf-captcha)
[![Total Downloads](http://poser.pugx.org/sunsgne/hyperf-captcha/downloads)](https://packagist.org/packages/sunsgne/hyperf-captcha)
[![Latest Unstable Version](http://poser.pugx.org/sunsgne/hyperf-captcha/v/unstable)](https://packagist.org/packages/sunsgne/hyperf-captcha)
[![License](http://poser.pugx.org/sunsgne/hyperf-captcha/license)](https://packagist.org/packages/sunsgne/hyperf-captcha)
[![PHP Version Require](http://poser.pugx.org/sunsgne/hyperf-captcha/require/php)](https://packagist.org/packages/sunsgne/hyperf-captcha)

</div>

# hyperf-captcha 
Hyperf Captcha 是一个专为[**hyperf**](https://github.com/hyperf/hyperf)协程框架设计的灵活可定制验证码组件，用于生成和展示验证码图片。它支持多种验证码类型，包括字符验证码和数学公式验证码。您可以根据需要轻松配置验证码的外观、大小和文字内容。本组件不提供存储机制（如 session、redis、文件等），完全由您自行实现存储和验证机制，使其适应性和灵活性更强。

# 功能特点
- 多种验证码类型：支持字符验证码和数学公式验证码，满足不同的使用场景。

- 灵活配置：提供丰富的配置选项，方便定制验证码的样式、大小和文字内容。

- 高适应性：专为 Hyperf 协程框架打造，可轻松集成到您的项目中。

- 无存储机制：本组件不涉及验证码的存储和验证，完全由您根据实际情况实现，灵活自由。


## 安装
使用 Composer 进行安装：
```bash
composer require sunsgne/hyperf-captcha
```
## 生成config文件
```bash
php bin/hyperf.php vendor:publish sunsgne/hyperf-captcha
```

## 开始
```php
$Captcha = (new \Sunsgne\HyperfCaptcha\Captcha())->create();
var_dump($Captcha);
```
var_dump：
```shell
{
"sensitive": false,
"key": "qcejdej2y",
"img": "data:imageXXXXXXX"
}
```

## Preview
![Preview](https://image.ibb.co/kZxMLm/image.png)

## 贡献与支持
欢迎贡献代码、提交问题和建议，共同改进本验证码组件，使其更加强大和灵活。如果您在使用过程中遇到任何问题或者需要帮助，请随时联系我们或者提交 Issue。

## 许可证
本项目基于 MIT 许可证 发布，可以自由使用、修改和分发。

## 说明
- 非常感谢[mewebstudio/captcha](https://github.com/mewebstudio/captcha)作者的开源
