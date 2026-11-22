# URBANCARE Site Reports V3.4 — Client selection

Retains all six condition-report templates, Task Completion Reports, photo capture and annotation, PDF export and owner portrait.

New: a client selector in BOTH report forms. Save a report with a client name to create/update its local client directory entry. Later reports can select that client to populate name, contact, site address, and optional email address and internal notes. The PDF omits the private client email and internal follow-up notes.

Client directory and reports exist on the same device/browser only and do not sync with ChatGPT/Outlook. The Export backup JSON now includes the client directory; importing also supports completion reports. Do not store highly sensitive information in client notes.

To deploy: upload index.html, lukasz-portrait.png, and urbancare-wordmark.png to the GitHub repository root on main. Keep the CNAME file. Test on your phone before client use.
