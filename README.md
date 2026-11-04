# MotionMint AI

Premium AI video creation platform — first frontend prototype.

## Planned product
- Text-to-video and image-to-video
- AI voiceovers, automatic subtitles and background music
- 720p, 1080p and 4K output choices (where supported by the selected provider)
- 9:16, 16:9 and 1:1 aspect ratios
- Personal video library and customer dashboard
- Admin dashboard for customers, subscriptions, payments, videos and AI usage
- Planned 7-day trial followed by $50/month
- Visa/Mastercard and supported Mobile Money payments
- English interface
- Standalone website and ChatGPT integration using one shared backend

## Current status
`index.html` is a visual frontend prototype. It is **not yet a working video generator**. The Generate button is a placeholder until a secure backend and provider integration are built.

## Preview
Open `index.html` in a browser. No build tools are required for this prototype.

## Build milestones
1. Build a secure backend and asynchronous video job queue.
2. Choose video providers and verify model capabilities and costs.
3. Add authentication, database and private video storage.
4. Add fair-use limits and cost monitoring before offering unlimited plans.
5. Integrate subscription billing and verified payment webhooks.
6. Build the customer video library and protected admin dashboard.
7. Expose the backend through an API and ChatGPT-compatible MCP integration.
8. Deploy and test before accepting subscriptions.

## Security
Never put AI provider keys, database service-role keys, or payment secret keys in browser code or commit them to Git. Store secrets as server-side environment variables.

## Commercial note
The $50/month plan and 7-day trial are product decisions, not an active checkout. "Unlimited" generation must be subject to clearly disclosed fair-use limits and provider constraints.
