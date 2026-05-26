\# 🔌 Contrato de la API



\## 📄 Especificación OpenAPI



\[Ver especificación OpenAPI](https://raw.githubusercontent.com/jcosoriorios-pixel/Conec\_Calima/main/docs/api/api-nueva.yaml)



\---



\## ℹ️ Información General



\- \*\*API:\*\* Conecta Calima

\- \*\*Versión:\*\* 1.0.0

\- \*\*Tipo:\*\* OpenAPI 3.0.3



\---



\## 🚗 Endpoints principales



\### GET /reportes

Obtiene reportes de movilidad activos.



\### POST /reportes

Crea un nuevo reporte de movilidad.



\### POST /reportes/{id}/verificar

Permite validar un reporte existente.



\### GET /eventos

Lista agenda cultural y avisos municipales.



\### GET /comercios

Obtiene comercios verificadores.



\---



\## 📦 Modelo Reporte



\- id

\- tipo\_incidente

\- ubicacion

\- coordenadas

\- descripcion

\- verificado\_por\_comercio

\- creado\_en



\---



\## 🎭 Modelo Evento



\- id

\- titulo

\- descripcion

\- fecha\_inicio

\- lugar

