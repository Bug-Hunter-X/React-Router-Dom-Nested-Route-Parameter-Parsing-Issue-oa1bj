# React Router DOM Nested Route Parameter Parsing Issue

This repository demonstrates an uncommon bug encountered when using nested routes and parameters in React Router DOM.  The issue involves the unexpected behavior when navigating to a nested route directly via a link, resulting in incorrect parameter parsing.

The problem arises when the nested route parameter is not correctly extracted from the URL when navigating to that route directly. This bug can lead to unexpected application behavior or errors.

## Bug Reproduction

1. Clone this repository.
2. Run `npm install`.
3. Run `npm start`.
4. Navigate to the nested route directly (e.g., `/users/123`).  Notice that the parameter is not correctly parsed.
5. Compare this behavior with navigating to the parent route and then clicking through to the child route.