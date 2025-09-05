# stock-metrics-challenge

Coding challenge: analyze stock data and calculate financial metrics.

## Ejercicio de Programación

Tienes acceso a un API que regresa información de valores financieros.  
Cada llamada devuelve un arreglo con **500 elementos**.

Cada elemento tiene la siguiente estructura:

```json
{
  "date": "2006-01-03",
  "open": 10.5,
  "high": 12.0,
  "low": 9.8,
  "close": 11.2
}
### Requerimientos

1. Haz **5 llamadas al API** (`page=1` hasta `page=5`).  
   - Cada llamada trae **500 elementos**.  
   - En total tendrás **2500 elementos**.  

2. A partir de estos 2500 elementos, calcula las siguientes **tres métricas**:  
   - 📉 **Métrica 1:** El valor más bajo de todos los campos `low`.  
   - 📊 **Métrica 2:** El **promedio** de los valores `open` únicamente para los elementos del **año 2006**.  
   - 📈 **Métrica 3:** La **racha positiva más larga**, es decir, la secuencia más larga de días consecutivos en la que `close > open`.  

### Entregable

- Tu código debe hacer las llamadas al API (o simularlas, si no se cuenta con un endpoint real).  
- Al final, imprime en consola las 3 métricas con resultados claros.  
- Puedes usar cualquier lenguaje de programación.  
