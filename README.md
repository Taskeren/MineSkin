# MineSkin
The PHP program to get Minecraft players' skin.

## How to use(Server)
1. Star this repository.
1. Download the index.php
1. Place it to a PHP server.

## How to use(Player)

```
https://api.taskeren.cn/MineSkin/?id={id}&format={format}
```

### id
The players' ID.

### format

#### (empty)
Return the url directly.
```
http://textures.minecraft.net/texture/292009a4925b58f02c77dadc3ecef07ea4c7472f64e0fdc32ce5522489362680
```

#### json
Return the json that contains `url` and `profile`.
```
{"url":"http:\/\/textures.minecraft.net\/texture\/292009a4925b58f02c77dadc3ecef07ea4c7472f64e0fdc32ce5522489362680","profile":{"name":"Notch","id":"069a79f444e94726a5befca90e38aaf5"}}
```

#### image
Return the image file.

![](http://textures.minecraft.net/texture/292009a4925b58f02c77dadc3ecef07ea4c7472f64e0fdc32ce5522489362680)
