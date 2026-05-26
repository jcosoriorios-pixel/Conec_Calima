\# 🔌 Contrato de la API



\[Ver especificación OpenAPI](https://raw.githubusercontent.com/jcosoriorios-pixel/Conec\_Calima/main/docs/api/api-nueva.yaml)

\# 🔌 Contrato de la API



\## Información General



\- API: Conecta Calima

\- Versión: 1.0.0

\- Tipo: OpenAPI 3.0.3



\## Endpoints principales



\### GET /reportes

Obtiene reportes de movilidad activos.



\### POST /reportes

Crea un nuevo reporte de movilidad.



\### POST /reportes/{id}/verificar

Permite validar un reporte existente.



\### GET /eventos

Lista eventos culturales y municipales.



\### GET /comercios

Obtiene comercios verificadores.



\## Modelo Reporte



\- id

\- tipo\_incidente

\- ubicacion

\- coordenadas

\- descripcion

\- verificado\_por\_comercio

\- creado\_en



\## Modelo Evento



\- id

\- titulo

\- descripcion

\- fecha\_inicio

\- lugar

