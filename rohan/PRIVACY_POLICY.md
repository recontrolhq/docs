# Privacy Policy

**Effective Date:** [INSERT DATE]
**Last Updated:** [INSERT DATE]

---

## 1. Introduction

Recontrol ("we," "us," "our," or the "Company") is committed to protecting your privacy. This Privacy Policy explains how we collect, use, disclose, retain, and safeguard your personal information when you use the Recontrol mobile application (the "App") and all related services (collectively, the "Service").

This Privacy Policy applies to all users of the Service, regardless of how you access it (mobile application, web application, or any other platform).

Please read this Privacy Policy carefully. By accessing or using the Service, you acknowledge that you have read and understood this Privacy Policy. This Privacy Policy describes our data practices; the legal bases for our processing of your personal data are set forth in Section 5. If you do not agree with our data practices as described in this Privacy Policy, you should not access or use the Service.

---

## 2. Who We Are

Recontrol is a personal and collaborative finance management application that helps users track accounts, record transactions, manage budgets, set financial goals, and collaborate with others in shared workspaces.

**Data Controller Contact Information:**

- **Company Name:** [INSERT LEGAL ENTITY NAME]
- **Email:** [INSERT CONTACT EMAIL]
- **Mailing Address:** [INSERT MAILING ADDRESS]
- **Data Protection Officer (if applicable):** [INSERT DPO EMAIL]

If you are a resident of the European Economic Area (EEA), the United Kingdom, or Switzerland, we are the data controller responsible for your personal data.

---

## 3. Information We Collect

We collect the following categories of information:

### 3.1 Information You Provide Directly

| Data Type | Details | Purpose |
|-----------|---------|---------|
| **Account Registration Information** | Email address, display name, password | Account creation and authentication |
| **Phone Number** (optional) | Phone number, if provided for passwordless SMS login or MFA | Authentication and account security |
| **Financial Account Data** | Account names, account types (asset, liability, income, expense, equity), account balances | Core Service functionality |
| **Transaction Data** | Transaction amounts, descriptions, timestamps, source and destination accounts, labels/categories, bookmark status | Core Service functionality |
| **Space Information** | Space names and organizational data | Collaborative workspace management |
| **Label Data** | Custom category labels you create | Transaction categorization |
| **Currency Preference** | Your selected display currency (ISO 4217 format) | Display and formatting preferences |
| **Communication Data** | Content of messages you send to us (support requests, feedback) | Customer support and Service improvement |

### 3.2 Information Collected Automatically

| Data Type | Details | Purpose |
|-----------|---------|---------|
| **Authentication Tokens** | JSON Web Tokens (JWT), access tokens, refresh tokens | Session management and authentication |
| **Session Information** | Session identifiers, login timestamps | Security and session management |
| **Basic Request Metadata** | IP address, user-agent string (which may include device type, operating system, and app version), request timestamps | Server operation, security monitoring, and debugging. This data is collected as part of standard server request processing. |
| **Server-Side Operational Data** | Backend performance metrics, API response times, server error logs | Infrastructure monitoring, service reliability, and debugging. This data is collected through server-side observability tools (OpenTelemetry, Prometheus) and pertains to server operations, not individual user behavior tracking. |

**Note:** The App does not currently integrate client-side analytics SDKs, crash reporting SDKs, or user behavior tracking tools. We do not track which screens you visit, which buttons you tap, or how you navigate the App. The operational data described above is collected on the server side as part of standard infrastructure monitoring.

### 3.3 Information We Do NOT Collect

We want to be transparent about data we do **not** collect:

- **Location Data:** We do not collect precise or approximate location data.
- **Contacts:** We do not access your device contacts or address book.
- **Photos or Media:** We do not access your camera, photo library, or media files.
- **Microphone or Audio:** We do not access your microphone or record audio.
- **Health or Fitness Data:** We do not collect any health or fitness information.
- **Browsing History:** We do not track your web browsing history outside the App.
- **Advertising Identifiers:** We do not collect advertising identifiers (IDFA/GAID) or track you across other apps or websites.
- **Bank Credentials:** We do not collect or store your bank login credentials, credit card numbers, or other payment instrument details. Recontrol is a manual financial tracking tool; it does not connect to your bank accounts.
- **Biometric Data:** We do not collect fingerprint, facial recognition, or other biometric data.

