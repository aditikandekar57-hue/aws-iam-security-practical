<img width="1366" height="768" alt="ec2-accesed-denied" src="https://github.com/user-attachments/assets/41cd2016-dcd2-44f0-987e-625cf1090cf7" /># aws-iam-security-practical
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

## Screenshot
[Access Denied](ec2-access-denied.png)



