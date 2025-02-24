---
layout: default
title: Suchana
nav_order: 13
permalink: /docs/suchana_exploratory_analysis
---

## Suchana's impact on the Production of Nutrient-rich SIS 
<br>


{: .note-title }
> Small Indigenous Species: A CGIAR-Led Revival
>
> Small indigenous species (SIS) are a naturally occurring dietary staple in Bangladesh. However, with the rise of commercial aquaculture, SIS populations declined significantly as farmers increasingly "cleaned" their ponds with pesticides. This practice, based on the belief that small, lower-yielding native fish competed with more marketable species like carp and tilapia, led to the widespread loss of SIS.
> 
> WorldFish has worked to dismantle this misconception, pioneering the promotion of carp-tilapia-SIS polyculture to enhance both productivity and nutrition. Since 2011, it has been implementing this approach through smaller projects like IDEA and ANEP. However, these initiatives remained limited in scale, each reaching fewer than 2,000 households across different divisions.


Suchana (2016-2023) was a large-scale project in the Sylhet division focusing on multiple nutrition interventions. It reached 250,000 households over 7 years, with at least 75,000 of these also getting the aquaculture-related interventions, which were delivered by WorldFish. 
The interventions included:
-  Encouraging the production of SIS;
-  Encouraging the production of dried fish;
-  Disseminating carp-tilapia-SIS polyculture systems;
-  Encouraging the usage of improved management practices

<br>
<br>



## Suchana in the BIHS

|                        | Wave 1 (2012) | Wave 2 (2015) | Wave 3 (2018) | Wave 4 (2024)          |
|------------------------|--------------|--------------|--------------|------------------------|
| **Treated Unions (total)** | 0            | 0            | 78           | 157 + 26 (replication) |
| **Treated Unions (BIHS)**  | 0            | 0            | 12           | 18                     |
| **# Treated households (BIHS)** | 0            | 0            | 257          | 390*                   |
| **All households (BIHS)**  | 6,503        | 6,436        | 5,604        | ?                      |

*Based on the number of households in those unions in R3

<iframe src="suchana_unions" height="500" width="700"> Suchana Intervention Areas </iframe>

<br>
<br>

## Observable Charactersitics 

- Carps, tilapia, SIS cultivated in the same pond
- Dried small fish (production and consumption)
- More harvests per pond
- Tilapia and Carps ponds more productive (?)
- Mothers thinking it is OK to feed small fish to their young children
- GIFT tilapia and G3 rohu (no way of checking this with the DiD)


<br>
<br>

## Exploratory Analysis

For now I am only using rounds 1, 2 and 3 of the BIHS (because I don't have access to the latest round). So instead of a staggered event study I am doing a TWFE, and considering the blue unions (treated between 2016 and 2018) as treatment.


### Parallel trends

<img src="share_produce_SIS.png" alt="Share of SIS Producing Households">

<img src="avg_number_harvests_pond.png" alt="Average Number of Harvests per Pond">


<br>
<br>


{% include comment-section.html url=page.url %}

