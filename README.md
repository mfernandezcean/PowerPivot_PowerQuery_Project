# Power BI Northwind Project
In this repository you'll find what I can do with Power Query and Power Pivot with the **Northwind** Data challenge. For this Anlysis i'm inly going to use Excel. In other file, I will make a dashboard with Power BI. 

![w12](https://github.com/mfernandezcean/PowerPivot_PowerQuery_Project/assets/105746149/19fbff06-1460-4193-855a-d655a2984a1e)


Sales & order data for ***Northwind Traders***, a fictitious gourmet food supplier, including information on customers, products, orders, shippers, and employees.

#### [Maven Analytics Challenge Link](https://app.mavenanalytics.io/datasets)

## Recommended Analysis
 1.   Are there any noticable sales trends over time?
 2.   Which are the best and worst selling products?
 3.  Can you identify any key customers?
 4.   Are shipping costs consistent across providers?

### Data Model:

![nw data model](https://github.com/mfernandezcean/PowerPivot_PowerQuery_Project/assets/105746149/77be057b-fdfd-46ba-9a7e-552fe6e25bc9)

---
### Answers 
#### 1.Are there any noticable sales trends over time?


![acscascascas](https://github.com/mfernandezcean/PowerPivot_PowerQuery_Project/assets/105746149/ff15ecb6-6fa8-40da-a277-ca823d9a8d9f)

Why the drastic fall at the end of the chart?

![acscsacascsacsa](https://github.com/mfernandezcean/PowerPivot_PowerQuery_Project/assets/105746149/caa4aaaf-cb4c-4810-95c7-acee25f99e29)



 - Removing the  month of May from the analysis, we can se a clear trend: 

![acsasccsacasascas](https://github.com/mfernandezcean/PowerPivot_PowerQuery_Project/assets/105746149/9f097819-7ff8-4846-b5a3-b9f73dcc849f)
---

#### 2.Which are the best and worst selling products?

![asxxasasx](https://github.com/mfernandezcean/PowerPivot_PowerQuery_Project/assets/105746149/1d4c964e-e804-4772-9a0b-656d46ac8249)
---

#### 3.Can you identify any key customers?

![asccascas](https://github.com/mfernandezcean/PowerPivot_PowerQuery_Project/assets/105746149/ff17ed76-4f7d-4964-af3b-087c6ec94e80)
---

#### 4.Are shipping costs consistent across providers?
- Measures looked afer:
   - Quantity of Orders Shipped
   - Revenues per Shipper
   - Average Revenue per order

- **No they are not.** I've spoted some incogruences with the shippers selection:
   - United Package is the solid lider of the shippers. Is on top in the 3 measrues
   - Speedy Express seems to be not the best partner
   - Federal Shipping show numbers that are promising

![ascscsacscs](https://github.com/mfernandezcean/PowerPivot_PowerQuery_Project/assets/105746149/e1e9cfa1-a884-4113-bd66-9cdd90c03f17)

![ascsaccas](https://github.com/mfernandezcean/PowerPivot_PowerQuery_Project/assets/105746149/f894b563-c15f-4123-82bf-509a229a1576)

![qwqwqqwq](https://github.com/mfernandezcean/PowerPivot_PowerQuery_Project/assets/105746149/f88c7053-98de-4ad4-b137-4b71dd0c443c)

- Speedy Express seems to be some how deficent revenue wise:
  
![wefefwefwewf](https://github.com/mfernandezcean/PowerPivot_PowerQuery_Project/assets/105746149/9ba23550-3cde-4feb-bf0f-20db0c13a214)


Speedy Express is ranked second in transactions, but it is the last one to bring in money. Has the **lowest Average** per order and has a big discount rate if we compare with United Package and its massive quantity sold.


- This table shows the distribution of the Quantity of orders, Revenue and also the Revenue after we substract the discount that every shipper has: 

| Shipper |% Quantity  |% Revenue|% Revenue w/Discount| Var: Rev. & Rev.w/Disc.
|--|--|--|--|--|
|  Federal Shipping| 30.11%|30.10%|30.29%|0.19%
|Speedy Express|31.02%|27.61%|27.56%|-0.05%
|United Package|38.87%|42.28%|42.15%|-0.13%|
||100%|100%|100%

We clearly see the very good perfomance of **Federal Shipping** in comparison with the other two. 


- #### Recomendation: If possible increase the business done with United Package and also with Federal Shipping, that currently is last in Quantiy of orders and shows promising Revenues numbers.
	- And decrease the amount of orders done with Speedy Express
---

### Extras
- Category of Product:

![ascascsa](https://github.com/mfernandezcean/PowerPivot_PowerQuery_Project/assets/105746149/df0a977a-2b84-4afb-8442-8036ea402bd9)
---

- Geo:
  
The World by Quantity of Orders:
![xasasxxas](https://github.com/mfernandezcean/PowerPivot_PowerQuery_Project/assets/105746149/0c43d3a0-53c7-44ae-a4eb-006b0f45b737)



![erge4r4et4ete4tt4](https://github.com/mfernandezcean/PowerPivot_PowerQuery_Project/assets/105746149/53921c0a-376e-45e4-97bf-2a021335e065)
