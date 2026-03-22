# Recontrol - Submission Materials

This folder contains all legal documents and store listing materials required for submitting Recontrol to the Apple App Store and Google Play Store.

---

## Contents

| File | Description |
|------|-------------|
| `TERMS_OF_SERVICE.md` | Full Terms of Service document |
| `PRIVACY_POLICY.md` | Full Privacy Policy document (GDPR, CCPA/CPRA, LGPD compliant) |
| `APPLE_APP_STORE_LISTING.md` | App Store listing: name, subtitle, promotional text, description, keywords, nutrition labels guide |
| `GOOGLE_PLAY_STORE_LISTING.md` | Play Store listing: title, short description, full description, data safety declarations, financial features declaration |

---

## Placeholders to Fill In Before Submission

Search for `[INSERT` across all files to find placeholders that need real values:

| Placeholder | Where Used | What to Fill In |
|-------------|-----------|-----------------|
| `[INSERT DATE]` | ToS, PP | Effective date of each document |
| `[INSERT LEGAL ENTITY NAME]` | PP | Your registered company/legal entity name |
| `[INSERT CONTACT EMAIL]` | ToS, PP | General contact or support email address |
| `[INSERT DPO EMAIL]` | PP | Data Protection Officer email (if applicable, required under GDPR if you meet the threshold) |
| `[INSERT MAILING ADDRESS]` | ToS, PP | Physical mailing address of the company |
| `[INSERT DATA DELETION URL]` | ToS, PP, Play Store | URL where users can request data deletion via the web |
| `[INSERT DATA RIGHTS REQUEST URL]` | PP | URL for submitting data rights requests (can be same as deletion URL) |
| `[INSERT PRIVACY POLICY URL]` | ToS | Public URL where the privacy policy is hosted |
| `[INSERT WEBSITE URL]` | ToS | Company or app website URL |
| `[INSERT CITY, STATE]` | ToS | City and state for arbitration venue |
| `[INSERT STATE/COUNTRY]` | ToS | Governing law jurisdiction |
| `[INSERT COUNTRY]` | ToS | Country for international users clause |
| `[INSERT COUNTRY WHERE SERVERS ARE LOCATED]` | PP | Where Nhost/AWS servers are located (check your Nhost project's AWS region) |
| `[INSERT AWS REGION]` | PP | Specific AWS region, e.g., "US East (N. Virginia)" or "EU (Frankfurt)" |
| `[INSERT OPEN-SOURCE LICENSES URL]` | ToS | URL or in-app location listing open-source library licenses |

Other values will also need adjusting (eg: using your company as you need, etc) but those should be quite evident with a read through.

---

## Pre-Submission Checklist

### Legal Documents
- [ ] Fill in ALL placeholders listed above
- [ ] Have the ToS and PP reviewed by a qualified attorney
- [ ] Host the Privacy Policy at a publicly accessible, stable URL (not a PDF, not geo-blocked)
- [ ] Host the Terms of Service at a publicly accessible, stable URL
- [ ] Ensure both documents are accessible within the app (e.g., in Settings)
- [ ] Ensure the Privacy Policy URL works and is not geo-blocked
- [ ] Verify the data deletion web URL is functional and accessible without login

### Apple App Store
- [ ] Add Privacy Policy URL in App Store Connect
- [ ] Complete App Privacy questionnaire (nutrition labels) -- use the guide in `APPLE_APP_STORE_LISTING.md`
- [ ] **Only declare data types actually collected on the client side** (see notes in the listing file)
- [ ] Include `PrivacyInfo.xcprivacy` manifest in the iOS build
- [ ] Verify account deletion works in-app
- [ ] Set age rating to 4+
- [ ] Set primary category to Finance
- [ ] Upload screenshots and preview video
- [ ] Enter all metadata (name, subtitle, keywords, description, promotional text)
- [ ] Include open-source license acknowledgments in the app (required by BSD/MIT/Apache licenses)

### Google Play Store
- [ ] Add Privacy Policy URL in Play Console
- [ ] Complete Data Safety form -- use the guide in `GOOGLE_PLAY_STORE_LISTING.md`
- [ ] **Only declare data types actually collected on the client side** (see notes in the listing file)
- [ ] Complete Financial Features Declaration
- [ ] Complete Data Deletion questions (provide in-app and web deletion URL)
- [ ] Verify account deletion works in-app and via web URL
- [ ] Set content rating to Everyone
- [ ] Set category to Finance
- [ ] Upload screenshots and feature graphic (1024x500)
- [ ] Enter all metadata (title, short description, full description)
- [ ] Ensure 20 closed testers have tested the app (required for new apps)
- [ ] Include open-source license acknowledgments in the app

---

## Important Notes

1. **Attorney Review:** While these documents are comprehensive and follow current platform requirements and applicable privacy regulations, they should be reviewed by a qualified attorney at some later point, particularly regarding the arbitration clause, governing law, and jurisdiction-specific compliance.

2. **Data Deletion:** Both stores require a working data deletion mechanism. Ensure the web-based deletion URL is functional before submission. Google Play also requires that the URL be accessible outside the app.

3. **No Data Selling:** The ToS and PP explicitly state that Recontrol does not sell user data. If this ever changes, both documents must be updated, and users must be notified and given the opportunity to consent.

4. **Financial Disclaimers:** The ToS includes strong disclaimers that Recontrol is not a financial advisor. This is critical for a finance app to avoid regulatory issues.

5. **Hosting:** Both the ToS and PP should be hosted on your website (not just in-app) so they can be linked from the store listings. They should be available without requiring a login.

6. **Open-Source License Considerations:** The Recontrol codebase is publicly available under the BSD 3-Clause License. The ToS (Section 8.6) explicitly distinguishes between the open-source source code and the hosted Service/compiled App. This is intentional -- the ToS governs use of the hosted Service and compiled App distributed through stores, while the BSD license governs the source code. Make sure the open-source license acknowledgments page is accessible in-app (many open-source licenses require this).

7. **Data Collection Accuracy (Critical for Store Approval):** The store declaration guides have been updated with notes about what to declare vs. what NOT to declare. The app currently does NOT have a client-side analytics or crash reporting SDK. If you add one in the future (e.g., Sentry, Crashlytics, PostHog), you MUST update the Privacy Policy, the Apple Nutrition Labels, and the Google Data Safety form accordingly. The #1 rejection reason on Google Play is mismatched declarations between actual app behavior and the Data Safety form.

8. **Data Breach Notification:** The Privacy Policy includes a data breach notification procedure (Section 8.1) as required by GDPR. Make sure your team has an internal incident response plan that can meet the 72-hour notification deadline.

9. **EU Consumer Protection:** The ToS (Section 16.6) explicitly carves out EU/UK consumers from binding arbitration and class action waivers, as these provisions are generally unenforceable under EU consumer protection law. This was done deliberately to avoid legal challenges.
