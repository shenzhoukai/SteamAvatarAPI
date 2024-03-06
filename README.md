# SteamAvatar
Steam Avatar URL API

### Request URL
https://steam.shenzhoukai.com/avatar.php

### Request Method
GET

### Request Param
SteamID(Requireed) - Player's Steam64 ID, start with 7656
Size(if not set, default as small) - small, medium, full

### Usage Demo
[https://steam.shenzhoukai.com/avatar.php?SteamID=76561198122095489&Size=full)](https://steam.shenzhoukai.com/avatar.php?SteamID=76561198122095489&Size=full

### Extra Function
Divert according to requested IP addresses - User will get a Chinese mainland cdn url of avatar img if user is requesting from Chinese mainland. Otherwise, user get the orginal url of avatar url from Steam API.
Referer Access - This API just accept request from whitelisted domain and empty referer. If you need to under in your domain as CORS, please contact me to add your domain into our whitelist.
