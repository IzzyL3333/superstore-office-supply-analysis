# Superstore Office Supplies Analysis 🛒
This exercise aimed to provide valuable, data-derived insights into sample Superstore data. As a Data Scientist, I performed basic EDA and data analysis using a sample of Superstore data. 

## Table of Contents
- [Data](#data)
- [Work](#work)
- [Behind the Scenes](#bts)
- [Future Considerations](#future-considerations)

---

<a id="data"></a>
### Data :books:
The data was originally sourced from [Tableau](https://public.tableau.com/app/learn/sample-data) as "EU Superstore Sales." 

The data consisted of three tables of Superstore information: Orders, Returns, and People. The analysis focuses on Orders only.

**Table: sample_superstore_data**
|Column Name| Description|
|---|---|
|Row ID | A unique identifier for each transactional row. |
|Order ID | A unique ID for each specific customer order. |
|Order Date | The date the order was placed. |
|Ship Date | The date the product was shipped. |
|Ship Mode | The mode of shipping used (e.g., Standard Class, First Class, Same Day, Second Class).  |
|Customer ID | A unique identifier for each customer. |
|Customer Name |	The name of the customer. |
|Segment |  The customer segment (e.g., Consumer, Corporate, Home Office). |
|Country | The country of residence of the customer. |
|City | The city of residence of the customer. |
|State | The state/province of residence of the customer. |
|Postal Code | The postal code of the customer's location. |
|Region | The region where the customer is located (e.g., North, South, East, West). |
|Product ID | A unique ID for each product. |
|Category | The main category of the product (e.g., Technology, Furniture, Office Supplies).|
|Sub-Category | The specific sub-category of the product (e.g., Chairs, Phones, Binders). |
|Product Name | The name of the specific product. |
|Sales | The total sales amount for the product in that transaction. |
|Quantity | The quantity of the product ordered. |
|Discount | The discount provided for the transaction (usually a percentage). |
|Profit | The profit or loss incurred from the transaction. |

---

<a id="work"></a>
### Work :bar_chart:

Using Tableau, the following questions were answered.

Sales
- What category brought the most sales in Office Supplies?
- What customer segments brought the most sales in Office Supplies?
- What region brought the most sales in Office Supplies?
- Which US state brought the most sales in Office Supplies?

Profit
- What category brought the most profit in Office Supplies?
- What customer segments brought the most profit in Office Supplies?
- What region brought the most profit in Office Supplies?
- Which US state brought the most profit in Office Supplies?

---

<a id="bts"></a>
### Behind the Scenes :eyes:

_Sales_
<img width="1536" height="412" alt="image" src="https://github.com/user-attachments/assets/6388943e-e7ca-4d95-828c-385283c58b79" />

**Storage** category brought the most sales in Office Supplies.

<img width="467" height="787" alt="image" src="https://github.com/user-attachments/assets/39179c38-e449-44cb-9a7f-43ec53ce648f" />

**West** region brought the most sales in Office Supplies.

<img width="1480" height="411" alt="image" src="https://github.com/user-attachments/assets/6db080f3-b4c9-4e68-8a60-4331dcf49ac1" />

**Consumers** brought the most sales in Office Supplies.

<img width="1539" height="790" alt="image" src="https://github.com/user-attachments/assets/e2146525-4450-406d-b354-d385e02d4f15" />

**California** state brought the most sales in Office Supplies.

_Profit_
<img width="1484" height="383" alt="image" src="https://github.com/user-attachments/assets/0ccc192a-bb5b-42ba-932d-9d4204d56320" />

**Paper** category brought the most profit in Office Supplies.

<img width="440" height="367" alt="image" src="https://github.com/user-attachments/assets/8ff61eb0-68e9-4f96-adbe-78473302ebf0" />

**West** region brought the most profit in Office Supplies.

<img width="1474" height="379" alt="image" src="https://github.com/user-attachments/assets/9180b70e-d583-4989-8db4-23abb240a352" />

**Consumers** brought the most profit in Office Supplies.

<img width="1714" height="786" alt="image" src="https://github.com/user-attachments/assets/0886d116-1ec1-4815-a9c4-b0f426873335" />

**California** state brought the most profit in Office Supplies.

--- 

<a id="future-considerations"></a>
**Future Considerations**
- Create a time series of the office supplies to determine which season would be most profitable.
- Interact with the map by state to determine the profit and sales by category and customer segment.  

Thanks for reading! 🛒