---

## 4. How We Use Your Information

We use the information we collect for the following purposes:

### 4.1 Providing and Operating the Service

- Creating and managing your user account;
- Authenticating your identity and managing sessions;
- Enabling you to create, view, edit, and delete financial accounts, transactions, labels, and Spaces;
- Enabling collaboration features, including Space memberships, role-based access control, and permission management;
- Processing your currency preference for display formatting;
- Providing customer support.

### 4.2 Improving the Service

- Analyzing usage patterns to improve functionality and user experience;
- Identifying and fixing bugs, errors, and performance issues;
- Developing new features based on aggregated usage trends.

### 4.3 Security and Fraud Prevention

- Detecting and preventing unauthorized access, fraud, and abuse;
- Monitoring for security threats and vulnerabilities;
- Enforcing our Terms of Service.

### 4.4 Legal Compliance

- Complying with applicable laws, regulations, legal processes, or enforceable governmental requests;
- Protecting our legal rights, privacy, safety, or property;
- Responding to lawful requests from public authorities, including national security or law enforcement requirements.

### 4.5 Communication

- Sending you essential service communications (account verification, security alerts, Terms/Privacy Policy updates);
- Responding to your inquiries and support requests.

**We do not use your personal information for advertising, marketing to third parties, or building advertising profiles. We do not sell your personal information.**

---

## 5. Legal Basis for Processing (EEA, UK, and Switzerland Users)

If you are located in the European Economic Area, the United Kingdom, or Switzerland, we process your personal data based on the following legal grounds:

| Legal Basis | Processing Activities |
|-------------|----------------------|
| **Performance of a Contract** (GDPR Art. 6(1)(b)) | Account creation, authentication, providing core Service functionality (accounts, transactions, Spaces, labels, currency preferences), session management |
| **Legitimate Interests** (GDPR Art. 6(1)(f)) | Service improvement, analytics, security and fraud prevention, debugging and error resolution. Our legitimate interests do not override your fundamental rights and freedoms. |
| **Legal Obligation** (GDPR Art. 6(1)(c)) | Compliance with applicable laws and regulations, responding to legal processes, tax and regulatory record-keeping |
| **Consent** (GDPR Art. 6(1)(a)) | Any optional data collection beyond what is necessary for the Service. You may withdraw your consent at any time without affecting the lawfulness of processing prior to withdrawal. |

---

## 6. How We Share Your Information

### 6.1 Service Providers

We share your information with the following categories of third-party service providers who process data on our behalf:

| Service Provider | Data Shared | Purpose |
|-----------------|-------------|---------|
| **Nhost** (Backend-as-a-Service) | Account data, authentication data, session tokens, email address, display name, phone number, financial data stored in the database | Authentication, user management, database hosting (PostgreSQL via Hasura), backend infrastructure. Nhost processes data on our behalf as a data processor. Nhost's infrastructure runs on **Amazon Web Services (AWS)**. |
| **Amazon Web Services (AWS)** (via Nhost) | All data stored and transmitted through the Service | Cloud infrastructure, server hosting, data storage, and processing. Data is stored in the [INSERT AWS REGION, e.g., "US East (N. Virginia)" or "EU (Frankfurt)"] region. |

### 6.2 Collaborative Space Members

When you participate in a shared Space, other members of that Space may see the financial data within that Space (accounts, transactions, labels) in accordance with the permissions assigned to their role. Your display name and email may be visible to other Space members.

### 6.3 Legal Requirements

We may disclose your information if required to do so by law or in the good faith belief that such action is necessary to:

- Comply with a legal obligation, court order, or legal process;
- Protect and defend our rights or property;
- Prevent or investigate possible wrongdoing in connection with the Service;
- Protect the personal safety of users of the Service or the public;
- Protect against legal liability.

### 6.4 Business Transfers

In the event of a merger, acquisition, reorganization, bankruptcy, or sale of all or a portion of our assets, your personal information may be transferred as part of that transaction. We will notify you via email and/or a prominent notice within the App of any change in ownership or uses of your personal information, as well as any choices you may have regarding your personal information.

