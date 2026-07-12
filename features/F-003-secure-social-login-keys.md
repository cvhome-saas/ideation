# Feature: Secure Social Login Keys
**ID**: F-003

## Description
Secure customer keys used for social login in our database. 
- Ensure that sensitive keys (like app client ID and secret) provided by the customer in the admin dashboard are securely stored.
- These keys are used to configure social login integrations with providers like Google, GitHub, and Facebook.
- Keys must be encrypted at rest in the database to prevent unauthorized access.

## Affected Modules
- `backend`
- `seller-ui` (admin dashboard)
