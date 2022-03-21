# Discord Account Token
*In this tutorial i will be showing you how to find your discord account token*

## 📝 Requirements
* Discord Account
* Desktop / Laptop
* Internet Access

## 💪 Setup
* Open Discord on your browser and open inspect element `CONTROL`+`SHIFT`+`I`
* Once inspect element is opened click the `Console` tab on the top
* Paste the following code in the console and press `Enter` on your keyboard
```javascript
(webpackChunkdiscord_app.push([[''],{},e=>{m=[];for(let c in e.c)m.push(e.c[c])}]),m).find(m=>m?.exports?.default?.getToken!==void 0).exports.default.getToken()
```
* 🎉 Congratulations you have successfully found your discord account token
