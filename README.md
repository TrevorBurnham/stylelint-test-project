# stylelint-test-project

This is a minimal project demonstrating a stylelint configuration that works with styled-components as of Dec 17, 2022.

Prompted by this discussion: [https://github.com/styled-components/styled-components/issues/3607](https://github.com/styled-components/styled-components/issues/3607)

## Expected behavior

```sh
$ npm install
$ npm run lint:css

> lint:css
> stylelint **/*.{js,jsx,ts,tsx}


src/index.tsx
 4:3  ✖  Unexpected unknown property "pposition"  property-no-unknown
 6:3  ✖  Unexpected duplicate "display"           declaration-block-no-duplicate-properties

2 problems (2 errors, 0 warnings)
```
