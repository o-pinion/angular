# angular-opinionated
Opiniated angular project structure 

## Contains
- [Structures](https://github.com/rbalet/angular-opinionated/wiki)
- [CSS Naming convention](https://github.com/o-pinion/angular/wiki/CSS-Naming-convention)
- [Conventions](https://github.com/o-pinion/angular/wiki/conventions)

## Helpers
- .eslintrc.json: Help update angular-eslint rules with the proposed project structure.

## .eslintrc.json 
Inside the `eslint.config.ts` file, adds the following

```typescript
const oLint = require('@o-pinion/angular/.eslintrc.json')

module.exports = tseslint.config(
  oLint,
  ...
)

```
