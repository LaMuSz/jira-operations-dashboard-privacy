# Privacy Policy for JIRA Operations Dashboard – Inter Cars Bulgaria

**Last updated: October 7, 2026**

## 1. Introduction

JIRA Operations Dashboard – Inter Cars Bulgaria ("the Extension") is an internal productivity tool intended for authorized Inter Cars Bulgaria users.

The Extension provides department-specific dashboards and tools for viewing and managing Jira Service Management requests and supporting related operational workflows.

The Extension currently includes functionality for multiple Inter Cars Bulgaria operational areas, including FSO, PM – Service Equipment, and PM – Aftermarket.

This Privacy Policy explains what information the Extension accesses, how that information is used, how it is stored, and which external services are involved in providing the Extension's functionality.

## 2. Information Accessed and Processed

The Extension may access and process information necessary to provide its Jira-related and operational functionality.

Depending on the Jira request, selected department, Support Group, and workflow, this information may include:

- Jira issue and request information;
- Jira issue keys and statuses;
- Jira request types;
- Jira comments;
- Jira attachments and attachment metadata;
- Jira user names and account information made available through Jira;
- Assignee and ticket creator information;
- Customer and operational information contained in Jira requests;
- Branch information;
- Article numbers;
- Wrong or substituted article numbers;
- Quantities;
- Manufacturer information;
- Order-related information;
- Department-specific operational information;
- Information required for creating or updating Jira requests;
- Information used to prepare user-initiated email drafts;
- Jira configuration information required to display dynamically configured fields;
- A Jira API token supplied by the user.

The Extension accesses and processes this information only when required to provide its intended operational functionality.

## 3. Authentication Information

Users may provide their own Jira API token to allow the Extension to communicate with the authorized Inter Cars Jira environment.

The Jira API token is stored locally using Chrome's extension storage functionality.

The Extension does not send the Jira API token to a developer-operated server and does not use it for purposes unrelated to accessing the Jira services required by the Extension.

For specific Jira configuration requests, the Extension may also reuse the user's existing authenticated Jira browser session on the authorized Jira domain.

This session-assisted functionality is used only when required to obtain Jira configuration information necessary for Extension features, such as dynamically configured field values.

The Extension does not collect, extract, store, or transmit the user's Jira password.

The Extension does not transmit Jira session credentials to a developer-operated server.

Users are responsible for protecting their Jira credentials, browser sessions, and access tokens in accordance with their organization's security policies.

## 4. Local Storage

The Extension uses Chrome local storage to retain settings and operational configuration required for its functionality.

Locally stored information may include:

- Jira connection configuration;
- Jira API token;
- Selected department;
- Selected Support Group;
- Dashboard preferences;
- Column configuration;
- Column widths and ordering;
- Extension settings;
- Department-specific preferences;
- Locally maintained workflow configuration;
- Notification-related settings;
- Ticket overdue threshold settings;
- Quick-reply templates;
- Quick-reply titles and message bodies;
- References between related Jira requests where required by Extension functionality;
- Other user-configured dashboard and workflow preferences.

This information is stored locally in the user's Chrome browser profile.

Locally stored quick-reply templates remain available between browser sessions and normal Extension updates unless the Extension is removed, Chrome extension storage is cleared, or the user deletes or changes the stored settings.

The Extension does not operate an independent external database or developer-operated backend for storing these settings.

## 5. Jira Communication

The Extension communicates with the authorized Inter Cars Jira environment at:

`https://jira.intercars.eu/`

This communication is necessary to perform functions such as:

- retrieving Jira requests;
- displaying ticket information;
- retrieving request types;
- retrieving statuses and comments;
- retrieving attachments and attachment metadata;
- assigning Jira requests;
- changing Jira request statuses;
- adding public Jira comments;
- creating related Jira requests;
- retrieving manufacturer, article, quantity, order, branch, and other operational information;
- retrieving Jira configuration information required for dynamically configured fields;
- supporting department-specific operational workflows.

Actions that modify Jira data are performed as part of the Extension's intended functionality and use the Jira access rights of the authenticated user.

The Extension does not perform unrelated Jira actions outside its intended operational workflows.

## 6. Jira Session Bridge

For specific Jira configuration data, the Extension may inject its own packaged script into an already open and authenticated `jira.intercars.eu` browser tab.

This functionality allows the Extension to reuse the user's existing authenticated Jira session for authorized configuration requests that cannot be performed using the Extension's standard Jira API workflow.

The injected code:

- is included inside the Extension package distributed through the Chrome Web Store;
- is executed only for the authorized `jira.intercars.eu` environment;
- is used only for Extension functionality;
- does not load remotely hosted executable code;
- does not collect or transmit the user's Jira password;
- does not transmit Jira session credentials to a developer-operated server.

## 7. Quick Replies and Comments

The Extension may allow users to create reusable quick-reply templates for Jira comments and status-change workflows.

Quick replies may contain:

- a user-defined title;
- a user-defined message body.

Quick-reply templates are stored locally in Chrome extension storage.

Selecting a quick reply only inserts its text into the relevant comment field.

The Extension does not automatically submit the selected quick reply.

The user may review and edit the text before manually submitting the Jira comment or completing the related Jira action.

The text is transmitted to Jira only when the user performs the relevant action.

## 8. Ticket Notifications and Overdue Indicators

The Extension may provide browser notifications for relevant Jira ticket activity.

Notifications are generated as part of the user's Jira operational workflow and are not used for advertising, profiling, or unrelated purposes.

The Extension may also calculate whether a ticket has exceeded a user-configured time threshold.

The configured overdue threshold is stored locally.

Ticket age and overdue time may be displayed directly in the dashboard to assist users with operational prioritization.

