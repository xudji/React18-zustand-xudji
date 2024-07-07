React18-zustand-xudji

React18 后端管理模板，快速构建企业级后台管理系统模板，旨在提供基础功能模块，减少不必要的封装，从而加速开发进程并便于后续的灵活扩展。

技术栈：

- react18
- react-router6
- zustand4
- vite4
- axios
- fakerjs、
- dayjs
  ......

支持的功能：

- [x] 登录/退出登录
- [x] 数据持久化存储
- [x] 路由鉴权
- [x] 动态主题
- [x] 错误处理
- [x] axios 封装

# 目录结构

```bash
├─ public                     # 静态资源
│   ├─ favicon.ico            # favicon图标
├─ src                        # 项目源代码
│   ├─ components             # 全局公用组件
│   ├─ layout                 # 布局组件
│   ├─ config                 # 全局配置
│   │   └─ router.tsx         # 路由配置
│   ├─ services               # api接口
│   ├─ stores                 # 全局 store管理
│   ├─ utils                  # 全局公用方法
│   ├─ pages                  # pages 所有页面
│   ├─ App.tsx                # 入口页面
│   ├─ global.d.ts            # 全局声明文件
│   ├─ index.css              # 全局样式文件
│   └─index.tsx               # 源码入口
└── .commitlintrc.js          # 自定义commitlint
└── .cz-config.js             # 自定义commitlint
└── .eslintignore             # eslint忽略文件
└── .eslintrc.js              # eslint配置
└── .prettierrc.js            # prettier配置
└── vite.config.js            # vite打包配置
└── index.html                # html模板
└── package.json              # package.json
```

# 安装及使用

# 安装依赖
npm install(推荐使用pnpm)

# 启动
npm start

# 构建
npm build

# 预览
npm preview

```

# 项目登录(账号密码随便填)

