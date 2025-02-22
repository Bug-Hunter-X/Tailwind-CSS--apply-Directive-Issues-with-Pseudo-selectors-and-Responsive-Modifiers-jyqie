# Tailwind CSS @apply Directive Bug

This repository demonstrates a bug related to Tailwind CSS's `@apply` directive when used with pseudo-selectors (`:hover`, `:focus`, etc.) and responsive modifiers (`md:`, `lg:`, etc.).  The `@apply` directive fails to correctly apply styles in these scenarios.

## Bug Description
The `@apply` directive, when used with classes containing pseudo-selectors or responsive modifiers, does not apply styles as expected.  This leads to styles not being applied on hover, focus, or specific screen sizes.

## Reproduction Steps
1. Clone this repository.
2. Open `bug.html` in your browser.
3. Observe that the hover effect and the responsive behavior are not working correctly.
4. Open `bugSolution.html` to see the solution.

## Solution
The solution involves avoiding the use of `@apply` for pseudo-selectors and responsive modifiers and instead applying classes directly.
