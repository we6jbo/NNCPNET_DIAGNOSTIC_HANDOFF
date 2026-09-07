# General Mail Delivery Failure

Utilities: https://j03.page/utils/

## Symptom

The delivery path failed outside a more specific classified stage.

## Troubleshooting strategy

Trace one new unique marker through client submission, local routing, transport handoff, remote return, local delivery, IMAP visibility, and the active desktop Inbox. Stop at the first checkpoint that cannot prove the marker progressed.

## Normal remediation

Repair only the first failed stage, preserve evidence before changes, and rerun from the beginning with a new unique marker.
