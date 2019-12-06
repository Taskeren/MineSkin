# MineSkin
The PHP program to get Minecraft players' skin.

### How to use(Server)
1. Star this repository.
1. Download the index.php
1. Place it to a PHP server.

### How to use(Player)

```
https://api.taskeren.cn/MineSkin/?id={id}&format={format}
```

#### id
The players' ID.

#### format

**(empty)**
Return the url directly.
```
http://textures.minecraft.net/texture/d86bbfcda11dd58bf5576bb8e2c04b290893e690cf51584d08e63525caab2af7
```

**json**
Return the json that contains `url`.
```
{"url":"http://textures.minecraft.net/texture/d86bbfcda11dd58bf5576bb8e2c04b290893e690cf51584d08e63525caab2af7"}
```

**image**
Return the image file.
![](http://textures.minecraft.net/texture/d86bbfcda11dd58bf5576bb8e2c04b290893e690cf51584d08e63525caab2af7)
