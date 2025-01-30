# prettier-config

## Install

1. Install Eslint on your projet

```shell
yarn add --dev prettier prettier-plugin-tailwindcss
```

2. Install config

```shell
yarn add --dev @nodstudio/prettier-config
```

3. Add prettier config

```json
// package.json
{
    // ...
    "prettier": "@nodstudio/prettier-config",
}
```

or

```json
// .prettierrc
"@nodstudio/prettier-config"
```

See [using a shareable config](https://prettier.io/docs/sharing-configurations/#using-a-shareable-config) for further information
