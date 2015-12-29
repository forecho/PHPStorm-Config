# PHPStorm-Config

我的 PHPStorm 配置信息

由于本人以前是 Sublime 的重度用户，现在也是……，只不过写代码基本上用 PHPStorm 了，但是还是会用 Sublime 阅读代码。

所以快捷键也好，代码片段也好，基本上都保留了 Sublime 的习惯。

本来是以为能找到轮子，但是结果没搜索到，所以自己动手。


## keymaps

快捷键主要修改了两个：

- Ctrl + d ：多选，重复选中一样的词
- Ctrl + Shift + d ：复制上一行粘贴

这两个快捷键是使用率非常频繁的，一旦习惯，根本停不下来。


## templates

代码片段


**HTML**

if

```html
<?php if ($ITERABLE$): ?>
                        
<?php endif ?>
```

ife

```html
<?php if ($ITERABLE$): ?>
                        
<?php else: ?>
    
<?php endif ?>
```

fore

```html
<?php foreach ($ITERABLE$ as $key => $value): ?>
                        
<?php endforeach ?>
```

php

```html
<?php $ITERABLE$ ?>
```

phpe

```html
<?php echo $ITERABLE$ ?>
```

<?

```html
<? $ITERABLE$ ?>
```

<?=

```html
<? $ITERABLE$ ?>
```


**PHP**

sw

```
switch ($ITERABLE$) {
    case 'value':
        # code...
        break;
    
    default:
        # code...
        break;
}
```

try

```
try {
                        
} catch (Exception $e) {
    
} 
```

prd

```
print_r("$END$");die;
```

if?

```
$retVal = ($ITERABLE$) ? $A$ : $B$ ;
```


ife

```
if ($ITERABLE$) {
    // code...
} else {
    // code...
}
```

fun

```
public function $NAME$($PARAMETERS$){
    $END$
}
```

## 文件夹说明

Windows 文件夹代表是 Windows 版的 PHPStorm ，此版本是 10。
把 Windows 文件夹里面的文件夹放在 `C:\Users\Administrator\.WebIde100\config` 目录下。