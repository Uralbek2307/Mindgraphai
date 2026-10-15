MemGraph — Multilingual AI Memory MVP
Included
Uzbek / English / Russian landing page
Free / Pro ($12/month) / Business (custom) pricing
Email/Gmail login demo flow
Google sign-in button UI
Onboarding/auth modal
Dashboard, Memory, Knowledge Graph, Ask Memory, Sources, Settings
LocalStorage persistence
TXT/CSV/JSON/MD import
JSON backup
Responsive mobile UI
Netlify
Upload index.html using Netlify manual deploy.
Production authentication
The Google button in this static MVP is a demo flow. Real Google OAuth requires a Google OAuth Client ID and a backend/session or an auth provider. Never expose a production secret/API key directly in frontend code.
Production AI memory
Recommended architecture: Frontend -> Auth -> Backend API -> PostgreSQL/pgvector or Memgraph/Neo4j -> Gemini/OpenAI-compatible model.
