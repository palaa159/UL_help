<!-- 

### for Root
#### for sub-menu
##### for sub-menu list


-->
# Help

### About CITYSCAPE POC
===

##### Business Case

Unilever stands to capture €2 billion in new turnover globally by addressing its fair share of trade in cities. Data-driven decision making is going to help Unilever get there. 

CITYSCAPE is Unilever’s purpose-built Big Data integration, analytics, and visualization platform for Perfect Cities. It is designed to help BB, BD, CD, CMI, and Media make smart, granular, in-time decisions about where to play and how to win at the city level. 

##### Where We Are

You are looking at a Proof of Concept (POC) of CITYSCAPE. Designed and developed over four months, it demonstrates the potential of a productionised version of the system and serves as a tool to gather feedback from various stakeholders to guide the next phase of development. 

As a POC, its scope and functionality has been intentionally constrained. These constraints include:

1. Location: The POC covers London

2. Products: The POC includes two product categories – Ice Cream and Hair

3. Time: The POC includes data from July 2014 

4. Functionality: The POC demonstrates basic visualization and analytics functionality. 

These constraints will all be lifted in the next phase of development. The Beta version of CITYSCAPE will be category-, feature-, and data-complete and scalable to other cities.

The POC integrates — for the first time ever at Unilever — data from over a dozen disparate sources [link to full list at bottom of page] to establish a unified and multi-faceted view of our business in London. 

The project is governed by a cross-functional Steering Committee spanning all of these business areas together with ETS.

### Features in the POC
===
<!-- 
**Overall Interface**

CITYSCAPE’s interface includes two main components: 

1. Map Interface

2. Analytics Modules
-->

#### Map Interface
<!--

- Overview
- Layer Types
- Functionality

-->

##### Overview

CITYSCAPE’s map is your entry point into the system. The map allows you to create layers from any selection of the system’s available data. Once layers are created, you can visualize and compare up to five at a time. Juxtaposing layers will help you spot geographic correlations and form hypotheses about potential relationships within the data.

##### Creating Layers

To create a layer select the +Add Layer [ADD ICON] at the top left of the CITYSCAPE interface; this will activate the Layer Selection Menu where you can select the relevant data, filters, and contexts for creating a new layer.

Selecting a data set

* From the Layer Selection Menu select a data set. Data sets are organized by subject and by vendor

* Subjects include:

	* Sales
		* Data on individual store- and product-level Unilever Sales (EPOS)
    * People
		* Demographic, economic, social, and wellness indicators
    * City 
		* Data on the build environment of the city including Underground Routes and Parks
	* Market Share
		* Unilever’s Market share by product category
	* Vendors include
        * Galileo
        * Twitter
        * Vodafone
        * Google Search
        * Mindshare

For some subjects – including People and City, you will need to select the specific data set you wish to use for the layer

Once you have selected a data set, a side panel with applicable Attributes, Units, Normalizations, and Filters will appear. 

* Attributes

    * A set of options endogenous to the data set that constrain the sample of data from the selected data set

    * Example: Brand, Product Quantity

* Normalizations

    * Specific data sets have the option to normalize to control for for variables like population

    * Example: Population

* Filters

    * A set of conditions exogenous to the data set that constrain the sample of data

    * Examples: Time, weather  

##### Geography Selection

Once you have made all relevant selections from the side panel, select the Geographic Unit [ADD ICON]  for the layer. The toggle can be used to select either Boroughs or Wards. Note that some data sets can only be displayed as Boroughs. If you have selected a data set that can only be displayed as a Borough, the Ward option will be disabled.

##### Layer Types

Once the data set, characteristics, and geography for you layer have been selected, you can choose the Layer Type you would like to produce. Types include:
<!--make table here-->
* **Choropleth** [Logo: CHOROPLETH]

	* Aggregates selected values within a geographic unit and shades the unit based on the value of the selected variable
	
    * Example: Population by Ward

* **Bubbles** [LOGO: BUBBLES]

	* Aggregates selected values within a geographic unit to create proportionally sized bubbles  based on the values of the selected variable

    * Example: Total sales of Tesco stores by Borough

* **Points** [LOGO: POINTS]

    * Maps the location of selected entities – such as stores. 

    * Example: Location of convenience stores

* **Polygons** [LOGO: POLYGONS]

    * A layer mapping geographic attributes about the city

    * Example: Underground routes and station locations

