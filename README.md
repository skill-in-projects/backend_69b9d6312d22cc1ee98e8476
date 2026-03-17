# SafePath - Backend API

## Application Database

**Application DB Connection String:** `postgresql://db_appdb_69b9d6312d22cc1ee98e8476_user:Y%2AoNREp%405XuIEdqanaLY4aBPf5IY%405pI@ep-solitary-thunder-akckxesc.c-3.us-west-2.aws.neon.tech:5432/AppDB_69b9d6312d22cc1ee98e8476?sslmode=require`

## Web API

**WebApi URL:** https://webapi69b9d6312d22cc1ee98e8476-production.up.railway.app

**Swagger API Tester URL:** https://webapi69b9d6312d22cc1ee98e8476-production.up.railway.app/swagger

## Google APIs (Gemini, Maps, Speech-to-Text)

The backend can use a Google API key provided via the **GOOGLE_API_KEY** environment variable (set on Railway). Use it for Gemini LLM, Maps, and Speech-to-Text. Check **GET /api/google/status** and **GET /api/google/health** to verify the key is set and reachable.

## Recommended Tools

**Recommended SQL Editor tool (Free):** [pgAdmin](https://www.pgadmin.org/download/)

## Deployment

This backend is configured for Railway deployment using nixpacks.toml.
