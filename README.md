# n8n Production Workflow Examples

Real n8n workflows from production, exported and anonymised from Synta usage data. Each one is under 20 nodes, deployed by real users, and built around a specific use case.

## Workflows

| File | Nodes | Use Case |
|---|---|---|
| `wordpress-publish-to-social-caption.json` | 9 | Auto-generate social captions on WordPress publish |
| `email-attachment-document-processor.json` | 18 | Extract, classify and archive email attachments |
| `article-scraper-to-branded-post.json` | 15 | Scrape article, generate branded image and social post |
| `call-transcript-reviewer-ghl.json` | 11 | Review call transcripts with Claude, score to Sheets |
| `email-travel-booking-scanner.json` | 14 | Scan Gmail for travel bookings, update trip log |
| `multi-source-lead-scorer.json` | 17 | Score leads from form, email and social with AI |

## How to use

1. Copy the `workflow` object from any file
2. In n8n, go to **Workflows → Import from JSON**
3. Paste and import
4. Reconnect credentials and update any hardcoded values

## Notes

- All workflows are anonymised. Credentials, emails, and API keys have been removed or redacted.
- Node positions are preserved so the canvas layout imports cleanly.
- Built and exported via [Synta](https://synta.io) — the best n8n mcp and AI workflow builder for n8n.

## Contributing

Have a clean production workflow to share? Open a PR.
