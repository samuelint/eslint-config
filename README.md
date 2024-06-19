# Samuel Magny - eslint-config

My goto eslint config

:warning: It does not support FLAT Config. Only works with `ESLint < 9`. If used with `ESLint 8` -> `ESLINT_USE_FLAT_CONFIG=false eslint .`

## How to use

### 1. Install

##### pnpm

```
pnpm add -D @samuelint/eslint-config
```

### 2. Configure

```
# .eslintrc.json
{
    "extends": "@samuelint/eslint-config",
    ...
}
```

OR

```
# .eslintrc.js
{
    extends: "@samuelint/eslint-config",
    ...
}
```

### 3. Enjoy

## References

https://eslint.org/docs/latest/extend/shareable-configs
