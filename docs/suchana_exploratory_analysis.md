---
layout: default
title: Suchana
nav_order: 13
permalink: /docs/suchana_exploratory_analysis
---

## Suchana's effect on the Production of Nutrient-rich SIS 
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

<style>
/* Timeline wrapper */
.timeline {
  position: relative;
  max-width: 1200px;
  margin: 0 auto;
}

/* Vertical line */
.timeline::after {
  content: '';
  position: absolute;
  width: 4px;
  background-color: #F0F0F0;
  top: 0;
  bottom: 0;
  left: 50%;
  margin-left: -3px;
}

/* Container around content — LESS EMPTY SPACE */
.container {
  padding: 4px 28px;       /* ↓ was 10px 40px */
  position: relative;
  background-color: inherit;
  width: 50%;
}

/* Circles — kept same size */
.container::after {
  content: '';
  position: absolute;
  width: 15px;
  height: 15px;
  right: -13px;
  background-color: #F0F0F0;
  border: 4px solid #085C08;
  top: 12px;               /* ↓ slightly reduced */
  border-radius: 50%;
  z-index: 1;
}

.left { left: 0; }
.right { left: 50%; }

/* Arrows — repositioned for smaller padding */
.left::before {
  content: " ";
  position: absolute;
  top: 18px;               /* ↓ was 22px */
  right: 22px;             /* ↓ was 30px */
  border: medium solid #F0F0F0;
  border-width: 8px 0 8px 8px;   /* ↓ smaller */
  border-color: transparent transparent transparent #F0F0F0;
}

.right::before {
  content: " ";
  position: absolute;
  top: 18px;
  left: 22px;              /* ↓ was 30px */
  border: medium solid #F0F0F0;
  border-width: 8px 8px 8px 0;
  border-color: transparent #F0F0F0 transparent transparent;
}

/* Fix circle position right side */
.right::after {
  left: -13px;
}

/* Actual content box — LESS EMPTY SPACE */
.content {
  padding: 10px 18px;      /* ↓ was 20px 30px */
  background-color: #F0F0F0;
  position: relative;
  border-radius: 6px;
}

/* Text sizes kept the same */
.small-text h4 {
  font-size: 14px;
  margin-bottom: 4px;
}

.small-text p {
  font-size: 12px;
  line-height: 1.3;
}

/* Mobile layout */
@media screen and (max-width: 600px) {

  .timeline::after {
    left: 31px;
  }

  .container {
    width: 100%;
    padding: 4px 20px 4px 55px;  /* tightened */
  }

  .container::before {
    left: 50px;
    border-width: 8px 8px 8px 0;
    border-color: transparent #F0F0F0 transparent transparent;
  }

  .left::after, .right::after {
    left: 15px;
  }

  .right {
    left: 0%;
  }
}

</style>


<div class="timeline">

  <div class="container left">
    <div class="content small-text">
      <h4>2012</h4>
      <p>BIHS R1</p>
    </div>
  </div>

  <div class="container left">
    <div class="content small-text">
      <h4>2015</h4>
      <p>BIHS R2</p>
    </div>
  </div>

  <div class="container right">
    <div class="content small-text">
      <h4>2016</h4>
      <p>Suchana starts in the original locations</p>
    </div>
  </div>

  <div class="container left">
    <div class="content small-text">
      <h4>2018</h4>
      <p>BIHS R3</p>
    </div>
  </div>

  <div class="container right">
    <div class="content small-text">
      <h4>2020</h4>
      <p>Suchana starts in replication areas</p>
    </div>
  </div>

  <div class="container right">
    <div class="content small-text">
      <h4>2022</h4>
      <p>End of original activities (December)</p>
    </div>
  </div>

  <div class="container right">
    <div class="content small-text">
      <h4>2023</h4>
      <p>End of replication activities</p>
    </div>
  </div>

  <div class="container left">
    <div class="content small-text">
      <h4>2024</h4>
      <p>BIHS R4</p>
    </div>
  </div>

</div>


<br>
<br>



## Suchana in the BIHS

Suchana was implemented at the Union level (smallest possible admin unit). However, many of these unions are not present in the BIHS. If one considers that the entire Upazila was treated once a union inside it received the intervention (which would make sense because of spillovers), we get a bit more power. I ran the exploratory analyses both ways. Results are pretty similar in magnitude and direction, but the ones for Upazilla-level treatment are more significant. 

|                        | Wave 1 (2012) | Wave 2 (2015) | Wave 3 (2018) | Wave 4 (2024)          |
|------------------------|--------------|--------------|--------------|------------------------|
| **Treated Unions (total)** | 0            | 0            | 78           | 157 + 26 (replication) |
| **Treated Unions (BIHS)**  | 0            | 0            | 12           | 18                     |
| **# Treated households (BIHS)** - Union level treatment | 0            | 0            | 257          | 390*                   |
| **# Treated households (BIHS)** - Upazila level treatment| 0            | 0            | 370         | 449*                   |
| **All households (BIHS)**  | 6,503        | 6,436        | 5,604        | ?                      |

