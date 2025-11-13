# 🧮 Stock Metrics Challenge (React)

**Frontend coding challenge** — Consume una API que entrega datos financieros y muestra métricas calculadas en una interfaz hecha con **React**.

---

## 🎯 Objetivo

Desarrollar una aplicación web con **React** que:
1. Llame 5 veces al endpoint del API (páginas 1–5, cada una con 500 elementos).
2. Combine los datos obtenidos (2500 registros en total).
3. Calcule y muestre las siguientes métricas:
   - 📉 **Métrica 1:** El valor más bajo entre todos los campos `low`.
   - 📈 **Métrica 2:** El promedio de los valores `open` del año 2020.
   - 🧭 **Métrica 3:** La fecha con la mayor diferencia entre `high` y `low`.

4. Visualiza los resultados de forma clara (tabla, tarjetas o gráfico).
5. Agrega indicadores de *loading*, *error* y una interfaz limpia.

---

## ⚙️ Requisitos técnicos

- Usa **React 18+** (CRA, Vite o Next.js).
- Puedes usar TypeScript o JavaScript.
- Se permiten librerías como:
  - `axios` o `fetch` para API calls
  - `chart.js` o `recharts` (opcional)
  - `tailwindcss` o `styled-components` (opcional)

---

## 📦 Entregables

Tu aplicación debe incluir:
- Componente principal (`App.jsx` o `App.tsx`).
- Lógica para hacer las llamadas al API (paginadas).
- Cálculo de métricas.
- Renderizado visual de resultados.

---

## ▶️ Cómo ejecutar

Si usas **Vite**, por ejemplo:

```bash
git clone <TU_REPO_URL>
cd stock-metrics-challenge
npm install
npm run dev
