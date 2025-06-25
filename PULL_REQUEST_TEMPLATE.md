# PR Title Tags to choose from (multiple tags can be used)

- [ ] Feature
- [ ] Bugfix
- [ ] Refactor
- [ ] Infrastructure
- [ ] Test
- [ ] Documentation

> Follow tags with name for the PR prefixed with one of the 3 tags add:, modify:, or remove:

E.g. [Bugfix] modify JWT token validation to handle decoding errors
E.g. [Feature] add new file preview for .eml files in frontend
E.g. [Refactor] modify add_user function and decompose into multiple pure functions

## PR Body Templates

### Feature PR Body Template

#### Summary

- 1 to 2 line summary of the changes
- E.g. Added JWT token validation to secure the login process.

#### Changes

- List of actual changes made in the code.
- E.g. Updated `lambda_handler.py` to delegate authentication.
- E.g. Created `auth.py` with JWT validation functions.
- E.g. Added unit tests for new authentication functionality.

#### Checklist

- [ ] Tests added for new functionality.
- [ ] Code compiles and passes all tests and CI checks.
- [ ] Documentation updated.

### Bugfix PR Body Template

#### Summary

- 2 to 3 line summary of the problem and the solution.
- E.g. Added type validation to file upload to prevent errors when uploadings invalid file types.
- Note if temporary hotfix or robust fix.

#### Checklist

- [ ] Tests added for new functionality (if robust fix).
- [ ] Code compiles and passes all tests and CI checks.
- [ ] Documentation updated.

### Refactor PR Body Template

#### Summary

- 1 to 2 line summary of the changes.
- E.g. Removed unused code in auth module.
- E.g. Decomposed mixed logic /login route into smaller functions.

#### Changes

- List of actual changes made in the code.
- Name the original files/functions and describe the changes made to them.
- E.g. Removed unused functions in `auth.py`.
- E.g. Changed error handling in `user.py` to use a more specific exception.

#### Checklist

- [ ] Tests added for new functionality (if robust fix).
- [ ] Code compiles and passes all tests and CI checks.
- [ ] Documentation updated.
