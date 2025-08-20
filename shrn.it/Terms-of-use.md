# Terms of Use - URL Shrn.it API

**Effective Date:** January 12, 2025  
**API Provider:** Shrn.it API  
**Platform:** RapidAPI Marketplace

## 1. Acceptance of Terms

By subscribing to and using the URL Shrn.it API ("the API") through RapidAPI, you ("User", "You") agree to be bound by these Terms of Use. If you do not agree to these terms, do not use the API.

## 2. API Description

The URL Shrn.it API provides programmatic access to:
- Create shortened URLs with custom or auto-generated codes
- Redirect short URLs to original destinations
- Manage and update existing short links
- Generate QR codes for shortened URLs
- View basic analytics (click counts, creation dates)

## 3. Permitted Use

### 3.1 Acceptable Use
You may use the API for:
- Personal projects and applications
- Commercial applications and services
- Integration into websites, mobile apps, and software
- Automated URL shortening for legitimate business purposes
- Analytics and tracking of your own content

### 3.2 Prohibited Use
You may NOT use the API to:
- Create or distribute malicious links (malware, phishing, scams)
- Shorten URLs to illegal content or services
- Circumvent security measures or access restrictions
- Create spam or unsolicited marketing campaigns
- Violate any applicable laws or regulations
- Abuse the service through automated attacks or excessive requests
- Resell API access without explicit permission
- Mask or hide the final destination of harmful content

## 4. Subscription Plans and Limits

### 4.1 Available Tiers
Subscription plans, quotas, and rate limits are defined on the RapidAPI pricing page. The main quotas are summarized below:

- **BASIC (Free):**
  - **Requests**: 100 / Day (Hard Limit)
  - **Rate Limit**: 1,000 requests / hour
  - **Batch Limit**: 5 URLs / request
  - Other operations are counted towards the daily request quota.
  - Redirects are excluded from daily quota.

- **PRO ($9.99/month):**
  - **Requests**: 250,000 / Month
  - **Rate Limit**: 60 requests / minute
  - **Batch Limit**: 20 URLs / request
  - Other operations are counted towards the monthly request quota.
  - Redirects are excluded from daily quota.

- **ULTRA ($29.99/month):**
  - **Requests**: 10,000 / Day
  - **Redirects & Link Listing**: 1,400,000 / Month
  - **Batch Operations**: 50,000 / Month
  - **Rate Limit**: 100 requests / minute
  - **Batch Limit**: 100 URLs / request
  - Other operations are counted towards the monthly request quota.
  - Redirects are excluded from daily quota.

- **MEGA ($99.99/month):**
  - **Requests**: 65,000 / Day
  - **Redirects & Link Listing**: 3,800,000 / Month
  - **Batch Operations**: 150,000 / Month
  - **Rate Limit**: 200 requests / minute
  - **Batch Limit**: 500 URLs / request
  - Other operations are counted towards the monthly request quota.
  - Redirects are excluded from daily quota.

### 4.2 Quota and Rate Limit Enforcement
- Daily quotas reset at 00:00 UTC. Monthly quotas reset on the first day of the calendar month.
- Rate limits (per minute/hour) are enforced to protect infrastructure integrity.
- Exceeding any limit will result in an HTTP 429 "Too Many Requests" response.
- Overage fees, if applicable to your plan, will be charged by RapidAPI for usage beyond the specified quotas.

## 5. API Key and Security

### 5.1 Authentication
- API access is managed and authenticated by the RapidAPI platform.
- You are responsible for securing your RapidAPI subscription keys.
- All API usage associated with your subscription key is your responsibility.

### 5.2 Security Requirements
- Store API keys securely (e.g., using environment variables or secret management tools). Do not hardcode them in your application's source code.
- Implement proper error handling for API responses, including 4xx and 5xx status codes.
- Use HTTPS for all API communications to ensure data is encrypted in transit.
- Report any suspected security vulnerabilities to our support team immediately.

## 6. Data and Privacy

### 6.1 Data Collection
The API collects and stores:
- Original and shortened URLs
- Creation timestamps and click counts
- Basic request metadata (IP addresses for rate limiting and security)
- User identification as provided by RapidAPI headers for quota management

### 6.2 Data Retention
- Short links remain active indefinitely unless deleted by the user or for a violation of these terms.
- Analytics data is retained for the operational purposes of the service.
- Links and associated data for deleted links cannot be recovered.

