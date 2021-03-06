## `master`

## 1.6.0
* Add path navigation for exports [#35](https://github.com/AsaAyers/js-hyperclick/pull/35)
  * `export * from './foo';`
  * `export { x, y } from './bar';`
  * `export default from './baz'`

## 1.5.0
* Add configuration to enable pending panes
* Add configuration for custom module roots.
  * This is configured in your `package.json` because it is project-specific.

## 1.4.0
* Add configuration for alternate file extensions. Use this to make `require(./foo)` pick up `./foo.jsx`

## 1.3.0
* Allow linking to relative files that don't exist yet
* Fixed #6 prevent throwing when a module doesn't resolve

## 1.2.0
* Fixed #2 Make import/require paths into links

## 1.1.5 - function declarations
* Fixed #5: Function declaration parameters weren't linkable

## 1.1.4 - identifiers
* Fixed #4: include `$` as a valid identifier

## 1.1.0 - Imports / Requires
* Jump through `import` / `require()` to where the variable was exported from

## 1.0.0 - First Release
* Link to variables defined in the same file
