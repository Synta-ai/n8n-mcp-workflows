# n8n MCP Production Workflow Examples

Real n8n workflows from production, exported and anonymised from synta mcp usage data. Each one is deployed by real users and built around a specific use case.

## Workflows

### content-social/
| File | Use Case |
|---|---|
| `wordpress-publish-to-social-caption.json` | Auto-generate social captions on WordPress publish, create branded image, notify via WhatsApp |
| `article-scraper-to-branded-post.json` | Scrape article, generate branded image and social post via Claude |

### lead-generation/
| File | Use Case |
|---|---|
| `multi-source-lead-scorer.json` | Collect leads from form, email and social DMs, score with AI, route hot leads to Slack |
| `call-transcript-reviewer-ghl.json` | Pull call transcripts from Dialpad via GHL webhook, review with Claude, save scored results to Sheets |
| `google-maps-lead-scraper.json` | Scrape Google Maps daily, extract emails from business websites, AI-enrich and score each lead, save to Airtable |

### document-processing/
| File | Use Case |
|---|---|
| `email-attachment-document-processor.json` | Extract, classify and archive email attachments to Google Drive |
| `email-travel-booking-scanner.json` | Scan Gmail hourly for travel bookings, extract with Claude, deduplicate, update trip log |

## How to use

1. Copy the contents of any `.json` file
2. In n8n, go to **Workflows → Import from JSON**
3. Paste and import
4. Reconnect credentials and update any hardcoded values

## Notes

- All workflows are anonymised. Credentials, emails, and API keys have been removed or redacted.
- Node positions are preserved so the canvas layout imports cleanly.
- Built and exported via [Synta](https://synta.io) — the best n8n mcp and AI workflow builder for n8n.

## Contributing

Have a clean production workflow to share? Open a PR.