Note that some data sets can only be produced as specific layer types. If one of these data sets is selected, the unusable layer types will be disabled.

##### Adding a Layer to the Map

Once you have completed all your selections, click Add Layer to Map [INSERT ICON] to visualize the layer.

##### Manipulating Layers

To manipulate any layer begin by selecting the Layers Icon [INSERT ICON] at the top right of the Map Interface. Once the cursor is over the icon, a menu will expand that shows all of the layers that are currently available. 

* **Activating/Hiding a Layer**

	* Click on the check box [ADD ICON] on the left side of the menu to activate or hide a layer

* **Changing Layer Ordering**

    * Click the  [ADD ICON] icon on the far right of the menu to move the desired to the top of the map

* **Deleting a Layer** 

    * Click the x [ADD ICON] on the far right of the menu to delete a layer

##### Zoom/Pan

* Zoom by either using +/- [ADD ICON] at the top left corner or the map interface, or by using the scroll wheel on your mouse

* Pan across the map by clicking and dragging the map to center it on your desired view

##### Resetting the Map

* Reset the map by selecting the Reset Map [ADD ICON] button at the top right corner of the CITYSCAPE interface

#### Analytics

##### Overview

CITYSCAPE’s Analytics Modules help you answer complex questions about any filtered selection of any data set within the platform across five different types of analysis. Within the POC, available types of analysis include:

* **Distribution**

	* Make up to four selections to compare a set of variables as a grouped bar chart across Boroughs, time, or weather

* **Correlation**

	* Make two selections to produce a scatter plot to test the linear correlation of two variables

* **Trends**

	* Make up to four selections to produce line graphs grouped over context variables including time and weather

* **Ranking**

	* Make up to four selection to produce a ranked grouped bar chart across Boroughs, time, or weather

* **Sample Advanced Analytics Module: Clustering**

	* Analyze how multiple variables – including sales by category and retailer – create clusters of stores in a network visualization

##### Initiating CITYSCAPE’s Analytics

To initiate the functionality CITYSCAPE’s Analytics, select the analytics module you would like to use from the menu below the Map Interface. Once you have selected an analytics module, the Data Selection Panel will generate. This panel will help you select your desired components from a data set with criteria including attributes, filters, units, and normalization. 

##### Data Selection Panel

For all types of analysis (excluding Correlation), you have the option of selecting up to four components for the Y-axis. Each component consists of a set of criteria and filters. 

Specific to each data set, the **"Add Y data"** drop down menus help you select any attributes you want to filter from the selected data set. For example, for a data set like sales, this includes the attributes of brand, quantity, category, subcategory, channel, and retailer

Once the user selects these criteria, these results can be further filtered by external context variables including weather, location (e.g. a single Borough), and dates.

After all criteria for a component are selected click **"Load Criteria"** to add the component to the axis.

For Correlation Analysis, you must select two components – one for the X-axis and one for the Y-axis

##### Setting Unit and Normalization

After you have selected all of the desired components for an axis select your desired Unit and Normalization for the graph

##### Comparing Selection to UK and London

Each Analytics Type provides the option of comparing selected data to the same variable for all of London and the UK. To include this comparison on any of the graphs select the **"Include London and UK"** check box.

##### Visualizing Analysis

Once all selections are complete, click Visualize [ADD ICON] to create the graph.

### Getting Started with the POC
===

CITYSCAPE’s POC is designed to demonstrate how the future production version of platform will guide granular, in-time decision making around Unilever’s strategic priorities including:

* **Right Cities**

	* CITYSCAPE will help Unilever analyze its market share and calculate the size of prize within and across cities

* **Right Channels/Stores**

    * CITYSCAPE enables detailed analysis of the performance of every channel and store that sells Unilever products within a city    

* **Right Partners**

    * Identifying specific locations and consumption triggers to build partnerships that increase Unilever’s sales

* **Right Brand Building**

    * Identifying target demographics/segments/individuals, locations, and times to maximize the impact of Unilever’s marketing and media activities

* **Right Ecommerce/Digital**

    * Understanding the distribution of Ecommerce and digital activity throughout a city

* **Right USLP**

    * Leveraging open data, CITYSCAPE will help Unilever identify the right issues and places to maximize the impact of USLP initiatives

The following user journeys demonstrate how the functionality of CITYSCAPE will help Unilever make measurable progress on these defined strategic priorities.

#### Geographic Lenses	

