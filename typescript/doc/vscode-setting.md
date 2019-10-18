
1、打开命令行，输入 `npm i -g typescript` 全局安装TS
2、继续在命令行输入 `tsc -init` 生成一个 tsconfig.json 的配置文件
3、打开 tsconfig.json ，主要选项已经设置好了，常用的设置是
```
{
    "target": "es5",
    "module": "commonjs",
    "outDir": "./js",                        /* Redirect output structure to the directory. */
    "rootDir": "./es",  
    "strict": true, 
    "esModuleInterop": true
}
```
4、使用快捷键 `CTRL + SHIFT + P` 输入 `code .` 选择 tsc:监视 任务。需要注意的终端的shell必须是cmd，用bash会无效
5、使用快捷键 `CTRL + SHIFT + B` 快速执行任务，必须在英文输入法的状态下输入，中文会调出emoji表情包
