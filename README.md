# Terminal Roast

Real-time AWS misconfiguration detection with contextual remediation. Terminal Roast helps you identify and fix AWS security issues before they become problems.

![Terminal Roast Demo](https://github.com/user-attachments/assets/0700125d-d464-47f5-bc07-5197bee0ba78)

## Features

### 🔥 S3 Bucket Security
- Detects public or poorly configured S3 buckets
- Checks for missing encryption, logging, and versioning
- Real-time monitoring via CloudTrail events
- Provides instant remediation commands

### 🔥 IAM Policy Analysis
- Identifies overly permissive IAM policies
- Detects unused permissions
- Validates MFA and password policies
- Suggests least-privilege fixes

### 🔥 Security Group Monitoring
- Spots exposed security groups and open ports
- Identifies unused security group rules
- Real-time detection of new ingress rules
- Generates ready-to-use remediation commands

### 🔥 Encryption Coverage
- Monitors EBS volumes for encryption
- Checks RDS instances for storage encryption
- Validates SQS queue encryption settings
- Provides step-by-step encryption guidance

## Requirements

- Python 3.8+
- AWS credentials configured
- Required permissions (see docs/permissions.md)

## Contributing

We welcome contributions! Please see our [Contributing Guide](CONTRIBUTING.md) for details.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Security

Found a security issue? Please check our [Security Policy](SECURITY.md) for reporting guidelines.

