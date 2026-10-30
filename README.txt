  
  Q)  what is Data Anylatics ?


"Data Analytics is the science of analyzing raw data to make conclusions about information, solve business problems, and drive strategic decisions using tools, statistical models, and visualization techniques."

  Q)  what is the working any firm/com/indu to Data Anylatics ?

companies ke paas hazaron, lakho customers ka data hota hai (jaise sales ka record, website ka traffic, user behavior, waghera). Ek Data Analyst ka kaam ye hota hai ke wo is bikhre hue data ko samajh kar management ko ye bataye ke. Example: Company ka sales data analyze karke pata lagana ke kis product ki sales zyada hai aur kis month mein profit kam hua.


Business mein kahan loss ho raha hai aur kahan profit?

Agle mahine ya saal sales ko kaise barhaya ja sakta hai?

Customers ki aisi konsi zarooratein hain jo poori nahi ho rahin?

Data Analytics ka matlab hai raw data ko collect, clean aur analyze karke useful information nikalna, taake business better decisions le sake.


=============================     Data Analytics     =============================

=======   Step 1: Data Collection

Different sources se data collect karna, jaise Excel, CSV files, databases aur company systems.


=======   Step 2: Data Cleaning

Missing values, duplicate records, spelling mistakes aur incorrect data ko fix karna.
Tools: Python, Pandas, NumPy, Excel.


=======   Step 3: Data Manipulation

Data ko filter, sort, merge aur transform karna, taake analysis ke liye ready ho.
Tools: Pandas, NumPy, SQL.


=======   Step 4: EDA & Statistical Analysis

EDA (Exploratory Data Analysis) mein data ko explore karke patterns, trends aur problems identify karte hain.

Statistics: Mean, Median, Mode, Standard Deviation.
Tools: Python, Pandas, NumPy, SciPy, Excel.


=======   Step 5: Data Visualization

Charts, graphs aur dashboards ke through results ko easy way mein present karna.
Tools: Matplotlib, Seaborn, Power BI, Tableau.


=======   Step 6: Insights & Reporting

Analysis ke results se business ko recommendations dena aur reports share karna.
2. Data Cleaning Python se kaise hoti hai?
Real-world data aksar clean nahi hota. Python ki libraries use karke hum data clean karte hain.

import pandas as pd

data = {
    "Name": ["Ali", "Sara", "Ali", None],
    "Sales": [5000, 7000, 5000, 4000]
}

df = pd.DataFrame(data)

# Remove duplicate rows
df = df.drop_duplicates()

# Remove rows with missing names
df = df.dropna(subset=["Name"])

print(df)



Important libraries:


- Pandas: Data cleaning, filtering, manipulation aur analysis.
- NumPy: Numerical calculations aur arrays.
- SciPy: Statistical tests aur scientific calculations.
- Matplotlib: Basic charts aur graphs.
- Seaborn: Statistical aur attractive visualizations.


3. Data Visualization kya hai?


Data ko charts aur graphs ki form mein show karna, taake user easily samajh sake.

Bar Chart:
Different products ya months ki sales compare karne ke liye.
Line Chart
Time ke sath sales ya profit ka trend dekhne ke liye.
Heatmap



4. Descriptive Statistics kya hai?


Descriptive Statistics data ko numbers ki help se summarize karti hai.

Example: Sales = 100, 200, 300
Term	Easy meaning	Result
Mean	Average	200
Median	Beech wali value	200
Mode	Sab se zyada repeat hone wali value	Koi mode nahi



5. Excel vs Python vs SQL

Technology	Kis kaam ke liye?
Excel	Small/medium data, formulas, PivotTables, basic EDA
Python	Data cleaning, automation, complex analysis, visualization
SQL	Database se data retrieve, filter, join aur aggregate karna
Power BI	Interactive dashboards aur business reports
Tableau	Data visualization aur dashboards

Note: Excel ki 1 lakh rows ke baad lazmi slow hone ki koi fixed limit nahi. Performance computer, formulas aur data model par depend karti hai. Excel worksheet ki maximum limit 1,048,576 rows hai.
SQL mein kaun si technologies hoti hain?
- Languages: SQL, T-SQL, PL/SQL.
- Database systems/servers: MySQL, PostgreSQL, Microsoft SQL Server, Oracle Database.
- SQL tools: MySQL Workbench, SQL Server Management Studio (SSMS), pgAdmin.
SQL ek query language hai; MySQL aur PostgreSQL database management systems hain.



