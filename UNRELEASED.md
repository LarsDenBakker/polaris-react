# Unreleased changes

### Breaking changes

### Enhancements

- Replaced customer avatar images with a single gray version ([#2453](https://github.com/Shopify/polaris-react/pull/2453))
- Added `external` prop to `ResourceList` ([#2408](https://github.com/Shopify/polaris-react/pull/2408))
- Added `onMouseEnter` and `onTouchStart` props to `Button` ([#2409](https://github.com/Shopify/polaris-react/pull/2409))
- Added `ariaHaspopup` prop to `Popover` ([#2248](https://github.com/Shopify/polaris-react/pull/2248))
- Fixed an accessibility issue where the `Form` implicit submit was still accessible via keyboard ([#2447](https://github.com/Shopify/polaris-react/pull/2447))

### Bug fixes

- Prevented scrolling to `Popover` content in development ([#2403](https://github.com/Shopify/polaris-react/pull/2403))
- Fixed an issue which caused HSL colors to not display in Edge ([#2418](https://github.com/Shopify/polaris-react/pull/2418))
- Fixed an issue where the dropzone component jumped from an extra-large layout to a layout based on the width of its container ([#2412](https://github.com/Shopify/polaris-react/pull/2412))
- Fixed an issue which caused HSL colors to not display in Edge ([#2418](https://github.com/Shopify/polaris-react/pull/2418))
- Changed Button's `disclosure` prop to be `boolean | "up" | "down"`, allowing greater control over the direction the disclosure caret faces ([#2431](https://github.com/Shopify/polaris-react/pull/2431))
- Fixed an issue where the dropzone component jumped from an extra-large layout to a layout based on the width of it's container ([#2412](https://github.com/Shopify/polaris-react/pull/2412))
- Fixed a race condition in DatePicker ([#2373](https://github.com/Shopify/polaris-react/pull/2373))
- Added the top bar height to the `Topbar` in `Frame` to ensure the `Sticky` components get the correct top position ([2415](https://github.com/Shopify/polaris-react/pull/2415))

### Documentation

- Added a details page and kitchen sink example to Storybook ([#2402](https://github.com/Shopify/polaris-react/pull/2402))
- Combined the interface used by `Page` so the types can be parsed ([#2358](https://github.com/Shopify/polaris-react/pull/2358))

### Development workflow

### Dependency upgrades

- Upgraded to TypeScript `v3.7.2` ([#2237](https://github.com/Shopify/polaris-react/pull/2237))
- Upgraded to Prettier to `v1.19.1` ([#2443](https://github.com/Shopify/polaris-react/pull/2443))

### Code quality

- Changed `aria-labelledby` to always exist on `TextField` ([#2401](https://github.com/Shopify/polaris-react/pull/2401))

### Deprecations
