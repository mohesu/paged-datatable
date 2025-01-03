## 2.2.1

- Merge dev branch into main 

## 2.2.0-dev1.1

This does not include any new feature, it just adds the documentation for expansible rows.

## 2.2.0-dev1

- Add expansible rows. Check out documentation to know how you can implement this feature.
- Add a bunch of new locales. Make sure to check the full list. Thanks community!
- Fix FilterBar is not hidden when no filter is added. 
- Rewrite README.md

## 2.1.1

- Fix Date- filters not showing `name` attribute as label in the text field.
- Fix FractionalColumnSize does not calculate correctly sizes.
- physics: const ClampingScrollPhysics()

## 2.1.0

- Add Italian locale

## 2.0.1

- Fix a bug in controller that does not reload dataset when applying a sort filter

## 2.0.0

> First public release of paged-datatable v2

- `intl` was updated to version 0.19.0

## 2.0.0-dev.4

- Update documentation
- Add more controller examples
- Fix several issues

> The next version will be a complete release. This version can be used in production. I'm waiting for feedback to publish
> a release.

## 2.0.0-dev.3

- Add localizations again.
- Add TextField-like editable columns.
- Add `ProgrammaticTableFilter`.
- Add `DateTimePickerTableFilter` and `DateRangePickerTableFilter`.

> Keep in mind this is an uncomplete release. Probably the next version will be a complete release.

## 2.0.0-dev.2

- Add filter bar and filters.
- Add controller methods to manage filters.
- Removed PagedDataTableMenu. Now to display a menu, use the `filterBarChild` and a `PopupMenuButton`.
- Improved the calculation of column widths.

> Keep in mind this is an uncomplete release. I will continue working on this package actively.

## 2.0.0-dev.1

**First prerelease of PagedDataTable v2!**

- Adds Horizontal scrolling.
- Fixes row selection.
- Adds a better `TableController`.
- Better column sorting.

> Keep in mind this is an uncomplete release. Filters, intl and cell edition features are disabled. I will continue working on this package
> actively.

## 1.4.4

- Add support for 'de' locale
- Fix initialPageSize is ignored when setup the widget

## 1.4.3

- Update dependencies
- Format dart code

## 1.4.2

- Packages version upgrade

## 1.4.1

- Improve documentation

## 1.4.0

- Remove internal memory cache.
- Display checkbox as the first column if the table allows row selection
- Bug fixes related to theming
- Add pagination methods to controller
- Improve drawing performance
- Better pub.dev documentation incoming

## 1.3.0

- Add option to completely remove the footer.
- Improve `PagedDataTableTheme` documentation.

## 1.2.0

- Upgrade Flutter version
- Make it compatible with Dart 3

## 1.1.4

- Apply dividerColor on every divider line.
- Add buttons theme

## 1.1.3

- Apply dividerColor on every divider line.
- Add buttons theme

## 1.1.2

- Revert old styling

## 1.1.1

- Fix bugs while customizing text styles

## 1.1.0

- Add better customization by placing a common widget or for a specific one using PagedDataTableTheme

## 1.0.17

- Add method to TableController to allow updating a row based on a predicate.

## 1.0.16

- Fix wrong header alignment

## 1.0.15

- Header child now can take less width. Replaced Expanded with Flexible.

## 1.0.14

- Add method to get applied filters from controller

## 1.0.13

- Fix small bug

## 1.0.12

- Add Flexible to every row

## 1.0.11

- Add option to remove the size of the rows

## 1.0.10

- Fix locales
- Fix refresh current dataset
- Add option to remove a row without reloading the entire dataset

## 1.0.9

- Remove header when no filter is added

## 1.0.8

- Added `ProgrammaticTableFilter`

## 1.0.7

- Fix menu overlay is not opening correctly

## 1.0.6

- Fix call stack exceeded

## 1.0.5

- Small bug fixes

## 1.0.4

- Add refresh listener. Listen to a stream and refresh the dataset when it changes
- Add custom row builder

## 1.0.3

- Add option to set default filters

## 1.0.2

- Fix scores

## 1.0.1

- Fix homepage

## 1.0.0

- Rewrite all the code from scratch

## 0.4.9

- Fixes ScrollController

## 0.4.8

- Fixes ScrollController

## 0.4.7

- When the page changes, the scrollbar is animated to the top of the table

## 0.4.6

- Fixes a bug with filters scrollbar

## 0.4.4

- Fixes a timer bug.

## 0.4.0

- Add a custom row builder

## 0.3.1

- Add option to clear selected rows

## 0.3.0

- Add refresh listener
- Add separated widget to build custom filters.

## 0.2.0

- Add widget to build custom filters.

## 0.1.0

- Initial release.
