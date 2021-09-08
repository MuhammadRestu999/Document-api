
 
# REST- API FULL 
Kumpulan database semua fitur yang ada di restapifull
<p align="center">
</p>
<p align="center">
<a href="https://github.com/zeeoneofc"><img title="Author" src="https://img.shields.io/badge/Author-Rey-orange.svg?style=for-the-badge&logo=github"></a>
</p>
<p align="center">
<a href="https://github.com/inirey/followers"><img title="Followers" src="https://img.shields.io/github/followers/inirey?color=red&style=flat-square"></a>
<a href="https://github.com/inirey/Document-api/stargazers/"><img title="Stars" src="https://img.shields.io/github/stars/inirey/Document-api?color=blue&style=flat-square"></a>
<a href="https://github.com/inirey/Document-api/network/members"><img title="Forks" src="https://img.shields.io/github/forks/inirey/Document-api?color=red&style=flat-square"></a>
<a href="https://github.com/inirey/Document-api/watchers"><img title="Watching" src="https://img.shields.io/github/watchers/inirey/Document-api?label=Watchers&color=blue&style=flat-square"></a>
</p>

## main REST- API
Check it [Here](https://restapifull-by-rey.herokuapp.com/api)


## Endopoint?
Pengambilan Endopoint
```js
await fetchJson(`https://restapifull-by-rey.herokuapp.com/api/anime/minato?apikey=administrator`, {method: 'get'})
await fetchJson(`https://raw.githubusercontent.com/inirey/Document-api/main/minato.json`)
```
## Client settings

```js
rey = await fetchJson(`https://restapifull-by-rey.herokuapp.com/api/anime/minato?&Apikey=administrator`, {method: 'get'})
min = JSON.parse(JSON.stringify(rey));
ato =  min[Math.floor(Math.random() * min.length)];
hasil = await getBuffer(ato)
client.sendMessage(from, hasil, image, { caption: 'anime Minato', quoted: mek })
```
</p>
