# Start

中文 | [英文](https://github.com/Tyh2001/fighting-design/blob/master/start/README.en-US.md)

## 说明

开发目录，在这里测试你的组件

## 开发阶段

在 `main.ts` 中，通过下面方式可以直接引入 `fighting-design/package` 下开发好的组件

```ts
import FightingDesign from '@fighting-design/fighting-components'
import '@fighting-design/fighting-theme'
```

## 打包阶段

如果你执行了 `pnpm build` 之后，想要测试你的打包文件是否可以正常工作，那么可以通过下面方式引入 `dist` 目录下的组件进行测试

```ts
import FightingDesign from '../dist'
import '../dist/theme/index.css'
```
