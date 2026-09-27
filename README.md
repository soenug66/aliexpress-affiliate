# AliExpress AI Affiliate Site — GitHub Ready

Starter website affiliate dengan storefront, artikel, dashboard generator, kontrak API serverless, dan GitHub Actions.

## Penting
GitHub Pages hanya untuk frontend statis. Jangan pernah menaruh AliExpress API secret atau AI API key di JavaScript browser.

Arsitektur produksi:
GitHub Pages -> Serverless API -> AliExpress / AI -> data/content.

## Setup
1. Upload seluruh folder ke repository GitHub.
2. Push ke branch `main`.
3. Aktifkan GitHub Pages dengan source **GitHub Actions**.
4. Hubungkan endpoint `/api/*` ke Cloudflare Workers, Vercel Functions, Netlify Functions, atau Supabase Edge Functions.
5. Simpan credential di environment secrets serverless.
6. Ganti data demo dan affiliate URL dengan data akun Anda.

## Kontrak API
Lihat `api/README.md`.
