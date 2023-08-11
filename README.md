# supplychain  

DataCo Supply Chain  
This datasets of Supply Chains used by the company DataCo Gloal was used for the analysis.  

Areas of important registered activities :  
-Provisioning  
-Production  
-Sales  
-Commercial Distribution  
It also allows the correlation of Structured Data with Unstructured Data for knowledge generation.  

Type of Products :  
Clothing  
Sports  
Electronic Supplies  

**Acknowledgements & Source  
Fabian Constante  
Instituto Politecnico de Leiria Escola Superior de Tecnologia e Gestao  
Contribution: Master interested in topics related to Big Data  
Fernando Silva, António Pereira**  

**https://data.mendeley.com/datasets/8gx2fvg2k6/5**  

-------------------  
*Some visualizations that use Plotly might not appear. Therefore, I suggest manually downloading them if you wish to view the results.*  

1. The first step, i need to import and show how the data structured.    
   1.1 In this case i used `read_csv` and `info()`  
   1.2 Also check on the total of null values in columns, so i use `isnull().sum()`  
2. The step to is merge some column, but in this scenario i'm just merge for First Name and Last Name and then check it again using `info()`  
3. This third step is to make the datasets easier to read and using `drop()` function to eliminate unused columns  
4. Check the descriptive statistics with `describe()`  
5. After that we also can create some visualization, but at this scenario i'm show only few of them.  
   5.1 **Top 5 Revenue by Product Category**  
   5.2 **Top 5 Item Sold by Product Category**  
   5.3 **Revenue by Shipping Mode**  
   5.4 **Analyzing Average Sales by Product ID**  
   5.5 **Analyzing Order Quanitity by Product ID**  
   5.6 **Analyzing Each Cost of Shipping Mode**  
   5.7 **Analyzing Average Benefit per order of Shipping Mode**  
   5.8 **Analyzing Delivery Status of Category Name**  
-------------------
