# Creating components manually

## Create component style files

1. Create a directory for your component in `src/components`.
2. Create a `{component name}.styles.ts` file inside the directory

Refer to the [Writing styles with emotion](./writing-styles-with-emotion.md) guidelines for more instruction.

## Create the React component

1. Create the React component(s) (preferably as TypeScript) in the same directory as the related style file(s).
2. Export these components from an `index.ts` file.
3. Re-export these components from `src/components/index.ts`.

This makes your React component available for import into your project.

## Document the component with examples

1. Create a directory for your example in `src-docs/src/views`. Name it the name of the component.
2. Create a `{component name}_example.js` file inside the directory. You'll use this file to define the different examples for your component.
3. Add the route to this file in `src-docs/src/routes.js`.
4. In the `{component name}_example.js` file you created, define examples which demonstrate the component and describe its role from a UI perspective.

### 👉 Refer to the [Documentation Guidelines](documentation-guidelines.md) for more instruction on writing docs.

[docs]: https://elastic.github.io/eui/
[docs-logical-group]: component-development.md#logically-grouped-components
