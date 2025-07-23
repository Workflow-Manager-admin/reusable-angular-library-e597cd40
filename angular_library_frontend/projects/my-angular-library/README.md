# my-angular-library

A reusable Angular library for use with Angular applications.

## Usage

1. Add this library as a dependency in your Angular application (once published to npm).
2. Import the library module in your app:

```typescript
import { MyAngularLibraryModule } from 'my-angular-library';
// Add MyAngularLibraryModule to your NgModule imports.
```

### Example

```html
<my-angular-library-example></my-angular-library-example>
```

## Development

This library is built using Angular CLI library conventions. Source code is in this `projects/my-angular-library/` folder.

- Build the library:

  ```
  ng build my-angular-library
  ```

- Run tests:

  ```
  ng test my-angular-library
  ```

## Storybook

Storybook support can be added for visual testing and documentation of components.

## Publishing

To publish:

1. Run `ng build my-angular-library --configuration production`
2. The output will be in `dist/my-angular-library`.
3. Publish using `npm publish dist/my-angular-library`.

Remember to update package metadata before publishing.

## Further documentation

- [Angular CLI: Libraries](https://angular.io/guide/creating-libraries)