### 6.5 With Your Consent

We may share your information with third parties when you have given us explicit consent to do so.

### 6.6 We Do NOT Share Your Information For

- **Advertising or marketing by third parties;**
- **Sale to data brokers;**
- **Building advertising profiles;**
- **Cross-app or cross-site tracking.**

---

## 7. Data Retention

We retain your personal information only for as long as necessary to fulfill the purposes for which it was collected, including to satisfy legal, accounting, or reporting requirements.

| Data Type | Retention Period |
|-----------|-----------------|
| **Account and profile data** | Retained while your account is active. Deleted within 30 days of account deletion request. |
| **Financial data** (accounts, transactions, labels) | Retained while your account is active. Deleted within 30 days of account deletion request. |
| **Authentication tokens** | Tokens are short-lived and expire automatically. Refresh tokens are invalidated upon logout or account deletion. |
| **Session data** | Retained for the duration of the active session. Cleared upon logout. |
| **Server-side operational data** (logs, metrics) | Retained for up to 12 months for infrastructure monitoring and debugging purposes, then automatically deleted or anonymized. This data pertains to server operations and is not linked to individual user profiles. |
| **Support communications** | Retained for up to 24 months after the last communication to enable follow-up and quality assurance. |

**Post-Deletion Retention:** After you delete your account, we may retain certain data in anonymized or aggregated form that cannot be used to identify you. We may also retain data as required by law (e.g., tax or regulatory requirements) for the minimum period mandated by the applicable regulation.

---

## 8. Data Security

We implement appropriate technical and organizational measures to protect your personal information against unauthorized access, alteration, disclosure, or destruction. These measures include:

- **Encryption in Transit:** All data transmitted between the App and our servers is encrypted using TLS (Transport Layer Security) / HTTPS;
- **Encryption at Rest:** Data stored in our databases is encrypted at rest using AES-256 encryption, provided by our cloud infrastructure provider (AWS);
- **Protocol Buffer Serialization:** API communications use binary Protocol Buffer encoding via Connect RPC, which is not human-readable in transit;
- **Secure Credential Storage:** On mobile devices, sensitive credentials (access tokens, refresh tokens) are stored using platform-provided secure storage mechanisms (iOS Keychain / Android Keystore via Expo Secure Store);
- **JWT Authentication:** All API requests are authenticated using signed JSON Web Tokens with server-side validation;
- **Role-Based Access Control:** Collaborative Spaces enforce granular, role-based permissions to restrict data access;
- **Webhook Security:** Server-to-server communications (such as database event webhooks) are secured with secret-based validation;
- **Input Validation:** All API requests are validated using Protocol Buffer schema validation (protovalidate) to prevent malformed or malicious input;
- **Access Controls:** Internal access to user data is restricted to authorized personnel on a need-to-know basis.

**No method of transmission over the Internet or method of electronic storage is 100% secure.** While we strive to use commercially acceptable means to protect your personal information, we cannot guarantee its absolute security. If you become aware of any security breach, please contact us immediately at [INSERT CONTACT EMAIL].

### 8.1 Data Breach Notification

In the event of a personal data breach that is likely to result in a risk to your rights and freedoms, we will:

- **Notify the relevant supervisory authority** within 72 hours of becoming aware of the breach, as required by GDPR Article 33 (for EEA/UK users);
- **Notify affected users without undue delay** where the breach is likely to result in a high risk to individuals' rights and freedoms, as required by GDPR Article 34;
- **Comply with all applicable breach notification laws**, including state-level breach notification requirements in the United States (which vary by state but generally require notification within 30 to 60 days);
- **Provide details** about the nature of the breach, the categories and approximate number of individuals affected, the likely consequences, and the measures taken or proposed to address the breach.

---

## 9. Your Rights and Choices

Depending on your location, you may have the following rights regarding your personal data:

### 9.1 Rights for All Users

- **Access:** Request a copy of the personal data we hold about you;
- **Correction:** Request correction of inaccurate or incomplete personal data;
- **Deletion:** Request deletion of your personal data (see Section 10);
- **Data Export:** Request a copy of your data in a portable format;
- **Withdraw Consent:** Where processing is based on consent, withdraw your consent at any time.

