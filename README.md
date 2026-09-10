# Training TS

## 前奏

### 1.安装typescript

> 安装 Node，然后安装 `npm install typescript -g`，typescript 安装完后，可以通过 `tsc -v` 验证是否安装成功

![Install typescript](/img/img_2026_09_10_21_18_44.webp)

### 2.新建TS文件

新建 `ts` 文件夹，然后添加 `index.ts`

```ts
let strName: string = "Donghai";
```

运行 ts

```bash
tsc --init

tsc -w
```

这个时候目录会生成 js 文件（因为浏览器识别不了 ts 文件，所以需要编译成 js）：

![run ts](/img/img_2026_09_10_21_29_48.webp)

接着新建终端，输入 `node index.js` 执行（node的终端不要关闭），这个时候将会打印代码中的 `strName` 字符串

![first print](/img/img_2026_09_10_21_33_03.webp)

## 0910 基础类型

### 字符串类型
