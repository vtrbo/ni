# @vtrbo/ni [![npm](https://img.shields.io/npm/v/@vtrbo/ni?color=a1b858&label=)](https://npmjs.com/package/@vtrbo/ni)

Forked from [antfu/ni](https://github.com/antfu/ni)

### 安装
```shell
@vtrbo/ni

npm install -g @vtrbo/ni
```

### `ni` - install

```shell
ni

# npm install
# yarn install
# pnpm install
# bun install
```

```shell
ni vite

# npm i vite
# yarn add vite
# pnpm add vite
# bun add vite
```

```shell
ni @types/node -D

# npm i @types/node -D
# yarn add @types/node -D
# pnpm add @types/node -D
# bun add @types/node -d
```

```shell
ni --frozen

# npm ci
# yarn install --frozen-lockfile (Yarn 1)
# yarn install --immutable (Yarn Berry)
# pnpm install --frozen-lockfile
# bun install --no-save
```

```shell
ni -g eslint

# npm i -g eslint
# yarn global add eslint (Yarn 1)
# pnpm add -g eslint
# bun add -g eslint
```

### `nr` - run

```shell
nr dev --port=3000

# npm run dev -- --port=3000
# yarn run dev --port=3000
# pnpm run dev -- --port=3000
# bun run dev --port=3000
```

### `nx` - execute

```shell
nx vitest

# npx vitest
# yarn dlx vitest
# pnpm dlx vitest
```

### `nu` - upgrade

```shell
nu

# npm upgrade
# yarn upgrade (Yarn 1)
# yarn up (Yarn Berry)
# pnpm update
```

```shell
nu -i

# (not available for npm & bun)
# yarn upgrade-interactive (Yarn 1)
# yarn up -i (Yarn Berry)
# pnpm update -i
```

### `nun` - uninstall

```shell
nun webpack

# npm uninstall webpack
# yarn remove webpack
# pnpm remove webpack
# bun remove webpack
```

```shell
nun -g eslint

# npm uninstall -g eslint
# yarn global remove eslint
# pnpm remove -g eslint
# bun remove -g eslint
```

### `nci` - clean install

```shell
nci

# npm ci
# yarn install --frozen-lockfile
# pnpm install --frozen-lockfile
# bun install --no-save
```

### `na` - agent alias

```shell
na

# npm
# yarn
# pnpm
# bun
```

```shell
na run foo

# npm run foo
# yarn run foo
# pnpm run foo
# bun run foo
```

### Change Directory

```shell
ni -C packages/foo vite
nr -C playground dev
```

### Config

```ini
# ~/.nirc

# fallback when no lock found
defaultAgent=npm

# for global installs
globalAgent=npm
```

```shell
# ~/.bashrc

# custom configuration file path
export NI_CONFIG_FILE="$HOME/.config/ni/nirc"
```

## 开源许可证

[MIT](./LICENSE) License &copy; 2022-PRESENT [Victor Bo](https://github.com/vtrbo)