### 9.2 Additional Rights for EEA, UK, and Switzerland Residents (GDPR)

- **Right to Erasure (Right to Be Forgotten):** Request the deletion of your personal data under certain circumstances;
- **Right to Restriction of Processing:** Request that we limit the processing of your personal data;
- **Right to Data Portability:** Receive your personal data in a structured, commonly used, machine-readable format;
- **Right to Object:** Object to processing based on legitimate interests or for direct marketing purposes;
- **Right Regarding Automated Decision-Making:** Not be subject to decisions based solely on automated processing, including profiling, that produce legal or similarly significant effects. We do not currently engage in automated decision-making or profiling;
- **Right to Lodge a Complaint:** You have the right to lodge a complaint with your local data protection supervisory authority. A list of EU data protection authorities is available at https://edpb.europa.eu/about-edpb/about-edpb/members_en.

### 9.3 Additional Rights for California Residents (CCPA/CPRA)

Under the California Consumer Privacy Act, as amended by the California Privacy Rights Act, California residents have the following rights:

- **Right to Know:** Request disclosure of the categories and specific pieces of personal information we have collected about you, the categories of sources, the business or commercial purposes for collection, and the categories of third parties with whom we share your information;
- **Right to Delete:** Request deletion of personal information we have collected from you;
- **Right to Correct:** Request correction of inaccurate personal information;
- **Right to Opt-Out of Sale/Sharing:** We do not sell or share your personal information for cross-context behavioral advertising. Therefore, there is no need to opt out;
- **Right to Limit Use of Sensitive Personal Information:** We only use sensitive personal information (such as financial data) as necessary to provide the Service. We do not use sensitive personal information for purposes beyond those permitted under the CCPA/CPRA;
- **Right to Non-Discrimination:** We will not discriminate against you for exercising any of your CCPA/CPRA rights.

**Categories of Personal Information Collected (past 12 months):**

| CCPA Category | Examples | Sold? | Shared for Cross-Context Behavioral Advertising? |
|---------------|----------|-------|--------------------------------------------------|
| Identifiers | Email address, display name, user ID, phone number | No | No |
| Financial Information | Account data, transaction data, account balances | No | No |
| Internet or Network Activity | App usage data, session information | No | No |
| Inferences | None drawn | N/A | N/A |

**"Do Not Sell or Share My Personal Information":** We do not sell your personal information to third parties. We do not share your personal information for cross-context behavioral advertising purposes.

### 9.4 Additional Rights for Residents of Other U.S. States

Residents of Virginia (VCDPA), Colorado (CPA), Connecticut (CTDPA), Utah (UCPA), Texas (TDPSA), Oregon (OCPA), Montana (MCDPA), and other states with comprehensive privacy laws may have similar rights to those described above, including the rights to access, correct, delete, and opt out of the sale of personal data and targeted advertising. To exercise these rights, please contact us using the information in Section 15.

### 9.5 Additional Rights for Brazilian Residents (LGPD)

Under Brazil's Lei Geral de Proteção de Dados, you have the right to: confirmation of data processing; access to data; correction of incomplete, inaccurate, or outdated data; anonymization, blocking, or deletion of unnecessary data; data portability; deletion of data processed with consent; information about public and private entities with which data is shared; information about the possibility of not providing consent and consequences thereof; and revocation of consent.

### 9.6 How to Exercise Your Rights

To exercise any of the rights described above, you may:

- **Use In-App Settings:** Access your account settings within the App;
- **Submit a Request Online:** Visit [INSERT DATA RIGHTS REQUEST URL];
- **Email Us:** Send a request to [INSERT CONTACT EMAIL].

We will respond to your request within thirty (30) days, or within the timeframe required by applicable law. We may ask you to verify your identity before processing your request to protect your data from unauthorized access.

---

## 10. Account Deletion and Data Erasure

### 10.1 How to Delete Your Account and Data

You have the right to delete your account and all associated personal data at any time. We provide multiple methods:

