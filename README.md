# Dashboards

## **Yandex Datalens**:
#### **Dataset**: New York City Airbnb Open Data (https://www.kaggle.com/datasets/dgomonov/new-york-cityairbnb-open-data)

#### **Dashboard name**: Airbnb in New York: Dashboard for Investors, Hosts & Property Buyers

#### **Link to the dashboard**: https://datalens.yandex/thr6l9ap14iqh

#### **Goal of the dashboard**: to provide an overview of the Airbnb market to investors, realtors and potential
buyers of housing for future rental. The dashboard should help identify trends and patterns in the data,
allowing you to make decisions about housing prices, marketing strategies depending on demand at the
point, purchase, opening of new rental points or their closure.
Main KPIs: price and occupancy, housing availability.

#### **Structure of the Dashboard**:
The two graphs on the left present information on the aggregated prices; the two charts in the middle
show occupancy and housing availability; the chart on the right shows statistics on homeowners:
![image](https://github.com/tivakhrusheva/Dashboards/assets/91075802/fd51008f-2ba1-4db7-9019-6db57a87a0c0)
![image](https://github.com/tivakhrusheva/Dashboards/assets/91075802/01379f83-463c-4dbc-bf15-9db4f4f2ce2b)

### Charts’ Description:
1. **Price by Room & Neigbourhood Type** – a bar chart showing aggregate prices by
Neighborhood Group with an additional split by housing type. One could select the option
only for one Neighborhood Group or one type of housing by setting the appropriate filters.

![image](https://github.com/tivakhrusheva/Dashboards/assets/91075802/c8c63df2-c888-4ca9-826b-886bcd0a775e)

2. **Heat Map: Price** – a heat map, showing the aggregated cost of housing on a map of New
York. As in the graph above, it is possible to set filters for a type of housing and
Neighborhood Group, as well as add a selection of aggregation type. Geodata was used for
the calculation, and an aggregation option and a cost variable were used to reflect density
as a colour:

![image](https://github.com/tivakhrusheva/Dashboards/assets/91075802/0f4b6a5f-3ed6-4290-8209-5cdf2e9efb94)

3. **Number of Listings by Neigbourhood Group & Room Type** – a bar chart showing the
number of different types of housing by Neighborhood Group:

![image](https://github.com/tivakhrusheva/Dashboards/assets/91075802/9c0330cc-4738-4503-b162-825296ea47f8)

4. **Neigbourhoods by Yearly Availability** – a bar chart showing the aggregate yearly number of
days of housing availability in each of the Neighborhood and Neighborhood:

![image](https://github.com/tivakhrusheva/Dashboards/assets/91075802/576157a1-250a-4e85-9ea4-9b091b8d52fa)

5. **Hosts’ Statistics** – a plot of top-homeowners on one of the two metrics: the number of
listings they own and the number of reviews of their homes. For filtering, the built-in Rank
function was used according to the selected metric:

![image](https://github.com/tivakhrusheva/Dashboards/assets/91075802/34359d6e-42db-4d8e-b441-db37a7fa897e)

### **Parameters**:
- **Aggregation Type** – the type of aggregation used for quantitative variables: mean, median,
minimum, maximum, and sum. The default mode is average; It is possible to select only one
value:

![image](https://github.com/tivakhrusheva/Dashboards/assets/91075802/d40762be-94b8-4d4e-9223-7ecf46cfef9b)

**Why**: only one available aggregation mode can distort the visibility of the data distribution, for
example, due to the outliers, so it is important to be able to look at the data using different
types of aggregation.

- **Entity to Show** – chart display option for housing affordability graph
1) Showing aggregated values for each Neighborhood indicating the Neighborhood Group using
color highlighting:

![image](https://github.com/tivakhrusheva/Dashboards/assets/91075802/38aa17a7-7e8b-4779-a130-ffd35279908f)

3) Showing aggregated values only for the Neighborhood Group without breaking down into
constituent areas or districts:

![image](https://github.com/tivakhrusheva/Dashboards/assets/91075802/203bc54f-7179-441a-a674-15a5856511aa)

**Why**:
1. There is a lot of Neighborhoods in the data, which can make it difficult to perceive data;
2. To understand which specific Neighborhood and Neighborhood Group are the most and least busy; be
able to evaluate both general and specific indicators.

### **Filters**:

- **Room Type** – type of housing for which graphs are drawn:
  
![image](https://github.com/tivakhrusheva/Dashboards/assets/91075802/6e53fafb-763a-4291-b716-953064ef8f10)
  **Why**: to evaluate data for a specific housing type.
  
- **Neighbourhood Group** – the area or district for which the graphs are built:
  
![image](https://github.com/tivakhrusheva/Dashboards/assets/91075802/6a6ac73b-8946-4696-bee6-a44b12d8e153)

**Why**: to evaluate the data for a specific district or area.
  
### **Calculated fields**:
**Field for Top-Statistics** – one of two possible metrics, according to which statistics are dynamically built
for the top 5 homeowners:

![image](https://github.com/tivakhrusheva/Dashboards/assets/91075802/9d4c7cb8-ed5e-4c18-bf1e-02028cc15694)

**Why**:
1. To be able to avoid building a graph of the same type for one entity, but with different metrics twice;
2. To be able to quickly switch from one metric to another and see the difference on the same graph.

## **Tableau**
#### **Dashboard Title**: Data visualization for realtors, investors and potential homebuyers on Airbnb in New York

#### **Data**: https://www.kaggle.com/datasets/dgomonov/new-york-city-airbnb-open-data

#### **Dashboard link**: 
https://public.tableau.com/trusted/AwTVggv1RkiaFrSMltiMJg==:Cs2dYa913BNeO5bA39hcXBRQ?:redirUrl=%2Fprofile%2Fapi%2Fpublish%2FAirbnbinNewYorkDashboardforInvestorsHostsPropertyBuyers_17026731022 110%2FDashboard

The purpose of the dashboard: to provide an overview of the Airbnb market to investors, realtors and potential buyers of housing for future rental. The dashboard should help identify trends and patterns in the data, allowing you to make decisions about housing prices, marketing strategies depending on demand at the point, purchase, opening of new rental points or their closure.

### **Graphs and diagrams**:
1. Price statistics by neighborhood group type;
2. Reflection of the variation in median price by location on the map;
3. Number of housing in each neighborhood group;
4. Sorting the neighborhood group by housing availability throughout the year.

### **Filters**: type of housing, location when selecting a point on the map.
These filters allow the user to select the type of housing and location on the map to obtain accurate statistics on housing prices. This is useful, for example, if the user wants to find out the average price for an apartment in a certain area of the city or compare prices for houses and apartments.

### **Options**: aggregation type to display housing price statistics
Central tendency measures -- mean, median, minimum or maximum.
Aggregation options allow the user to choose which statistics to use to display home prices. The average can be useful to understand the overall price trend in the real estate market, while the median can be useful to understand which home prices are most common.

### **Actions**:
Filtering all graphs by housing type, highlighting the selected housing type. I considered them useful for the same reasons as filters

