# Rio de Janeiro Data Analysis

This repository contains Python scripts for analyzing Airbnb data in Rio de Janeiro. The dataset used for this analysis can be found [here](http://data.insideairbnb.com/brazil/rj/rio-de-janeiro/2022-06-20/visualisations/listings.csv).

## Problem Statement

The focus of this analysis is on Rio de Janeiro, utilizing neighborhood information, prices, and rental types to answer the following questions:

1. **Average price per rental type in Rio de Janeiro:**
   - Implemented a function `precio_promedio_por_tipo_de_alquiler()` that calculates the average price for each rental type. The results are stored in a dictionary where the rental type serves as the key, and the average price as the value.

2. **Number of rental types per neighborhood:**
   - The function `cantidad_de_tipos_por_barrio()` returns a dictionary, `tipo_de_alquiler_por_barrio`, mapping neighborhoods to the count of each rental type available in that neighborhood.

3. **Number of listings per neighborhood:**
   - The function `cantidad_anuncios_barrio()` calculates the total number of listings for each neighborhood and returns a dictionary with neighborhoods as keys and the corresponding number of listings as values.

## Data Structures

### 1st Question

We aim to determine the average price per rental type, and this information is stored in a dictionary where each rental type is associated with its average price. The process involves summing the prices for each rental type and then calculating the average.

### 2nd Question

The second question is addressed by the function `cantidad_de_tipos_por_barrio()`, which returns a dictionary named `tipo_de_alquiler_por_barrio`. This dictionary has neighborhoods as keys and another dictionary as values. The inner dictionary has rental types as keys and the count of each type in that neighborhood as values.

### 3rd Question

The third question is tackled by the function `cantidad_anuncios_barrio()`, which returns a dictionary named `cantidad_anuncios_barrio`. It maps each neighborhood to the total number of listings in that neighborhood.
