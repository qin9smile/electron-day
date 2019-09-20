# Electron Day
Electron学习

## init - Electron 与 create-react-app的结合

### Step 1

```bash
npx create-react-app electron-day
cd electron-day
```

安装 `Electron` 及相关依赖
注： `electron-builder` 是目前比较推荐的`Electron`打包工具

```bash
yarn add electron electron-builder --dev

# 安装一些工具
yarn add wait-on concurrently --dev
yarn add electron-is-dev
```
