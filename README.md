# `@axate/prettier-config`

Shared config for Prettier for frontend projects @ axate.com

# How to use

**Install**

```
yarn add --dev @axate/prettier-config
```

**a) use with package.json**

```
// package.json
{
  ...,
  "prettier": "@axate/prettier-config"
}
```

**b) use with .prettierrc.json**

```
// .prettierrc.json
"@axate/prettier-config"
```

**Overrides**

Options above do not allow to extend the configuration. For that, you need to use following approach:

```
// .prettierrc.js
module.exports = {
  ...require("@axate/prettier-config"),
  // custom overrides here
};
```

[More info on shared configurations](https://prettier.io/docs/en/configuration.html#sharing-configurations)