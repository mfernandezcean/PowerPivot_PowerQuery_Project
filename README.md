# PowerPivot_PowerQuery_Project
In this repository you'll find what I can do with Power Query and Power Pivot with the **Northwind** Data challenge. For this Anlysis i'm inly going to use Excel. In other file, I will make a dashboard with Power BI. 


![w12](https://github.com/mfernandezcean/PowerPivot_PowerQuery_Project/assets/105746149/a3ffb3f3-17be-4c9d-94d4-058d872af0b6)


Sales & order data for ***Northwind Traders***, a fictitious gourmet food supplier, including information on customers, products, orders, shippers, and employees.

#### [Maven Analytics Challenge Link](https://app.mavenanalytics.io/datasets)

## Recommended Analysis
 1.   Are there any noticable sales trends over time?
 2.   Which are the best and worst selling products?
 3.  Can you identify any key customers?
 4.   Are shipping costs consistent across providers?

### Data Model:

![nw data model](https://github.com/mfernandezcean/PowerPivot_PowerQuery_Project/assets/105746149/48cd929a-b8a4-4420-a668-58a5fad15861)

---
### Answers 
#### 1.Are there any noticable sales trends over time?

![q](https://github.com/mfernandezcean/PowerPivot_PowerQuery_Project/assets/105746149/40fa08fa-bddd-4ae1-9cf0-c45fde8cf9c5)

Why the drastic fall at the end of the chart?

![q111](https://github.com/mfernandezcean/PowerPivot_PowerQuery_Project/assets/105746149/a1f033bd-4888-4ba9-8de3-f0224ad20bb6)

 - Removing the incomple month of May, we can se a clear trend: Grouping by quarters, we avoid the impact of the incomplete info of May 2015, without the nesecitiy of ingoring it.


![67i](https://github.com/mfernandezcean/PowerPivot_PowerQuery_Project/assets/105746149/05200185-bba0-4e26-9d32-66165b0334af)
---
#### 2.Which are the best and worst selling products?

![ascacsas](https://github.com/mfernandezcean/PowerPivot_PowerQuery_Project/assets/105746149/e06d418f-a76e-43c6-bc4c-b9ab11f48ebd)
---
#### 3.Can you identify any key customers?

![123231](https://github.com/mfernandezcean/PowerPivot_PowerQuery_Project/assets/105746149/94bda7ed-f43a-4fd8-b7d3-b71bb856d2f7)
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

![qwdwqd](https://github.com/mfernandezcean/PowerPivot_PowerQuery_Project/assets/105746149/50f2511d-a67a-412d-9139-33e55e932326)

![revenueship](https://github.com/mfernandezcean/PowerPivot_PowerQuery_Project/assets/105746149/f3c21c48-9f08-4611-9de5-0c4f606cff0e)

![Avgincome](https://github.com/mfernandezcean/PowerPivot_PowerQuery_Project/assets/105746149/f601d990-4dbf-45eb-adb8-ec8e86edccbf)

- Speedy Express seems to be some how deficent revenue wise:
  
![wfewfefwe](https://github.com/mfernandezcean/PowerPivot_PowerQuery_Project/assets/105746149/43b31d7c-1988-4dd0-9e67-d659374b7afe)


| Shipper |% Quantity  |% Revenue|% Revenue w/Discount| Var: Rev. & Rev.w/Disc.
|--|--|--|--|--|
|  Federal Shipping| 30.11%|30.10%|30.29%|0.19%
|Speedy Express|31.02%|27.61%|27.56%|-0.05%
|United Package|38.87%|42.28%|42.15%|-0.13%|
||100%|100%|100%

- #### Recomendation: If possible increase the business done with United Package and also with Federal Shipping
