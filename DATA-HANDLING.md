# Data handling and current limits

This is a review disclosure for an unreleased integration, not a promise that
public onboarding or production retention controls are already available.

Decide retains account/connection references, source versions and scoped content,
the exact decision and receipt, approved assignments, immutable read snapshots,
raw returned reference events, verified reports and usage when reported. These
support ownership checks, exact approval and independent verification.

The approved document's text is provided to the connected Grok account for the
bounded extraction. Grok returns references to selected lines; Decide resolves
them from its saved snapshot and independently reads the current Google source.
Supabase stores application state; Composio mediates the application's Google
connection. Render hosts the MCP listener and processes its server requests. Private
Google credentials and native person-session tokens are not given to the Bot.

Results and receipts survive disconnect. Disconnect prevents further Decide
access; it cannot erase content already received by Grok or revoke independent
Grok plugins. Grok plugins/computer resources are account-wide, so a Bot name alone
is not an isolation guarantee. Decide enforces authority at its gateway.

Grok billing and provider review remain independent. Missing cost information is
unknown, not zero. Decide does not promise control of independent Grok spending
or immediate cancellation of its compute.

Consumer account deletion, published retention periods, final privacy/terms pages
and release disclosures are not yet complete. Do not invite consumers or describe
this file as a completed production privacy policy. Support:
[saul@nixnux.org](mailto:saul@nixnux.org).