6. Industry mein Data Analyst ke liye kya requirements hain?

Skill	Industry mein use
Excel	Data handling aur reports
SQL	Databases se data nikalna
Python	Pandas, NumPy aur automation
Statistics	Mean, Median, Mode aur trends
Power BI / Tableau	Dashboards aur visualization
EDA	Data mein patterns aur issues find karna
Communication	Results ko business team ko explain karna

Additional skills mein data quality, problem-solving, business understanding aur basic Git knowledge bhi helpful hain.

Recommended learning order: Excel → SQL → Statistics → Python (Pandas, NumPy) → EDA → Power BI → Projects.											
================================================================================================						
Data Analyst ko kaun kaun se departments hire karte hain?
- 🏦 Banking                                 ==   Financial Data Analyst
- 🛒 Retail (Imtiaz, Bin Hashim, Carrefour)  ==  Retail Data Analyst
- 📦 Logistics                               ==  Operations Analyst
- 🛍 E-commerce                              ==  Marketing Data Analyst / Supply Chain Analyst
- 📱 Telecom
- 🏥 Healthcare                              ==  Healthcare Data Analyst / HR Data Analyst
- 🏭 Manufacturing                           ==  Supply Chain Analyst / HR Data Analyst
- ✈️ Airlines                                ==  HR Data Analyst
- 💻 Software Houses                         ==  Product Analyst

Sabse zyada demand wali specializations
1. BI Analyst
2. Financial Data Analyst
3. Retail Data Analyst
4. Product Analyst
5. Supply Chain Analyst
6. Marketing Data Analyst

Har jagah data hota hai, is liye har industry ko data analyze karne wale professionals ki zarurat hoti hai.================================================================================================================

Programming : Its a set of instruction

Categories of programming:
1) High Level Programming (Python, JS, C#, C++, PHP, Java , Pascal , R )
2) Low level programming (Assembly Language)
3) Machine Language ( 1 & 0)

Translation :
1) Compiler : pory code 1 time translate krta ha
2) Interpretor  : line by line translate (left to right) = python Interpretor ha
3) Assembler: 



# --------------------------------python  online  compiler-------------------------------

# .py mtlb python extension  

print("Hello Anas")

# built in function 

# print()

#  str() 
#  int()
#  float()



# data types 

# "anas" = string data types 
# 123 = int data types 
# 43.09 = float dta type

# check data type function 

print(type(123))

# simple operation perform

print(200 + 400)     # add kia
print("200" + "400")  # concatination krdya

#    typeCasting

#  str() 
#  int()
#  float()

print(int(10.00)) # float ko int me convert kia type casting sy


---------------- How To DownLoad The Anaconda In Your System ---------------- ??


is k andr multiple software hoty hn "jupyter notebook" "pycham" etc hm Anacoda ma jupyter notebook k sath jyengy or kam vs code or online compiler pr bh ho jta ha.
 
"search anaconda.com"  then resources ma download distribution or download option show hoa submit k neechy skip reg  kr k 
"distribution installer" or "miniconda installer" 2 hongy tw hm  "distribution instal" or jo system ha windows mac Linux wohi click kr den window ha
tw "window 64bit"  download kr k install krlengy..       then

1 website ha geeksforgeeks or lakin apny search krna ha "how to install anaconda on windows" or isme step by step guide kia ha kis trhn 
download hogi or installing setup. 

downl folder ma agya double click or 64bit next license i agree next just me nexr next register anaconda sy check hta do "Add anaconda to my path environment variable" pr check lgao next next finsh  then
check kaise krna hoga ha search bar ma anaconda prompt enter or check "python --version" "conda --version" only enter kr k pyhton andr
chla sakte hn exit

easiest way to open jupyter notebook.
'create folder' & click 'folder path' & write "cmd" enter & then "jupyter notebook" enter 
 Home screen open hogi right ma "new" ka 1 option hoga 
"python 3 (ipykernel)" click krlyn ipy extension ha yeh new file or folder bh bn jtyn hn