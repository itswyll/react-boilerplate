# erp-system

Internal ERP system

## Extensions

For more consistency in development

### CSS

Styled components, or SCSS with css modules can be used.
Both will allowed for reuse of component-like styles, but SCSS is likely more straightforward design wise.
This would separate out the styling, scss just needs to be set in linting.

- Set browserlist
  - https://parceljs.org/languages/javascript/#browser-compatibility
  - https://github.com/browserslist/browserslist#best-practices
- If images are used?
  - https://github.com/okonet/lint-staged#minify-the-images

#### Styled Components

- Looking into sorting the styled components side with style-lint and typescript interactions.
  - https://github.com/Igorbek/typescript-plugin-styled-components
- Testing components with jest
  - https://github.com/styled-components/jest-styled-components
- If there are clashes linting with styled-comps
  - https://github.com/styled-components/stylelint-config-styled-components/blob/master/index.js

#### SCSS

- Alternatively sass with modules seems good
  - https://parceljs.org/languages/css/#css-modules
  - https://github.com/css-modules/css-modules

### Typescript

- May require different transpiler depending on .tsconfig
  - https://parceljs.org/languages/typescript/#tsc
