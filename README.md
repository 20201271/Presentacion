# Base de Datos: Los determinantes políticos e institucionales de la ratificación del Acuerdo de Escazú en Sudamérica

Este repositorio contiene la base de datos unificada utilizada para analizar la relación entre la ratificación del Acuerdo de Escazú, la calidad democrática, la soberanía estatal y el nivel de desarrollo económico en países sudamericanos.

## Diccionario de Variables

| Variable | Descripción | Fuente | Año(s) |
|---------|-------------|--------|--------|
| `pais` | Nombre del país en inglés (según V-Dem) | Wikipedia | 2018-2024 |
| `liberal_democracy_index` | Índice de democracia liberal (0–1; mayor = más democrático) | V-Dem v15 (`v2x_libdem`) | 2018-2024 |
| `state_authority_over_territory` | Control estatal sobre el territorio (0–1; mayor = más control) | V-Dem v15 (`v2svstterr`) | 2018-2024 |
| `gdp_per_capita_avg` | PIB per cápita promedio en dólares corrientes (USD) | Banco Mundial (`NY.GDP.PCAP.CD`) | 2018–2024 |
| `inestabilidad_politica` | Índice de inestabilidad política (escala 1–7; mayor = más inestable) | Wikipedia | 2018-2024 |

> **Nota**: Venezuela no tiene datos de PIB per cápita en el Banco Mundial para el período 2018–2024, por lo que aparece como `NA` en `gdp_per_capita_avg`.

## Países incluidos (12)

- Argentina  
- Bolivia  
- Brazil  
- Chile  
- Colombia  
- Ecuador  
- Guyana  
- Paraguay  
- Peru  
- Suriname  
- Uruguay  
- Venezuela  

## Autor
Lidia Esquivel Roque  
PUCP 20201271
