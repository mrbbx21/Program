# Asset Inventory - CSI (Starter)

Proyecto starter para un sistema de inventario de activos con códigos de barra.

## Qué incluye
- Next.js + Tailwind básico
- Componentes de ejemplo (lista, formulario, detalle)
- Integración de ejemplo para Firebase (Firestore) y Supabase
- Generación de código de barras (JsBarcode) y export PDF (jsPDF)

## Setup local
1. Instala dependencias:
   ```bash
   npm install
   ```
2. Copia `.env.local.example` a `.env.local` y agrega tus claves.
3. Levanta en desarrollo:
   ```bash
   npm run dev
   ```

## Deploy en Vercel
- Conecta tu repo a Vercel, agrega las variables de entorno (NEXT_PUBLIC_...)
- Deploy automático al hacer push a `main`

