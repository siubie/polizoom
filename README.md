# polizoom
Generate Zoom Meeting 

1. Buat dulu akun zoom
2. Register app di zoom marketplace
3. Setting client id client secret redirect url
4. setting db
```
CREATE TABLE `token` (
 `id` int(11) NOT NULL AUTO_INCREMENT,
 `access_token` text NOT NULL,
 PRIMARY KEY (`id`)
) ENGINE=InnoDB DEFAULT CHARSET=utf8mb4;
```
5. Looping en max 100 meet create per day 
