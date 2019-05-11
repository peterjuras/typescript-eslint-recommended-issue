Extending the `plugin:@typescript-eslint/eslint-recommended` configuration  [as specified in the config readme](https://github.com/typescript-eslint/typescript-eslint/tree/master/packages/eslint-plugin/src/configs#eslint-recommended) currently throws an error:

```
Oops! Something went wrong! :(

ESLint: 5.16.0.
ESLint couldn't find the config "plugin:@typescript-eslint/eslint-recommended" to extend from. Please check that the name of the config is correct.
```

### Steps to reproduce:

1. `git clone https://github.com/peterjuras/typescript-eslint-recommended-issue.git`
2. `cd typescript-eslint-recommended-issue`
3. `yarn install`
4. `yarn lint`