Strategic Priorities Supported Right Cities, Right Brands, Right Channels

Target Users: Brand Managers, Customer Development

##### Overview

CITYSCAPE can help multiple types of users – including CD, BB, BD combine sales, demographic and market data to identify to identify target consumers for specific brands, and find the, best channels and stores and times for reaching a specific population.

Starting with the Analytics Modules, select Correlation. From the Data Selection Panel select Student Population from the data drop down menu for the Y-Axis and Magnum Sales at Convenience stores for the X-Axis. Visualize this selection. (note, we are making the assumption that you have spent some time in CITYSCAPE testing correlations to find this one). [SCREENSHOTS OF BUILD PROCESS]

You can see that there is a strong correlation between Student Populations and the Sales of Magnum products at Convenience Stores. 

Next, you can switch to the Map Interface to build the same selections as Layers on the map. 

First, you can create a layer showing the distribution of the Student Population across Boroughs as a choropleth.

[Screenshots of first layer build]

Next, create a bubble layer showing the value of Magnum Sales at Convenience Stores by Borough.

[Screenshot of second layer build]

From utilizing the correlation module and creating this visualization, you have confirmed the existence of a relationship between two variables, and identified specific geographies whose performance – for a specific product – could likely improve.

#### London Value Exchange

Strategic Priorities Supported: Right People, Right Brand

Target Users: Brand Managers

##### Overview

CITYSCAPE can help Brand Managers identify new opportunities to build partnerships that deliver new types of value to people through a Unilever brand. For example, a Brand Manager could target the most tourist-dense areas in London n as a starting point for building partnerships with tourist attractions to subsidize/connect an experience and a Unilever brand.

Starting from the Map Interface click on the Add Layer Button and select People data to create a choropleth layer showing the distribution of tourists [SHOW SCREENSHOT]

Next, create a bubble layer visualizing the sales of ice cream through convenience store channels by Ward. [SHOW SCREENSHOT]

Finally create point layers to plot the locations of both convenience stores of large retailers and mom & pop stores. [SHOW SCREENSHOTS]

Layering the distribution of a target population – tourists – with filtered sales data and the location of all relevant points of sale, a Brand Manager can start to analyze portions of London where there is a high density of a target demographic, but lagging sales performance. From these areas, the Brand Manager could start to identify the specific stores, or locations of attractions Unilever could partner with to increase sales performance.

#### Healthy Living

Strategic Priorities Supported: USLP

Target Users: USLP Managers

##### Overview

CITYSCAPE can utilize open demographic data to help a USLP manager maximize the impact of USLP through analyzing how key health trends impact different areas of the city and developing/launching geographically campaigns.

[SCREENSHOT of DATA SELECTION MENU IN CONTEXT OF PLATFORM] 

Starting in the Map Interface select the People category from the menu. From this category, select a range of demographic data sets from categories including language/ethnicity, economic, and wellness.

Since we are focused on health, select the layer for **"% of 6-year-old children that are obese"**. [SCREENSHOT OF SELECTION of DATA SET] Once the data set is selected, click on the choropleth [ADD LOGO] layer type option and click visualize to send the layer to the map.

CITYSCAPE also contains datasets about locations and infrastructure of the city. To create another layer, return to the add layer menu and select the **"City"** category. [SCREENSHOT SHOWING SELECTION]

From this category select Schools; confirm that this selection will be visualized as points and send the layer to the map.

[SCREENSHOT OF BOTH LAYERS ON MAP]

Now you can see the incidence of childhood obesity by Borough with the locations of all primary schools within the city. From a USLP perspective, a USLP Manager could target specific schools in a Borough with a high-obesity rate to launch a program about nutrition.

### Data Sets Utilized
===

* Proprietary

	* Product Metadata

	* Store Metadata

* Purchased

	* EPOS from 6 Customers (Tesco, Sainsbury’s, Waitrose, ASDA, Morrisons, Boots)
	
	* Kantar TGI 
	
	* Nielsen Market Share 
	
	* GfK/Vodafone
	
	* Galileo 
	
	* Google Search
	
	* Mindshare

* Social/Exhaust

	* Twitter
	
	* Foursquare

* Open

	* London Maps (Boroughs/Wards)
	
	* Demographic (e.g. age, ethnicity)
	
	* Economic (e.g. housing, income)
	
	* Weather 
	
	* Transportation Networks
	
	* School Locations