*Based on the number of households in those unions in R3

### Treatment at the Union level
<iframe src="suchana_unions" height="400" width="560"> Suchana Intervention Areas </iframe>

### Treatment at the Upazila level
<iframe src="suchana_upazilla" height="400" width="560"> Suchana Intervention Areas </iframe>

<br>
<br>

## Observable Characteristics 

- Carps, tilapia, SIS cultivated in the same pond
- Dried small fish (production and consumption)
- More harvests per pond
- Tilapia and Carps ponds more productive (?)
- Mothers thinking it is OK to feed small fish to their young children (no way of checking this with the DiD - R1 is missing)
- GIFT tilapia and G3 rohu (no way of checking this with the DiD)


<br>
<br>

## Exploratory Analysis

For now I am only using rounds 1, 2 and 3 of the BIHS (because I don't have access to the latest round). So instead of a staggered event study I am doing a TWFE, and considering the blue unions (treated between 2016 and 2018) as treatment.


### Parallel trends

<img src="combined_share_SIS.png" alt="Share of SIS Producing Households">

<img src="combined_share_mola.png" alt="Share of Mola Producing Households">

<img src="combined_share_consume_dry_SIS.png" alt="Share of Households Consuming dried SIS">

<img src="combined_share_consume_SIS.png" alt="Share of Households Consuming SIS">

<img src="combined_avg_harvest_per_pond.png" alt="Average Number of Harvests per Pond">

<img src="combined_l1_11.png" alt="Average Harvest per Pond">

<img src="combined_average_yields.png" alt="Avg. Spent on Fish Feed per kg produced (Carp ponds)">

<img src="combined_carp_SIS_poly_avg.png" alt="Share of Households Growing Carps and SIS in same pond">


<br>

### TWFE Preliminary Results

### Treatment at Union Level (likely underpowered for R3)

| Union-level Treatment | (1) Produce SIS | (2) Produce Mola | (3) Consumes SIS | (4) Consumes Dry SIS | (5) Average Harvest per Pond (kg) | (6) Number of Harvest | (7) Avg Spent on Feed/kg Harvest (Carp Ponds) | (8) Carp-SIS Polyculture |
|----------------------|--------------|--------------|--------------|--------------|------------------------------|-------------------|---------------------------------|----------------------|
| **Treated x Round 3** | 0.095 | 0.21*** | 0.028 | 0.047 | -63.42 | 14.46*** | -80.5* | -0.016 |
|                      | (0.067) | (0.0468) | (0.0349) | (0.034) | (69.7) | (3.35) | (48.7) | (0.114) |
| **Individual FE**    | Yes | Yes | Yes | Yes | Yes | Yes | Yes | Yes |
| **Time FE**         | Yes | Yes | Yes | Yes | Yes | Yes | Yes | Yes |
| **Observations**    | 4,104 | 4,104 | 17,475 | 17,475 | 2,425 | 2,439 | 2,075 | 2,439 |
| **R²**             | 0.6439 | 0.4468 | 0.4828 | 0.517 | 0.5011 | 0.4633 | 0.3922 | 0.4351 |

Standard errors are clustered at the union level.

### Treatment at Upazila Level

| Upazilla-level Treatment | (1) Produce SIS | (2) Produce Mola | (3) Consumes SIS | (4) Consumes Dry SIS | (5) Average Harvest per Pond (kg) | (6) Number of Harvest | (7) Avg Spent on Feed/kg Harvest (Carp Ponds) | (8) Carp-SIS Polyculture |
|----------------------|--------------|--------------|--------------|--------------|------------------------------|-------------------|---------------------------------|----------------------|
| **Treated x Round 3** | 0.08* | 0.222*** | 0.078** | 0.09*** | -67.19 | 11.91*** | -84.5* | -0.036 |
|                      | (0.049) | (0.053) | (0.038) | (0.034) | (70.4) | (3.583) | (49.3) | (0.0935) |
| **Individual FE**    | Yes | Yes | Yes | Yes | Yes | Yes | Yes | Yes |
| **Time FE**         | Yes | Yes | Yes | Yes | Yes | Yes | Yes | Yes |
| **Observations**    | 4,104 | 4,104 | 17,475 | 17,475 | 2,425 | 2,439 | 2,075 | 2,439 |
| **R²**             | 0.6439 | 0.4492 | 0.4831 | 0.5174 | 0.5011 | 0.4631 | 0.3922 | 0.435 |

Standard errors are clustered at the union level. Clustering at upazila level does not change much (it just becomes more significant). But I chose to keep it at union level since actual treatment delivery by Worldfish was at union level.

<br>
<br>


{% include comment-section.html url=page.url %}

