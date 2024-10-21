# Splunk App for AWS Cloud Security Monitoring

This Splunk app provides comprehensive monitoring and alerting for AWS cloud security activities. It includes pre-configured dashboards and alerts to help you maintain a secure cloud environment.

## Author

Kumbira Muhwati

## Features

- Real-time monitoring of AWS CloudTrail logs
- Customizable dashboards for visualizing security events
- Pre-configured alerts for common security threats
- Easy integration with existing Splunk deployments

## Installation

1. Download the app from the Splunk App store or this GitHub repository.
2. Install the app on your Splunk instance:
   - Splunk Web: Apps > Manage Apps > Install app from file
   - CLI: `splunk install app /path/to/splunk-aws-security-monitor.tar.gz`
3. Restart Splunk
4. Configure the app with your AWS credentials (see Configuration section)

## Configuration

1. Navigate to the app's setup page in Splunk Web
2. Enter your AWS access key ID and secret access key
3. Specify the AWS regions you want to monitor
4. Save the configuration

## Usage

After installation and configuration, you can access the app's dashboards and alerts from the Splunk Web interface:

1. Go to "Apps" > "Splunk App for AWS Cloud Security Monitoring"
2. Use the navigation menu to access different dashboards and alert configurations

## Dashboards

- Overview: High-level summary of AWS security events
- IAM Activity: User and role activity monitoring
- Network Security: VPC and security group changes
- Data Access: S3 bucket and database access logs
- Compute Security: EC2 instance and container security events

## Alerts

- Unauthorized API calls
- Root account usage
- IAM policy changes
- Network ACL and security group modifications
- Large data transfers
- Unusual instance launches or terminations

## Contributing

We welcome contributions to improve this Splunk app. Please submit pull requests or open issues on our GitHub repository.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Support

For support, please open an issue on GitHub or contact our support team at support@example.com.