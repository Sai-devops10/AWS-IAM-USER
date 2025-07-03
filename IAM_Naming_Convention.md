# IAM User & Group Naming Convention

To keep IAM users and groups consistent and easy to manage, please follow this naming convention:

## Format

`role-team-environment`

- **role**: user job function (admin, dev, analyst, ops)  
- **team**: team or department (hr, finance, devteam)  
- **environment**: dev, test, prod

## Rules

- Use **only lowercase letters** and hyphens (`-`)  
- No spaces or special characters  
- Allowed environments: `dev`, `test`, `prod`

## Examples

| Valid Names       | Invalid Names       | Reason                  |
|-------------------|---------------------|-------------------------|
| `admin-dev-prod`  | `Admin-Dev-Prod`    | No uppercase letters    |
| `analyst-hr-test` | `analyst_hr_test`   | No underscores          |
| `dev-ops-dev`     | `devops`            | Missing parts           |
|                   | `admin-dev-stage`   | `stage` environment not allowed |

Please follow this when creating IAM users and groups.
