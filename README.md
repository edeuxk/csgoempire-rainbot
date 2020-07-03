# Csgoempire Rainbot

This script collect free coins when csgoempire do a rain.

  - Clean code

### Setup
- Connect to csgoempire.com
- Open your browser console (F12 or right click)
- Copy past the following code
```sh
setInterval(function(){for(var e=document.getElementsByTagName("button"),n=0;n<e.length;n++)-1<e[n].innerText.indexOf("Claim FREE Coins")&&(e[n].click(),console.log("Coins claimed"))},1e4),console.log("[RAINBOT] - Script started");
```
