p8105\_final\_project\_BF
================
Xiaoyue Zhang, Jieqi Tu, Hongyao Xie, Mengran Ma, Bingyu Sun
11/6/2018

Proposal
--------

### Section 1

-   **Group members**

Bingyu Sun (bs3142), Hongyao Xie (hx2264),

Jieqi Tu (jt3098), Mengran Ma (mm5354),

Xiaoyue Zhang (xz2788)

-   **The tentative project title**

Assessing Hospitals Based Medicare Factors by State in U.S.

-   **The motivation for this project**

1.  explore different aspects of hospitals including facilities, health workers, infection risk, etc. by state unit and overall distribution in U.S.

2.  study diseases and cause of death through United States in order to establish leading causes and expenses of staying in hospitals from patients' aspect.

3.  establish regression models of the trend of medicare expenses and other factors to predict future changes and bring up suggestion for hospital improvement.

### Section 2

-   **The intended final products**

A github.io website containing all the analyses and information about our final project, which includes the following:

1.  Plots and tables that may help us better understand diseases and certain causes of death through whole United States in order to establish leading causes and expenses of staying in hospitals from patients' aspects.

2.  Statistical summaries/numerical values and perhaps in combination with geographical maps for summarizing various aspects of hospitals including facilities, enviroment, infection risk, etc. by state this unit and overall distribution across the U.S.

3.  Regression model/analyses where we are trying to predict if there is any trend for associations between medicare expenses and other factors, in order to see/forecast future changes and bring up suggestions for hospitals' potential improvements.

-   **The anticipated data sources**

The black Friday dataset(<https://www.kaggle.com/mehdidag/black-friday>) derived from kaggle was generated in a competition hosted by Analytics Vidhya. This dataset is a sample of the transactions made in a retail store, which aims at understanding the customer purchase behaviour against different products.

The deals dataset(<https://www.bfads.net/forums/viewtopic.php?f=25&t=35040>) from BFAds.net contains up-to-date 2018 Black Friday deals, which could be a potential source for analyzing featured offers and latest hot sales on Black Friday at well-known stores, such as BestBuy, Targets, and Walmart.

### Section 3

-   **The planned analyses / visualizations / coding challenges**

1.  **The planned analyses**

For all rankings and graphing: specify hospital ownership (Government, Proprietary, Voluntary non-profit), hospital type. (Acute Care Hospitals etc.)

Since there is only overall rating for hospitals, we would like to re-classfy hospitals based on factors of interest to illustrate hospitals' strength and weakfulness in different aspects.

-   Ranking hospitals based on the overall assessment, such as mortality, safty of care, patients experiences etc. (Data: Hospital General Information)

-   Ranking hospitals based on Hospital Consumer Assessment of Healthcare Providers and Systems (HCAHPS) Patient Survey. (Data: HCAHPS)

-   Ranking hospitals based on facilities provided. (Data: Structural Measures)

-   Ranking hospitals based on effectiveness of different services including emergency, Heart Attack or Chest Pain, Blood Clot Prevention and Treatment etc. (Data: Timely and Effective Care - Hospital)

1.  **Visualizations**

-   Boxplots comparing effectiveness of different services among hospitals.

-   A map demonstrating infrastructures and facilities provided by different hospitals grouping by pre-specified levels, with label illustrating hospital ownership, and different scores.

-   A bar chart revealing the proportion of hospitals (by overall rating) facet by different factors, indicating whether they are below, average, or above national average. (Data: Hospital General Information)

-   A map visualizing hospital rating by patient, classfying hospitals based on patients' response.

-   Overall theme: adding custom controls, like **dropdown events** allowing selection of specific rating, region etc, and **range sliders and selectors** zooming in and out to show data for each hospital when zoomed in.

1.  **Coding challenges**

    1.  For visualization:

    -   Making a map consists of different levels (ranking) may be challenging.

    1.  For data manipulation and tidying:

    -   Propor ways of classfying hospitals by different measurements can be difficult, may need to merge different datasets, mutate variables using nest and write functions.

2.  **The planned timeline**

    -   Week 1: Data cleaning; Data exploring; Discussion on work splitting.
    -   Week 2: Data analysis and group meetings on revisions.
    -   Week 3: Plots making and group meetings on revisions.
    -   Week 4: Website building and dashboard making; In-class discussion with other gourps.
