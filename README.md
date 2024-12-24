# Dynamic Content Purge Issue with Tailwind CSS in Next.js/Nuxt.js

This repository demonstrates a common issue encountered when using Tailwind CSS with frameworks like Next.js or Nuxt.js.  The problem arises when Tailwind's purge process fails to identify and include CSS classes generated dynamically. This results in missing styles for components or content rendered after the initial build.

The `bug.js` file contains example code that showcases the issue. The `bugSolution.js` demonstrates the solution to this problem.

## Steps to Reproduce

1. Clone this repository.
2. Run `npm install`.
3. Run the development server (depending on your framework).
4. Observe the missing styles in the dynamically rendered content.