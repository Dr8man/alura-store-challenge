# 🛒 Alura Store – Challenge ONE (Data Science)

Este repositorio contiene la resolución completa del primer desafío del programa **Oracle Next Education - Data Science**, desarrollado en el entorno de **Google Colab** y gestionado mediante **GitHub**.

---

## 🎯 Objetivo del Desafío
Analizar los datos de ventas de cuatro tiendas de Alura Store para determinar cuál debería ser vendida, aplicando criterios cuantitativos y cualitativos, e integrando habilidades de manipulación de datos, visualización y análisis de negocio.

---

## 📊 Criterios Evaluados
Se utilizaron cinco criterios clave para evaluar el rendimiento de cada tienda. Cada criterio fue puntuado del 1 (peor) al 4 (mejor), en función del rendimiento relativo de las tiendas.

1. **Facturación total**
2. **Distribución de ventas por categoría**
3. **Calificación promedio de los clientes**
4. **Comportamiento extremo de productos vendidos**
5. **Costo promedio de envío**

---

## ⚖️ Sistema de Ponderación (β)
Cada criterio fue ponderado según su impacto estratégico con un coeficiente cualitativo **β**, de acuerdo a la siguiente escala:

- β = 1 → Bajo impacto
- β = 2 → Impacto medio
- β = 3 → Alto impacto

### 📋 Betas asignados:

| Criterio | Descripción                         | β |
|----------|-------------------------------------|---|
| 1        | Facturación total                   | 3 |
| 2        | Ventas por categoría                | 2 |
| 3        | Calificación promedio               | 3 |
| 4        | Productos más y menos vendidos      | 2 |
| 5        | Costo promedio de envío             | 3 |

---

## 🧮 Cálculo del Puntaje Final
Se asignó a cada tienda un puntaje en cada criterio (1 a 4), luego multiplicado por su beta correspondiente. La suma total de los valores ponderados representa el **puntaje final de cada tienda**:

Puntaje Total = (C1 × β1) + (C2 × β2) + (C3 × β3) + (C4 × β4) + (C5 × β5)


---

## 🥇 Resultado Final
- **Tienda con mejor desempeño:** [Nombre de la tienda con mayor puntaje]
- **Tienda con peor desempeño:** [Nombre de la tienda con menor puntaje]

### ✅ Recomendación:
Con base en los resultados, se recomienda **vender la tienda con peor desempeño**, optimizando así los recursos de la empresa y concentrando esfuerzos en las sucursales más rentables y competitivas.

---

## 👤 Autor
**[Dr8man]**  
Programa Oracle Next Education – Data Science  
GitHub: [https://github.com/Dr8man](https://github.com/Dr8man)

