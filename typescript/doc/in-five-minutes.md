

 [原文链接](https://www.tslang.cn/docs/handbook/typescript-in-5-minutes.html)
 # 1、安装typescript
 ```
 npm install -g typescript
 ```
 # 2、运行
tsc 1.ts
function greeter(person: string) {
    return "Hello, " + person;
}

let user = [0, 1, 2];

document.body.innerHTML = greeter(user);