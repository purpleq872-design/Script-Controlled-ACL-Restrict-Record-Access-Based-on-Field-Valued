# Project Design

## Project Title
Script Controlled ACL Restrict Record Access Based on Field Value

## System Design
The system uses a Script-Controlled Access Control List (ACL) to control access to records based on a specific field value.

## Main Components
- User
- Record
- Field Value
- ACL Rule
- Access Control Script

## Working Flow
1. User requests access to a record.
2. The ACL checks the user's permission.
3. The system checks the required field value.
4. If the condition is satisfied, access is granted.
5. Otherwise, access is denied.

## Security Design
The ACL ensures that unauthorized users cannot access restricted records.

## Expected Result
Record access is dynamically controlled based on the configured field value.
