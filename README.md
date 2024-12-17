# Tailwind CSS @apply Directive Issue in Imported File

This repository demonstrates a bug where Tailwind's `@apply` directive fails to function correctly when used within a CSS file that's imported into the main stylesheet using `@import`. Other styles from the imported file work as expected, only `@apply` is affected.

## Steps to Reproduce

1. Clone the repository.
2. Run `npm install` or equivalent to install dependencies (if any).
3. Try to build your project. Notice that the styles defined using `@apply` will not be applied.