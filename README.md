<h1 align="center">Avocadocalypse</h1>
<p align="center"><em>U.S.-centric avocado study (2015–2021)</em></p>

## Table of Contents

1. [Questions & Hypotheses](#questions--hypotheses)
2. [Approach and Analysis](#approach-and-analysis)
3. [Technical Challenges](#technical-challenges)
4. [Q1. Price and Volume](#q1-price-and-volume)
5. [Q2. Regions and Sales](#q2-regions-and-sales)
6. [Q3. Product Preference](#q3-product-preference)
7. [Q4. Mirror Image?](#q4-mirror-image)
8. [Deeper Analysis](#deeper-analysis)
9. [New Metric: Purchasing Power (Los Angeles)](#new-metric-purchasing-power-los-angeles)
10. [Final Results](#final-results)

---

## Questions & Hypotheses

1. **Does the price have an influence on the volume?**  
   *Hypothesis:* Yes, the price has an influence on the volume and vice versa.

2. **Which areas consumed avocados the most from 2015 to 2021?**  
   *Hypothesis:* Mostly the highly developed areas because of vegetarian and vegan trends.

3. **The PLU4770 being the biggest Hass variety, is it also the one consumed the most?**  
   *Hypothesis:* Yes, because consumers tend to go for the cleanest, most beautiful, biggest product.

4. **Is the trend in the most consuming city an image of the general trend in the U.S?**  
   *Hypothesis:* Yes.

---

## Approach and Analysis

1. Data tables downloaded from [hassavocadoboard.com](https://hassavocadoboard.com) (primary source).
2. Formatted, compiled, and cleaned into a single dataset.
3. Columns considered: `AveragePrice`, `TotalVolume`, `Year`, `Region`, various PLU codes.
4. Statistical inference and graphical visualization were employed.

---

## Technical Challenges

1. Some missing values in the "bags" column; these were excluded.
2. Mixed 'region' fields: both cities and whole U.S. regions (e.g., TotalUS, California, SouthCentral, NorthEast), which had to be separated.

---

## Q1. Price and Volume

<p align="center">
  <img src="https://github.com/user-attachments/assets/643edca1-0294-4b02-8350-07981108f395" alt="average price" width="45%" style="display:inline-block; margin-right: 10px;" />
  <img src="https://github.com/user-attachments/assets/91a348cd-27f6-456c-a5c2-ec60491fb323" alt="volume per year" width="45%" style="display:inline-block;" />
</p>

- Aside from the price decrease from $1.5 to $1.3 (2019 to 2020), which corresponded with a 1 billion increase in sales, there is **no strong correlation** between price and volume.

---

## Q2. Regions and Sales

<p align="center">
  <img src="https://github.com/user-attachments/assets/da6445ae-88e0-48fa-9193-3fa6f651a18c" alt="volume per region" width="45%" style="display:inline-block; margin-right: 10px;" />
  <img src="https://github.com/user-attachments/assets/2ba1cd4d-b1de-49ad-8d1a-d60551fb91b0" alt="volume per city" width="45%" style="display:inline-block;" />
</p>

Looking at the cities, we see Los Angeles, New York, Houston, Denver, San Francisco, Chicago as the cities who consume the most.
_Los Angeles is the top city (1.05 billion avocados sold, 2015–2021)._

---

## Q3. Product Preference

<h4 align="center">Variety per Year</h4>

<p align="center">
  <img src="https://github.com/user-attachments/assets/9e29d3ea-8604-410b-86e0-b925b2d4830c" alt="variety per year" width="60%" />
</p>

- The most popular avocado variety is **PLU 4046** (small size).
- **PLU 4770** (the biggest Hass) is the least sold, not the most.
- Important: Difference might be due to production—not just preference.

---

## Q4. Mirror Image?

<table>
  <tr>
    <td align="center" width="50%">
      <img src="https://github.com/user-attachments/assets/6f870747-2993-4b9a-9cfe-20d5a979697b" alt="volume and variety per year" width="100%" />
      <div><strong>Volume in the U.S from 2015 to 2021</strong></div>
    </td>
    <td align="center" width="50%">
      <img src="https://github.com/user-attachments/assets/1a5d0c50-8e12-4543-bbd0-de38342d1beb" alt="volume los angeles" width="100%" />
      <div><strong>Volume in Los Angeles from 2015 to 2021</strong></div>
    </td>
  </tr>
</table>

**Total U.S. volume (2015–2021):**  
- The general trend: total volume **increases** over time.

**Los Angeles consumption:**  
- Trend is _stable_ around **150 million** per year.

**Conclusion:**  
- LA’s trend does **not** mirror the U.S. as a whole.

---

## Deeper Analysis

<h4 align="center">Top Cities/Years</h4>

<p align="center">
  <img src="https://github.com/user-attachments/assets/ad736bb2-19dd-4370-b6e4-de025df93b4f" alt="top 10 cities years" width="60%" />
</p>

- Los Angeles & New York are the two majors contributors to the sales of avocados in the U.S followed by Phoenix, Houston and Dallas
---

## New Metric: Purchasing Power (Los Angeles)

<table>
  <tr>
    <td align="center" width="50%">
      <img src="https://github.com/user-attachments/assets/395ee4c0-5302-4e9a-a02d-ecb3421dcb81" alt="volume los angeles" width="100%" />
      <div><strong>Volume in Los Angeles from 2015 to 2021</strong></div>
    </td>
    <td align="center" width="50%">
      <img src="https://github.com/user-attachments/assets/06cecc41-a264-4160-9d23-78b297f2ef45" alt="Purchasing power" width="100%" />
      <div><strong>Purchasing Power from 2015 to 2021</strong></div>
    </td>
  </tr>
</table>

- In 2018, the price per avocado dropped, as did the number of avocados per inhabitant, corresponding with a drop in total volume.
- Despite rising prices and general cost of living, _the number of avocados bought per inhabitant does not fluctuate significantly_.

---

## Final Results

1. **Does the price have an influence on the volume?**  
   In a sense yes but it is not significant enough to have an influence; other variables come into play.

2. **Which areas consumed avocados the most from 2015 to 2021?**  
   West, California, and South Central have consumed the most avocados from 2015 to 2021. Los Angeles is the city where the most avocados were sold during that period (1.05 billion avocados sold).

3. **The PLU4770 being the biggest Hass variety, is it also the one consumed the most?**  
   Quite the opposite, the PLU4770 is the least sold while the smaller one, the PLU 4046, is the one sold the most. However, it would be important to compare the production units to the units sold to see if the fact that the PLU4770 is sold the least is because it is also the least produced.

4. **Is the trend in the most consuming city an image of the general trend in the U.S?**  
   No, the trend in Los Angeles tends to be stabilized around 150 million every year while the general trend in the U.S tends to increase over the years.

5. **Los Angeles and New York consume the most avocados, followed by Dallas, Houston, Phoenix, Chicago, and San Francisco.**

6. **Despite the price increase, the general cost of living increasing as well, the number of avocados bought per inhabitant doesn’t fluctuate significantly.**

---
