## 簡答
簡單回答即可，也可以畫圖或以pseudo code示意

### Programming

1. 請寫出執行此段code後會輸出什麼結果及原理
```javascript
b();
console.log(a);

var a = 'Hello World!';

function b() {
    console.log('Called b!');
}
```

2. 請簡述IIFE

3. 請簡述javascript中event loop如何運作與同步/非同步的關係

4. 請簡單解釋closure

5. 請簡述es5 function與arrow function的不同

6. 考慮以下的code，請改寫為typescript

```javascript
function createArray(length, value) {
    let result = [];
    for (let i = 0; i < length; i += 1) {
        result[i] = value;
    }
    return result;
}
```

### Develop

1. 請簡述git-flow的概念

2. 請簡述webpack/babel的使用情境及作用

3. 請簡述你平常debug的流程為何

4. 你用過哪些前端framework，請簡單說出優點及缺點
