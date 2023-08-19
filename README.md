# higgs-cheat
https://higgs.boson.jp/ というサイトで使えるチートです。  
コピーしてコンソールで実行するか、ブックマークレートにして使ってください。

```javascript
function typeKey(){if(!document.querySelector("[class^='Typing_roman__']")||globalThis.typeNow)return"Created by @amex2189";globalThis.typeNow=!0;let e=document.querySelector("[class^='Typing_roman__']"),t=e.textContent,y=t.split("");y.forEach((t,y)=>{setTimeout(()=>{let y=new KeyboardEvent("keydown",{key:t,code:"Key"+t.toUpperCase(),keyCode:t.charCodeAt(0),bubbles:!0,cancelable:!0});e.dispatchEvent(y)},2*y)}),setTimeout(()=>{globalThis.typeNow=!1},(y.length+1)*2)}globalThis.typeNow=!1,setInterval(typeKey,100);
```

現在は対策済みです
[https://x.com/amex2189/status/1692939183571214362](https://x.com/amex2189/status/1692939183571214362)
しかしまだ抜け穴が有るので探って見てください…