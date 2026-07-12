# Feature: Customer Profile Update
**ID**: F-004

## Description
Allow customers of a store to update their personal information and delivery addresses.
- Customers can update their address, phone number, and other profile details.
- **Restriction**: "Main" information fetched from trusted social providers (e.g., email address) cannot be modified by the user to maintain data integrity and account security.
- The system must differentiate between user-editable fields and provider-locked fields.

## Affected Modules
- `backend` (Update logic and validation)
- `landing-ui` (Customer profile/account settings page)