- **In-App Deletion:** Navigate to Settings within the App and follow the account deletion process;
- **Web-Based Deletion:** Visit [INSERT DATA DELETION URL] to initiate account and data deletion;
- **Email Request:** Send a deletion request to [INSERT CONTACT EMAIL].

### 10.2 What Gets Deleted

Upon processing your deletion request, we will permanently delete:

- Your user account and profile information (email, display name, phone number);
- All financial accounts you created;
- All transactions you recorded;
- All custom labels;
- Your currency preferences and other settings;
- Your Space memberships and role assignments;
- Session tokens and authentication data.

### 10.3 Processing Timeframe

Deletion requests will be processed within **thirty (30) days** of receipt. During this period, your account will be deactivated and inaccessible.

### 10.4 Data That May Be Retained

After account deletion, we may retain limited data only where:

- Required by applicable law, regulation, or legal process (e.g., tax records, regulatory compliance);
- Necessary to resolve pending disputes or enforce our Terms of Service;
- The data has been anonymized or aggregated so that it can no longer identify you.

Any retained data will be stored securely and used only for the permitted purpose. We will clearly inform you if any data must be retained and the reason for such retention.

### 10.5 Written Confirmation of Deletion

You may request written confirmation that your data has been deleted by emailing [INSERT CONTACT EMAIL]. We will provide such confirmation within a reasonable timeframe after the deletion process has been completed.

### 10.6 Effect on Shared Spaces

If you are a member of shared Spaces:

- Your membership will be removed from all Spaces;
- Data you contributed to a shared Space (such as transactions or accounts) may be retained within that Space in anonymized form or attributed to a generic "deleted user" placeholder (containing no identifiable information such as your name, email, or any other personal data) to preserve the integrity of other members' financial records;
- If you are the sole administrator of a Space, you will be prompted to transfer ownership or delete the Space before account deletion can proceed.

---

## 11. Children's Privacy

The Service is not intended for children under the age of sixteen (16). We do not knowingly collect personal information from children under 16. If we become aware that we have collected personal information from a child under 16 without parental consent, we will take steps to delete that information as promptly as possible.

If you are a parent or guardian and believe your child has provided us with personal information, please contact us at [INSERT CONTACT EMAIL] so we can take appropriate action.

---

## 12. International Data Transfers

Your information may be transferred to, stored, and processed in countries other than your country of residence, including [INSERT COUNTRY WHERE SERVERS ARE LOCATED, e.g., "the United States"], where our servers and service providers (Nhost and Amazon Web Services) are located.

If you are located in the EEA, UK, or Switzerland, we ensure that any transfer of personal data to countries outside the EEA/UK is subject to appropriate safeguards, including:

- **Standard Contractual Clauses (SCCs):** We use European Commission-approved Standard Contractual Clauses for data transfers to third countries that have not received an adequacy decision;
- **Adequacy Decisions:** Where applicable, we transfer data to countries that the European Commission has determined provide an adequate level of data protection;
- **Data Processing Agreements:** We enter into data processing agreements with all service providers that process personal data on our behalf.

For more information about the safeguards in place, please contact us at [INSERT CONTACT EMAIL].

---

## 13. Third-Party Services and SDKs

The Service uses the following third-party services:

