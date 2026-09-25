# Project Testing

## Project Title
Script Controlled ACL Restrict Record Access Based on Field Value

## Testing Objective
To verify that the ACL correctly allows or restricts record access based on the configured field value.

## Test Cases

### Test Case 1: Authorized Access
- User has the required permission.
- Field value satisfies the configured condition.
- Expected Result: Access should be allowed.

### Test Case 2: Unauthorized Access
- User does not have the required permission.
- Field value does not satisfy the configured condition.
- Expected Result: Access should be denied.

### Test Case 3: Different Field Value
- Change the field value.
- Test the same record again.
- Expected Result: Access should change according to the ACL condition.

## Testing Re…
