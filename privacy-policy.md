# Privacy Policy — Standup Scribe

**Effective date:** November 25, 2026
**Developer:** Abhishek Phukan (individual developer)
**Support contact:** lenevo02487@gmail.com

Standup Scribe is an app for Jira Cloud built on the Atlassian Forge platform. This policy explains, in plain language, what the app does with your data.

## How the app runs

Standup Scribe runs entirely inside Atlassian Forge, on your own Jira site, under Atlassian's infrastructure and security model. The developer does not operate any server that the app talks to.

## What happens to the text you paste

- When you paste standup notes or a meeting transcript into Standup Scribe and click "Create digest", the text is processed inside the Forge environment of your Jira site for one purpose only: generating the per-person digest shown back to you.
- The standup text you paste is **not transmitted to, and not stored on, any external server controlled by the developer**.
- The developer never sees your standup text, your digest output, or the contents of your Jira issues.

## Jira data the app reads

- With your site's permission (Forge scopes `read:jira-work` and `read:jira-user`), the app may look up the Jira issues mentioned in your text (for example, `KAN-1`) through the Jira API, acting as the signed-in user.
- Only the issue's title and status are read, and only to enrich the digest (so a ticket key can be shown with its real title and status).
- This lookup is read-only. The app never creates, edits, comments on, or deletes Jira issues.

## Analytics and tracking

- The app does **not** collect analytics, usage metrics, or tracking data of any kind.
- The app contains no advertising and no third-party trackers.
- The app does not sell, share, or disclose any data to third parties, because the developer receives no data from the app in the first place.

## Data retention

Because the digest is generated inside your Jira site and is not sent to the developer, there is no user data for the developer to retain or delete.

## Uninstalling

You can uninstall Standup Scribe from your Jira site at any time (Jira settings → Apps). Uninstalling removes the app and its access to your site immediately.

## Changes to this policy

If this policy changes, the updated version will be published with a new effective date before the change takes effect.

## Contact

Questions about this policy: **lenevo02487@gmail.com**
