# Start

English | [Chinese](https://github.com/Tyh2001/fighting-design/blob/master/start/README.md)

## explain

Your component development directory is here

## Development phase

In `main.ts`, components developed under `fighting-design/package` can be directly introduced in the following ways

```ts
import FightingDesign from '@fighting-design/fighting-components'
import '@fighting-design/fighting-theme'
```

## Packaging phase

If you want to test whether your package file can work normally after you execute `pnpm build`, you can import the components under `dist` directory for testing in the following way

```ts
import FightingDesign from '../dist'
import '../dist/theme/index.css'
```
