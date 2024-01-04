# Capstone on Interactive Dashboards with Power BI
## _A Statistical overview on HDB re-sale flats_
![image](https://github.com/KH-Liew/SCTP-Capstone-1-HDB-re-sale-statistic/assets/155032208/0a1e5800-e2cd-4c52-acb0-69c5f585dc71)
<img width="700" alt="image" src="https://github.com/KH-Liew/SCTP-Capstone-1-HDB-re-sale-statistic/assets/155032208/8c961629-891f-4649-9315-5158e4af6b75">
<img width="699" alt="image" src="https://github.com/KH-Liew/SCTP-Capstone-1-HDB-re-sale-statistic/assets/155032208/e4871fa2-5b68-4735-8404-d0373598778b">

[**Link to data-set**](https://beta.data.gov.sg/collections/189/view)
## Description of Dataset

The main data set used in the capstone is the hdb_resale_flat sources from data.gov.sg. It mainly consist of Resale transacted prices for Mar 2012 to Jun 2019, the data is based on date of registration for the resale transactions and includes the flat model, flat type, remaining lease, units’ floor area, storey and location.

The data set has 141688 entries and is dated from Mar 2012 to Jun 2019.

## Data Transformation
* Review Columns Quality
* Renamed Columns
* Changed Columns Type
* Fill in empty cells and adjust dates entry format
* Added new remaining lease term column based on HDB max 99 years lease

## Description of Dashboard

An analysis of Singapore HDB re-sale flats, dataset from year 2012 to 2019. The dashboard provides a visual and interactive platform for exploring re-sale flats patterns and trends, helping user to gain insights on the re-sale flats market in Singapore. The dashboard was created using Microsoft Power BI and focuses on mainly on the sum of re-sale price of flat types by year and locations. Slicers and Matrix Chart target insights on the specific sum of re-sale price based on the flat type, district, transcation year. The secondary information: Key Influncers provide insights on the driving factors of the increase and decrease of the re-sale prices.

## Insights
### _General Observations_
* The Types of HDB re-sale flats are single room, 2,3,4 & 5 rooms,  Executive, Multi-Generation
* The Top 3 most popular flat type are 3,4 & 5 rooms
* The Top 5 most popular district are Jurong West, Woodlands, Tampines, Sengkang, Yishun.

### _Analysis_
1. Factors driving the increase valuation of re-sale flats
   - Units' storey or floor level (most significant increase on units at 
     higher floors)
   - Market Trend on average higher increase in re-sale price in BUkit TImah, Bishan district
   - Executive & 5 rooms unit type have on average higher increase in re-sale value

2. Factors driving the decrease valuation or re-sale flats
   - Smaller units / floor area (2 rooms, 3 rooms flat)
   - Sum of remaining lease term is 47 or less (based on max 99 Years lease of HDB Units)
  
3. Sum of resale_price trended down, resulting in a 51.65% decrease between 2012 and 2019.﻿﻿ ﻿﻿
4. ﻿Sum of resale_price started trending up on 2015, rising by 23.12% ($1,786,912,634.99) in 3 years.﻿﻿ ﻿﻿
﻿﻿5. Sum of resale_price jumped from $7,729,135,940.52 to $9,516,048,575.51 during its steepest incline between 2015 and 2018.﻿﻿ ﻿
6. 4 ROOM accounted for 40.24% of Count of block.﻿﻿ ﻿

### _Future Scope_
The HDB market trend is constantly evolving, based on the most recent National Day Rally speech in 2023 a new classification of flats were introduction where towns will no longer be demarcated as mature and non-matured.

Coming 2024, Tighter Restrictions will also be implemented such as the 10 years MOP (Min Occupation Period) which is the time period ‘New’ HDB owners are required to occupy their flat before they can sell it on open market.

Such changes and announcements will have an impact on the valuation of HDB re-sale market trend on top of the fundamental and Key impacts related to the flats’ location, floor area, units’ storey and remaining lease term.



[**_Link to my Linkedin Profile_**](https://www.linkedin.com/in/kok-hong-liew-54338b189/)
