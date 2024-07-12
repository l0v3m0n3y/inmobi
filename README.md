# inmobi
JavaScript library for cmp.inmobi.com
# main
```js
async function main(){
    const {inmobi} = require('./inmobi');
    const mobi= new inmobi();
    let req=await mobi.geo_ip()
    console.log(req)
}
main()
```
