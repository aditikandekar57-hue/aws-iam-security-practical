# aws-iam-security-practical
## Objective
To implement AWS IAM best practices by creating users with limited permissions and verifying access control.

## Tasks Performed
- Enabled MFA for root user
- Created IAM user with EC2 read-only permissions
- Created IAM group and attached managed policy
- Verified least privilege by testing EC2 launch restriction

## Security Concepts Applied
- Least privilege principle
- Identity-based access control
- Root user protection
- Permission testing

## Outcome
IAM user was able to view EC2 resources but denied permission to launch instances, confirming correct security configuration.

## Screenshots
![IAM User](iam-user.png)
![IAM Group](iam-group-policy.png)
![Access Denied](ec2-access-denied.png)
![Root MFA](root-mfa.png)
