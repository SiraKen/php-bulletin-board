# Note

## PHPでのIPアドレスの扱い

IPアドレス取得

```php
$_SERVER["REMOTE_ADDR"] ;
```

DB格納には `ip2long` と `long2ip` を使う

```php
<?php
// ipを数値に変換
echo ip2long( "220.210.136.208" ) . "\n\n" ;

// 数値をipに戻す
echo long2ip( 3704785104 ) ;
?>
```