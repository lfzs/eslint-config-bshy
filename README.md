# eslint-config-bshy

eslint 配置文件

## 使用方式

### 原生 JavaScript/Node 项目

1、`pnpm add @bshy/eslint-config-vanilla`

2、添加到 .eslintrc.json 配置文件

```json
"extends": [
  "@bshy/eslint-config-vanilla"
]
```

### 原生小程序项目

1、`pnpm add @bshy/eslint-config-miniprogram`

2、添加到 .eslintrc.json 配置文件

```json
"extends": [
  "@bshy/eslint-config-miniprogram"
]
```

注意：eslint 解析器是 @babel/eslint-parser 和官方的 Espree 会有一些差异，[参考](https://www.npmjs.com/package/@babel/eslint-parser)

### Vue 3 项目

TODO

### Vue 3 + Typescript 项目

TODO

### 注意事项

1、TODO
