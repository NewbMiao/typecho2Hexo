# typecho2Hexo

Typecho 文章批量转 Hexo Markdown 文档。

## Usage

1.修改数据库配置，表前缀

```php
// 根据实际情况更改
$db->connect('localhost','username','password','database');
$prefix = 'tc_';
```

2.运行

```bash
php converter.php
```
