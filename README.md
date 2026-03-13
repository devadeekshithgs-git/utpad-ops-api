# Utpad Ops API (Supabase-backed)

This API now persists ops data in Supabase instead of in-memory arrays.

## Required env

- `SUPABASE_URL`
- `SUPABASE_PROJECT_REF`
- `SUPABASE_PUBLISHABLE_KEY`
- `SUPABASE_SECRET_KEY`

Use `.env.example` as template.

## Run

```bash
npm install
npm run start
```

## Endpoints

- `POST /api/v1/ops/events`
- `GET /api/v1/ops/events`
- `GET /api/v1/ops/events/stream`
- `GET /api/v1/ops/workers`
- `POST /api/v1/ops/workers`
- `PATCH /api/v1/ops/workers/:workerId/access`
- `PATCH /api/v1/ops/workers/:workerId/active`
- `GET /api/v1/ops/supabase/config`