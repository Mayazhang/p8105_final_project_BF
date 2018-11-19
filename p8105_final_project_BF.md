p8105\_final\_project\_BF
================
Xiaoyue Zhang, Jieqi Tu, Hongyao Xie, Mengran Ma, Bingyu Sun
11/6/2018

Proposal
--------

-   **Group members**

Bingyu Sun (bs3142), Hongyao Xie (hx2264),

Jieqi Tu (jt3098), Mengran Ma (mm5354),

Xiaoyue Zhang (xz2788)

-   **The tentative project title**

Ecologic study of association between crime rate and drug use in U.S.

-   **The motivation for this project**
-   Explore the association between rate of different types of crime and abuse of four kinds of drugs and build a regression model for different crimes by state level.
-   Study distributions of crimes and drug use in each state and conclude which pair of crime and drug use is highly related in each state
-   Analyze data from 2002 to 2016 to conduct hypothesis test of the trend of crime rate and drug use as well as to make predictions.
-   Draw a map across U.S. about detailed data of crime rate and drug use in each state

-   **The intended final products**

A github.io website containing all the analyses and information about our final project, which includes the following:

1.  Plots and tables that may help us better understand diseases and certain causes of death through whole United States in order to establish leading causes and expenses of staying in hospitals from patients' aspects.

2.  Statistical summaries/numerical values and perhaps in combination with geographical maps for summarizing various aspects of hospitals including facilities, enviroment, infection risk, etc. by state this unit and overall distribution across the U.S.

3.  Regression model/analyses where we are trying to predict if there is any trend for associations between medicare expenses and other factors, in order to see/forecast future changes and bring up suggestions for hospitals' potential improvements.

-   **The anticipated data sources**

The latest version of hospital compare datasets from Data.Medicare.gov will be analyzed in this project. The Medicare is a federal government website managed by the Centers of Medicare & Medicaid Services in Baltimore which aims at providing official data concerning health-related topics. The hospital compare datasets primarily focus on the quality of healthcare at over 4000 Medicare-certified hospitals across states.

#### The planned analyses / visualizations / coding challenges

**The planned analyses**

-   For all rankings and graphing: specify hospital ownership (Government, Proprietary, Voluntary non-profit), hospital type. (Acute Care Hospitals etc.)

-   Since there is only overall rating for hospitals (Data: Hospital General Information), we would like to re-classfy hospitals based on factors of interest to illustrate hospitals' strength and weakfulness in different aspects.

-   Ranking hospitals based on Hospital Consumer Assessment of Healthcare Providers and Systems (HCAHPS) Patient Survey. (Data: HCAHPS)

-   Ranking hospitals based on facilities provided. (Data: Structural Measures)

-   Ranking hospitals based on effectiveness of different services including emergency, Heart Attack or Chest Pain, Blood Clot Prevention and Treatment etc. (Data: Timely and Effective Care - Hospital)

**Visualizations**

-   Boxplots comparing effectiveness of different services among hospitals.

-   A map demonstrating infrastructures and facilities provided by different hospitals grouping by pre-specified levels, with label illustrating hospital ownership, and different scores.

-   A bar chart revealing the proportion of hospitals (by overall rating) facet by different factors, indicating whether they are below, average, or above national average. (Data: Hospital General Information)

-   A map visualizing hospital rating by patient, classfying hospitals based on patients' response.

-   Overall theme: adding custom controls, like **dropdown events** allowing selection of specific rating, region etc, and **range sliders and selectors** zooming in and out to show data for each hospital when zoomed in.

**Coding challenges**

-   For visualization:

    -   Making a map consists of different levels (ranking) may be challenging.

-   For data manipulation and tidying:

    -   Propor ways of classfying hospitals by different measurements can be difficult, may need to merge different datasets, mutate variables using nest and write functions.

#### The planned timeline

-   Week 1: Data cleaning; Data exploring; Discussion on work splitting.
-   Week 2: Data analysis and group meetings on revisions.
-   Week 3: Plots making and group meetings on revisions.
-   Week 4: Website building and dashboard making; In-class discussion with other gourps.
