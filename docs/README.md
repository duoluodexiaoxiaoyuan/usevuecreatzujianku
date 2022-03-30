# 快速开始

#### 安装组件库

```bash
npm i usevuecreatzujianku
```

#### 引用组件库

> 在 main.js 中引用组件库

```javascript
// 全部引入
import "usevuecreatzujianku/dist/css/index.css";
import MUI from "usevuecreatzujianku";
Vue.use(MUI);

// 按需引入
import "usevuecreatzujianku/dist/css/demo.css";
import { Demo } from "usevuecreatzujianku";
Vue.use(Demo);
```
