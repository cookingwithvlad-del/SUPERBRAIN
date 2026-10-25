# Plugins

The "failed to connect" errors in Claude Code cloud sessions come from connectors bundled inside plugins (HubSpot, PagerDuty, Datadog, Honeycomb and others). The cloud network blocks those hosts. My real accounts are fine. Removing unused plugins clears most of the errors.

| Plugin | Call | Useful parts |
| --- | --- | --- |
| Marketing | Keep | content-creation, campaign-plan, brand-review, competitive-brief |
| Small Business | Keep | social-content-engine, content-strategy, proposal-builder, invoice-chase, restock, inventory-planner |
| Canva | Keep | resize-for-social-media, bulk-create, brand-check |
| Postiz | Keep | Social scheduling |
| FFmpeg | Keep | Batch video conversions for the local video editor |
| Desktop Commander | Keep | Working in folders on my computer |
| Productivity | Optional | Overlaps Notion |
| Design, Figma | Optional | Only if designing in Figma |
| Engineering, Honeycomb, Sanity, Data | Remove | Software and analytics tooling |
| Finance (SOX, journal entries) | Remove | Corporate accounting |
| Bitcoin companies, Stock valuation (CN), Alexandria | Remove | Off-topic |

To allow a blocked host in cloud sessions: Project settings → Cloud environment → Add cloud environment → Allowed domains. Docs: https://code.claude.com/docs/en/cloud-environments#network-access