| Service | Provider | Data Processed | Purpose | Privacy Policy |
|---------|----------|----------------|---------|----------------|
| **Nhost** | Nhost | Email, password (hashed using industry-standard algorithms), display name, phone number, session data, authentication tokens | Authentication, user management, database hosting (PostgreSQL via Hasura) | [https://nhost.io/privacy](https://nhost.io/privacy) |
| **Amazon Web Services (AWS)** | Amazon (via Nhost) | All data stored and transmitted through the Service (encrypted at rest and in transit) | Cloud infrastructure, server hosting, data storage | [https://aws.amazon.com/privacy/](https://aws.amazon.com/privacy/) |

We require all third-party service providers to:

- Process personal data only on our documented instructions;
- Implement appropriate technical and organizational security measures;
- Not use the data for their own purposes;
- Delete or return all personal data upon termination of the service relationship.

We do not integrate third-party advertising SDKs, analytics SDKs that track users across apps, or social media tracking pixels.

---

## 14. Cookies and Tracking Technologies

### 14.1 Mobile Application

The Recontrol mobile application does not use cookies. The App uses the following local storage technologies:

- **Secure Store (Expo Secure Store):** Used to securely store authentication credentials (access tokens and refresh tokens) on your device using platform-native secure storage (iOS Keychain / Android Keystore);
- **AsyncStorage:** Used to persist session state locally on your device for convenience (e.g., remaining logged in between app sessions).

These technologies are strictly necessary for the operation of the Service and are not used for tracking, analytics, or advertising purposes.

### 14.2 Web Application

The Recontrol web application uses the following:

- **Session Storage:** Used to manage your authentication session within a browser tab and enable cross-tab session synchronization;
- **Local Storage:** Used to persist session state across browser sessions.

We do not use third-party tracking cookies, advertising cookies, or analytics cookies on the web application.

---

## 15. Contact Us

If you have any questions, concerns, or requests regarding this Privacy Policy or our data practices, please contact us:

- **Email:** [INSERT CONTACT EMAIL]
- **Mailing Address:** [INSERT MAILING ADDRESS]
- **Data Protection Officer:** [INSERT DPO EMAIL] (if applicable)
- **Data Deletion Requests:** [INSERT DATA DELETION URL]

### Response Times

We will respond to all privacy-related inquiries within:

- **30 days** for GDPR requests (extendable by 60 days for complex requests, with notice);
- **45 days** for CCPA/CPRA requests (extendable by an additional 45 days, with notice);
- **15 business days** for LGPD requests;
- **30 days** for all other requests.

---

## 16. Changes to This Privacy Policy

We may update this Privacy Policy from time to time to reflect changes in our practices, technology, legal requirements, or other factors. When we make material changes, we will:

- Update the "Last Updated" date at the top of this Privacy Policy;
- Provide notice within the App (e.g., in-app notification or banner);
- Send an email notification to the address associated with your account for significant changes;
- Where required by applicable law, obtain your consent before the changes take effect.

We encourage you to review this Privacy Policy periodically to stay informed about how we are protecting your information. Your continued use of the Service after the effective date of any updated Privacy Policy constitutes your acceptance of the changes.

---

## 17. California "Do Not Sell or Share" Disclosure

**We do not sell your personal information.** We do not share your personal information for cross-context behavioral advertising purposes. Because we do not engage in these practices, we are not required to offer a "Do Not Sell or Share" opt-out mechanism. However, if you have any questions about our data practices, please contact us at [INSERT CONTACT EMAIL].

---

## 18. Additional State-Specific Disclosures

### Nevada Residents

We do not sell your personal information as defined under Nevada Revised Statutes Chapter 603A. If you are a Nevada resident, you may submit a request to opt out of any potential future sale by emailing [INSERT CONTACT EMAIL].

### Virginia, Colorado, Connecticut, Utah, Texas, Oregon, Montana, and Other State Residents

Residents of states with comprehensive privacy laws may have rights similar to those described in Section 9. We honor all applicable state privacy laws. To exercise your rights, please use the contact information in Section 15.

---

## 19. Data Protection Impact Assessments

Where required by applicable law (such as GDPR Article 35), we conduct Data Protection Impact Assessments (DPIAs) for processing activities that are likely to result in a high risk to the rights and freedoms of individuals. Given the sensitive nature of financial data, we are committed to assessing and mitigating risks associated with the processing of your financial information.

---

## 20. Supervisory Authorities

If you are located in the EEA, UK, or Switzerland and believe that our processing of your personal data infringes applicable data protection law, you have the right to lodge a complaint with your local supervisory authority:

- **EU:** Find your local authority at https://edpb.europa.eu/about-edpb/about-edpb/members_en
- **UK:** Information Commissioner's Office (ICO) at https://ico.org.uk/make-a-complaint/
- **Switzerland:** Federal Data Protection and Information Commissioner (FDPIC) at https://www.edoeb.admin.ch/

We encourage you to contact us first so we can attempt to resolve your concern directly.

---

**By using Recontrol, you acknowledge that you have read and understood this Privacy Policy.**