## 9. Attachments and Downloads

The Extension may display and process Jira attachment metadata.

When a user explicitly interacts with an attachment, the Extension may:

- preview supported image formats;
- preview supported PDF files;
- initiate a download for other file types.

Certain file types, including potentially unsafe content such as HTML or SVG files, may be downloaded instead of being rendered inside the Extension's privileged context.

Attachment downloads are initiated only by the user and are not performed automatically.

## 10. Email and Outlook Functionality

The Extension may provide functionality for preparing user-initiated email drafts based on operational information from Jira requests.

For this functionality, the Extension may interact with supported Microsoft Outlook web domains.

The Extension may use Jira ticket information to prepare email subject lines and message content as part of the user's operational workflow.

The Extension does not automatically send email messages.

The user remains responsible for reviewing and sending prepared email drafts.

The Extension does not use email content for advertising, profiling, or unrelated purposes.

## 11. Personal Information

Jira requests may contain information that can identify individuals, such as:

- names;
- usernames;
- email addresses;
- Jira account information;
- customer information;
- other information entered into Jira by authorized users.

The Extension processes such information only when it is present in Jira data required to provide the requested dashboard or workflow functionality.

The Extension does not use this information to build advertising profiles or for purposes unrelated to its operational Jira functionality.

## 12. Personal Communications

The Extension may process Jira comments and information used to prepare email communications when these are required for its operational workflows.

Such information is used only to provide the relevant Extension functionality.

The Extension does not use personal communications for advertising, profiling, or unrelated analytics.

## 13. Website Content

The Extension may process content obtained from authorized Jira services when necessary to:

- display Jira requests;
- organize and filter ticket information;
- search operational data;
- display Jira comments;
- display attachment information;
- retrieve configuration data;
- perform authorized Jira actions;
- prepare user-initiated operational outputs.

The Extension does not collect users' general browsing history.

The Extension does not monitor unrelated websites.

The Extension interacts only with supported services required for its intended functionality.

## 14. Data Sharing and Sale

The Extension does not sell user data.

The Extension does not transfer user data to third parties for:

- advertising;
- marketing;
- data brokerage;
- profiling;
- creditworthiness assessment;
- lending purposes;
- other unrelated purposes.

Information is transmitted only when necessary to communicate with services required for the Extension's intended functionality, including:

- the authorized Inter Cars Jira environment;
- supported Microsoft Outlook web services used by the user.

The Extension does not operate a developer-controlled service that receives copies of Jira ticket content, Jira comments, quick replies, Jira API tokens, or Jira session credentials.

## 15. Advertising and Analytics

The Extension does not contain advertising.

The Extension does not use user data for targeted advertising.

The Extension does not use third-party advertising trackers.

The Extension does not use user data to determine creditworthiness or for lending purposes.

The Extension does not monitor general browsing activity.

Operational telemetry, if enabled in a released version of the Extension, is used only for understanding Extension usage and improving the Extension's functionality and is not used for advertising or user profiling.

## 16. Remote Code

The Extension does not execute remotely hosted JavaScript or WebAssembly code.

Executable code required by the Extension is included within the Extension package distributed through the Chrome Web Store.

The Jira session bridge used by the Extension is also included within the Extension package.

Communication with Jira and supported web services consists of data and API requests required to provide Extension functionality.

The Extension does not download or execute remote executable code.

## 17. Data Retention

Configuration and other locally stored information remain in the user's Chrome extension storage until:

- it is changed by the user;
- it is removed by the user;
- the Extension's storage is cleared;
- the Extension is uninstalled;
- Chrome removes the stored data according to its own storage behavior.

Normal Extension updates do not intentionally delete locally stored settings.

Data stored within Jira, Outlook, or other organizational services is subject to the retention policies of those respective services and Inter Cars.

## 18. Security

The Extension limits its access to the services and information required for its operational functionality.

Communication with supported Jira and Outlook services is performed over HTTPS.

Access to Jira information is subject to the permissions associated with the authenticated user's Jira account.

The Extension does not attempt to bypass Jira permissions or organizational access controls.

Jira API tokens and Extension settings are stored locally using Chrome extension storage.

The Extension does not transmit Jira passwords or Jira authentication tokens to a developer-operated backend.

## 19. Chrome Extension Permissions

The Extension may request Chrome permissions required to provide its functionality.

These may include:

- `storage` – used to save Extension settings, Jira configuration, dashboard preferences, quick replies, and workflow configuration locally;
- `notifications` – used to display relevant Jira workflow notifications;
- `downloads` – used for user-initiated Jira attachment downloads;
- `scripting` – used to inject the Extension's packaged Jira session bridge into the authorized Jira environment when required;
- host permissions – used to communicate with the authorized Inter Cars Jira environment and supported Outlook web services.

These permissions are used only for the Extension's stated operational purpose.

## 20. Limited Use

User data accessed by the Extension is used only to provide or improve the Extension's user-facing Jira operational functionality.

The Extension does not use or transfer user data for purposes unrelated to its stated single purpose.

The Extension does not sell user data.

The Extension does not use user data for advertising, creditworthiness assessment, or lending purposes.

The Extension does not use user data for unrelated profiling.

## 21. Changes to This Privacy Policy

This Privacy Policy may be updated when Extension functionality, permissions, integrations, or data-handling practices change.

The latest version of this Privacy Policy will be published on this page.

## 22. Contact

For questions regarding this Privacy Policy or the JIRA Operations Dashboard – Inter Cars Bulgaria Extension, please contact:

**Inter Cars Bulgaria – JIRA Operations Dashboard**  
**Email:** icbgextensions@gmail.com
