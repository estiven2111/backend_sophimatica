# 📄 Sophimática Backend - Procesamiento Inteligente de Facturas

Este proyecto es el backend de la solución de procesamiento automático de facturas de **Sophimática**. Se encarga de analizar facturas en PDF o imagen, extraer la información relevante utilizando inteligencia artificial, almacenarla en base de datos, y exponerla a través de una API para su consumo.

## 🧠 ¿Qué hace?

- Permite subir archivos de factura (PDF o imagen)
- Procesa el contenido usando **Azure Text Analytics**
- Extrae información como:
  - Número de factura
  - Cédula / NIT
  - Razón social
  - Fecha
  - Concepto
  - Subtotal, total, impuestos (IVA, ipoconsumo, reteICA)
- Guarda los resultados en MongoDB
- Expone una API REST para consulta y visualización

## 🛠️ Tecnologías

- Node.js + Express
- MongoDB (Mongoose)
- Azure Cognitive Services (Text Analytics)
- Multer (para manejo de archivos)
- Dotenv
- Cors


