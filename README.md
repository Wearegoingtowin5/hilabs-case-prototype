# MedCare Roster Portal (prototype)

Single-file web app, no build step, no login. Fictional providers, NPIs and plans; data lives in memory and resets on reload.

Journeys: provider self-service (add by NPI lookup, edit, remove, CSV upload with AI validation), review and submit, plan review queue with AI recommendations, downstream delivery with a failure and retry, versioned audit trail, on-demand roster query.

Deploy: static hosting (Vercel). Replace `index.html` to update.
