**Honolulu Data Science Meetup - Thursday November 16**

Bob Hiltner will demonstrate live how to build an analysis dashboard from scratch in Tableau. Using variable parameters and filters, see how Tableau brings a tabular dataset into a beautiful and useful visual framework that gives you a compelling way to tell your data's story.

**Description of "World Health Indicators - Fertility & Longevity"**
Fertility Rate (Data (Fertility-Rate)) vs. Life Expectancy at Birth (Data (Life-Expectancy-At-Birth)).  Color shows details about Region (Metadata - Countries (Country-Metadata)).  Size shows Population.  Details are shown for Country Name (Metadata - Countries (Country-Metadata)). The view is filtered on Region (Metadata - Countries (Country-Metadata)), which excludes Null.
Marks

The mark type is Circle.
Stacked marks is off.

**Shelves**

**Pages:**
Year
**Rows:**
Life Expectancy at Birth
**Columns:**
Fertility Rate
**Filters:**
Region
**Level of detail:**
Country Name
**Color:**
Region (Metadata - Countries (Country-Metadata))
**Size:**
Population

**Dimensions**
Country Name (Metadata - Countries (Country-Metadata)) has 212 members on this sheet
Members: Afghanistan; Albania; Andorra; Angola; Aruba; ...
Region (Metadata - Countries (Country-Metadata)) has 7 members on this sheet
Members: Europe & Central Asia; Latin America & Caribbean; Middle East & North Africa; South Asia; Sub-Saharan Africa; ...
Year has 54 members on this sheet
Members: 1960; 1961; 1962; 1963; 1964; ...

**Measures**
Life Expectancy at Birth (Data (Life-Expectancy-At-Birth)) ranges from 19.50 to 83.83 on this sheet.
Fertility Rate (Data (Fertility-Rate)) ranges from 0.836 to 9.223 on this sheet.
Population ranges from 4,279 to 1,357,380,000 on this sheet.

**Data Source Details**

**Data Source:**
Data (**Country-Population**)
Type:
federated
Table:
Data$


**Data Source:**
Data (**Fertility-Rate**)
Type:
federated
Table:
Data$

Data (Fertility-Rate) is grouped by Year, and joined to Data (Country-Population) using Year.

**Data Source:**
Metadata - Countries (**Country-Metadata**)
Type:
federated
Table:
'Metadata - Countries$'

Metadata - Countries (Country-Metadata) is grouped by Country Name, and joined to Data (Country-Population) using Country Name.

**Data Source:**
Data (**Life-Expectancy-At-Birth**)
Type:
federated
Table:
Data$

Data (**Life-Expectancy-At-Birth**) is grouped by Year, and joined to Data (Country-Population) using Year.
