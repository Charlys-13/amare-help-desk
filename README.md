# AMARE Help Desk

Proyecto React + Vite preparado para GitHub Pages y Supabase.

## Local
1. Copia `.env.example` a `.env.local`.
2. Coloca la URL y Publishable Key de Supabase.
3. Ejecuta `npm install` y `npm run dev`.

## Supabase
Ejecuta `supabase.sql` en SQL Editor. Antes de producción configura políticas RLS apropiadas para tus usuarios.

## GitHub Pages
Repositorio previsto: `amare-help-desk`. En Settings > Pages selecciona GitHub Actions. Agrega los secrets `VITE_SUPABASE_URL` y `VITE_SUPABASE_PUBLISHABLE_KEY`.
