## Slidev 模板

一个标准的 Slidev 项目模板结构包括如下文件

```txt
./default/
├── README.md # 记录会议时间、标题和副标题
└── src
    ├── components # 自定义的 vue 组件
    │   └── Counter.vue
    ├── package.json
    ├── pages # 存储被引用的 slidev
    │   └── imported-slides.md
    ├── public # 存储图片等静态资源
    ├── slides.md # 入口文件（更改此文件以编写 slide）
    ├── snippets # 存储被引用的代码（需搭配 monaco-run）
    │   └── external.ts
    ├── styles # css 样式
    │   └── index.css
    └── vite.config.ts
```

## 使用方式

将任意 Slidev 项目模板复制到项目根路径下使用

```bash
cp -r templates/default ./0000-00-00
```

## 模板列表

1. `default` 默认模板，包含了官方使用 slidev 的示例
2. `academic` 学术汇报模板，参考自 [slidev-theme-academic](https://github.com/alexanderdavide/slidev-theme-academic)
