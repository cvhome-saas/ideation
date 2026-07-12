# Feature: Dynamic Landing Page Config
**ID**: F-002

## Description
Support dynamic configuration for the landing page for every store. 
- **First Stage**: Use a static config from the backend that determines how the `landing-ui` will display components on the landing page. We will not build a visual builder at this stage. Every store will have a static config defining how to display its initial landing page.
- **Future Stage**: Build a builder in `seller-ui` to configure this config and manage what should be displayed.

## Affected Modules
- `backend`
- `landing-ui`
- `seller-ui` (future)