### 6.3 Privacy
- We do not sell or share your personal data or the content of your links with third parties, except as required by law.
- We do not access or analyze the content of the destination URLs you shorten.
- We comply with GDPR and other applicable privacy regulations.

## 7. Service Availability

### 7.1 Uptime
- We strive for a 99.9% uptime but do not offer a formal Service Level Agreement (SLA) or guarantee uninterrupted service.
- Scheduled maintenance will be announced in advance whenever possible.
- The service is provided "as is" and "as available" without warranty.

### 7.2 Modifications
- We may update or modify API features to improve the service.
- We will strive to make such changes backward-compatible. Any breaking changes will be communicated in advance with a reasonable deprecation period.

## 8. Content and Compliance

### 8.1 Your Responsibilities
You are solely responsible for:
- The content of the URLs you shorten and distribute.
- Ensuring your use of the API complies with all applicable laws and regulations.
- Respecting intellectual property rights.

### 8.2 Content Removal
We reserve the right, at our sole discretion, to:
- Remove or disable any shortened URL that violates these terms, without notice.
- Suspend or terminate your access to the API for violations.
- Cooperate with law enforcement and report illegal content to the appropriate authorities.

## 9. Liability and Disclaimers

### 9.1 Limitation of Liability
- The API is provided without warranties of any kind, express or implied.
- We are not liable for any indirect, incidental, special, or consequential damages arising from your use of the API.
- Our total liability to you for any claims shall not exceed the total amount of fees you paid to us in the three (3) months preceding the claim.

### 9.2 Indemnification
You agree to indemnify and hold harmless the API provider, its affiliates, and employees from any claims, damages, or expenses arising from your use of the service or your violation of these Terms of Use.

## 10. Billing and Payments

### 10.1 Payment Terms
- All billing and payments are processed exclusively through the RapidAPI Marketplace.
- Subscription fees are billed in advance according to your selected plan's cycle (e.g., monthly).
- All fees are non-refundable, except as required by law or RapidAPI's policies.

### 10.2 Overage Charges
- **PRO**: $0.0005 per request over the monthly limit.
- **ULTRA**:
  - Requests: $0.0002 / request
  - Redirects/Listing: $0.00003 / request
  - Batch Ops: $0.00005 / request
- **MEGA**:
  - Requests: $0.00008 / request
  - Redirects/Listing: $0.00003 / request
  - Batch Ops: $0.00008 / request
- **BASIC**: This is a hard-limit plan. No overages are permitted.

## 11. Termination

### 11.1 User Termination
You may cancel your subscription at any time through the RapidAPI dashboard.

### 11.2 Provider Termination
We may terminate or suspend your access to the API immediately, without prior notice, for:
- A material breach of these Terms of Use.
- Any illegal or harmful use of the service.
- Non-payment of fees as required by RapidAPI.
- Extended periods of inactivity on a free tier.

## 12. Support

### 12.1 Technical Support
- Primary support is provided via support tickets on the RapidAPI platform.
- Comprehensive documentation is available on the API's RapidAPI listing.

### 12.2 Service Level
- **BASIC**: Community support (we aim to respond but provide no guarantee).
- **PRO**: 48-hour response time SLA.
- **ULTRA**: 24-hour response time SLA.
- **MEGA**: Priority support with a 12-hour response time SLA.

## 13. Changes to Terms

We reserve the right to modify these terms at any time. We will notify users of significant changes via the RapidAPI platform. Continued use of the API after such changes constitutes your acceptance of the new terms.

## 14. Governing Law

These terms are governed by the laws of the European Union, without regard to its conflict of law principles.

## 15. Contact Information

For questions about these Terms of Use, please contact us through the RapidAPI platform's support messaging system.
- **Email for legal notices**: `legal@shrn.it` (placeholder, please update)
- **API Status Page**: `status.shrn.it` (placeholder, please update)

## 16. RapidAPI Marketplace Terms

In addition to these terms, your use of the API is also subject to RapidAPI's own Terms of Service and policies, which take precedence in case of any conflict.

---

**By using this API, you acknowledge that you have read, understood, and agree to be bound by these Terms of Use.**

*Last Updated: August 20, 2025*
*Version: 1.1.0*
