# PowerPivot_PowerQuery_Project
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

![qwdwqd](https://github.com/mfernandezcean/PowerPivot_PowerQuery_Project/assets/105746149/21f3a7e1-aac3-4318-adbd-874364e81238)

![revenueship](https://github.com/mfernandezcean/PowerPivot_PowerQuery_Project/assets/105746149/cf09fb68-43d0-443a-8242-b1945ad27930)

![Avgincome](https://github.com/mfernandezcean/PowerPivot_PowerQuery_Project/assets/105746149/c12f040e-fd72-41b4-902b-f56c01059ae7)

- Speedy Express seems to be some how deficent revenue wise:
  
![wfewfefwe](https://github.com/mfernandezcean/PowerPivot_PowerQuery_Project/assets/105746149/bfee001e-6260-4a82-bbd6-4265d92fc059)


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

![ascascsa](https://github.com/mfernandezcean/PowerPivot_PowerQuery_Project/assets/105746149/df0a977a-2b84-4afb-8442-8036ea402bd9)

![xasasxxas](https://github.com/mfernandezcean/PowerPivot_PowerQuery_Project/assets/105746149/0c43d3a0-53c7-44ae-a4eb-006b0f45b737)
