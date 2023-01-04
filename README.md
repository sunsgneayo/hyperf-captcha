<div align="center" style="border-radius: 50px">
    <img width="260px"  src="https://cdn.sunsgne.top/logo-i.png" alt="sunsgne">
</div>

**<p align="center">sunsgne/hyperf-captcha</p>**

**<p align="center">🐬 Verification code generator based on hyperf high-performance coroutine framework 🐬</p>**

<div align="center">

[![Latest Stable Version](http://poser.pugx.org/sunsgne/hyperf-captcha/v)](https://packagist.org/packages/sunsgne/hyperf-captcha)
[![Total Downloads](http://poser.pugx.org/sunsgne/hyperf-captcha/downloads)](https://packagist.org/packages/sunsgne/hyperf-captcha)
[![Latest Unstable Version](http://poser.pugx.org/sunsgne/hyperf-captcha/v/unstable)](https://packagist.org/packages/sunsgne/hyperf-captcha)
[![License](http://poser.pugx.org/sunsgne/hyperf-captcha/license)](https://packagist.org/packages/sunsgne/hyperf-captcha)
[![PHP Version Require](http://poser.pugx.org/sunsgne/hyperf-captcha/require/php)](https://packagist.org/packages/sunsgne/hyperf-captcha)

</div>

# hyperf  captcha 
主要适配[协程框架 **hyperf**](https://github.com/hyperf/hyperf)，主要验证码背景图与图片样式来源于[mewebstudio/captcha](https://github.com/mewebstudio/captcha)，
其中有字符验证，数学公式验证等。可配置验证码样式，大小与文字等。不提供存储机制包括(session，redis，file...)，在开发过程中可自由实现存储机制和验证机制。
灵活多变可适配性强。


## 使用
```bash
composer require sunsgne/hyperf-captcha
```
## 生成config文件

```bash
php bin/hyperf.php vendor:publish sunsgne/hyperf-captcha
```

## Preview
![Preview](https://image.ibb.co/kZxMLm/image.png)



## 说明
- 非常感谢[mewebstudio/captcha](https://github.com/mewebstudio/captcha)作者的开源
