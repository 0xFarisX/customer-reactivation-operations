# Architecture

The application is a Next.js and TypeScript workspace backed by Supabase. Leads,
assignments, touches, callbacks and pipeline states are stored as structured
records. Authentication and manager rules separate caller work from operational
administration. Server routes handle controlled email and summarization actions,
while the interface presents queues, lead workspaces and reporting.

