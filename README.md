# aws-failed-login-monitor
Cloud Security project using AWS CloudTrail, CloudWatch, and SNS to monitor failed login attempts.
# AWS Failed Login Monitoring

## Objective
Monitor failed login attempts in AWS and get real-time email alerts using CloudTrail, CloudWatch, and SNS.

## Tools Used
- AWS CloudTrail
- AWS CloudWatch Logs & Metric Filters
- AWS SNS (Simple Notification Service)
- IAM Users

## Steps
1. Enabled CloudTrail and ensured logs are delivered to CloudWatch.
2. Created a metric filter for detecting failed authentication events.
3. Configured a CloudWatch alarm to trigger when the metric threshold is exceeded.
4. Subscribed email to SNS topic for notifications.
5. Tested alarm by attempting failed login.

## Screenshots
Added images in `screenshots/` folder showing:
- Metric filter setup
- CloudWatch alarm setup
- Email notification received

## Notes
This project demonstrates hands-on knowledge of AWS security monitoring, useful for entry-level cloud security roles.
