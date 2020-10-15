|image1|

+-------------------------------------------+
| Appendix to the User Configuration Manual |
+===========================================+
|                                           |
+-------------------------------------------+
| Version 1.0 / May 2020                    |
+-------------------------------------------+

Table of contents
=================

`1. TELEMETRY PROFILES WIZARD 4 <#telemetry-profiles-wizard>`__

`1.1. TIME AND POINTS SELECTION 5 <#time-and-points-selection>`__

`1.1.1. Filters 6 <#filters>`__

`1.1.2. Time and Points Selection 7 <#time-and-points-selection-1>`__

`1.2. DATA ANALYSIS 9 <#data-analysis>`__

`1.2.1. Chart/Table 9 <#charttable>`__

`1.2.2. Time and Points Selection 12 <#time-and-points-selection-2>`__

`1.3. CALENDAR CONFIGURATION 14 <#calendar-configuration>`__

`1.3.1. Calendar Configuration 14 <#calendar-configuration-1>`__

`1.3.2. Time and Points Selection 15 <#time-and-points-selection-3>`__

`1.4. PROFILES AND ENVELOPES 17 <#profiles-and-envelopes>`__

`1.4.1. Profiles and Envelopes 17 <#profiles-and-envelopes-1>`__

`1.4.2. Time and Points Selection 20 <#time-and-points-selection-4>`__

`1.5. PROFILES CONFIRMATION 21 <#profiles-confirmation>`__

`1.5.1. Profiles 21 <#profiles>`__

`1.5.2. Time and Points Selection 23 <#time-and-points-selection-5>`__

`HOW TO CREATE A SET OF ROLLING PROFILES FOR ALL THE FLOWMETERS related
to A Hierarchical element OF THE NETWORK
26 <#how-to-create-a-set-of-rolling-profiles-for-all-the-flowmeters-related-to-a-hierarchical-element-of-the-network>`__

`2. DATA VISUALIZATION 31 <#data-visualization>`__

`2.1. ALGORITHM & TELEMETRY POINTS SELECTION
32 <#algorithm-telemetry-points-selection>`__

`2.2. SERIES 40 <#series>`__

`2.2.1. Algorithms Series 40 <#algorithms-series>`__

`2.2.2. Telemetry Point Series 41 <#telemetry-point-series>`__

`2.3. CHART/VALUES 42 <#chartvalues>`__

`2.3.1. Chart 42 <#chart>`__

`2.3.2. Algorithms Values 48 <#algorithms-values>`__

`2.3.3. Telemetry Points Values. 49 <#telemetry-points-values.>`__

`2.4. MANAGE WORKSPACES/TEMPLATES 50 <#manage-workspacestemplates>`__

`HOW TO… 57 <#how-to>`__

`3. ALARMS PERFORMANCE 58 <#alarms-performance>`__

`3.1. SELECTION 59 <#selection>`__

`3.2. ALARMS 59 <#alarms>`__

`3.3. MANAGE ALARMS 63 <#manage-alarms>`__

`4. ALARMED ELEMENTS 68 <#alarmed-elements>`__

`4.1. SELECTION 69 <#selection-1>`__

`4.2. ELEMENTS 69 <#elements>`__

`4.3. MANAGE ELEMENTS 72 <#manage-elements>`__

`5. HISTORICAL CONFIGURATION (NETWORK ELEMENTS)
76 <#historical-configuration-network-elements>`__

`6. WEEKLY PARK (?) 77 <#weekly-park>`__

TELEMETRY PROFILES WIZARD
=========================

This page is accessible from Left Main Menu/Configuration/Telemetry
Profiles Wizard:

|image2|

Figure 1: Telemetry Profiles Wizard Left Main Menu Location

The user can configure daily average profiles based on historical data
for any telemetry signal/point in the system.

The operator, when configuring the profiles, can:

-  Select the points to which the system will calculate profiles;

-  Establish over what period the system will calculate the profiles;

-  Eliminate outliers of the series;

-  Create, in the Calendar section, different types of days that the
      system will take into consideration in the calculation of the
      profiles;

-  Exclude/Include in the calculation of those values ​​recorded in
      periods affected by anomalous events.

The configuration of the profiles is done through a wizard menu
including the following steps:

1. Time and Points Selection.

2. Data Analysis.

3. Calendar Configurations.

4. Profiles and Envelopes.

5. Profiles Confirmation.

|image3|

Figure 2. Steps for configuring telemetry profiles

TIME AND POINTS SELECTION
-------------------------

This page allows the user to select the points to which the system will
calculate the profiles and to establish over what period the system will
calculate the profiles.

The main screen possesses two sections:

1. Filters.

2. Time and Points Selection.

|image4|

Figure 3. Sections in Time and Points Selection

From the top-right menu the user can:

-  Filter |image5|

-  Change Filter mode\ |image6|

-  Clear filter\ |image7|

Filters
~~~~~~~

This section allows the user to filter the points to which the system
will create the profiles. Users have to select at least one “Dimension”
and then by “Points Configured at”, by “Network Element Types”, by
“Hierarchy Element” or a combination of them. The user can check/uncheck
all the element types by clicking on the “check all” button |image8|.

|image9|

Figure 4.Filtering area

The system shows the information related to the Points at two different
levels:

-  Table: Main Grid containing information for all the points filtered.

-  Detailed information: where the user can go in-depth into the
      information on each point.

TABLE OVERVIEW

The following fields are available in the Points main grid:

-  Selected: users can choose for which ones of the filtered point the
      system will create profiles. There is a select all button at the
      top-left corner. This button picks all the points filtered,
      including the ones listed in the following pages.

-  Point ID

-  Point Description

-  Unit

-  Source

-  Point of Interest

DETAILED INFORMATION

The user can obtain more information in the expanded row of every Point
in the grid. The system possesses two tabs to capture and display the
most relevant information:

1. Point Configuration: a table containing detailed information for all
   the elements where the Point has been configured. The table contains
   the following fields:

-  Point ID

-  Point Description

-  Element Type

-  Element Name

-  Category

2. Validation Groups: a list containing the data validation groups to
   which users assigned the Point.

   |image10|

Figure 5. Expandable row information

.. _time-and-points-selection-1:

Time and Points Selection
~~~~~~~~~~~~~~~~~~~~~~~~~

This section allows users to:

-  Select the set of data for profiles creation.

-  Check the Points already selected.

-  Check the Calendars already configured.

TIME SELECTION

This area allows users to select the set of data that the system uses
for the calculation of the profiles. There are two alternative methods:

-  Fixed: the system performs the calculations based on a fixed set of
      data, with a start and end date. The profiles generated by this
      method are static and is only calculated one time when the user
      concludes the configuration of the profiles process.

-  Rolling: the system performs the calculations based on a dynamic set
      of data defined by the Days attribute, that is the number of days
      considered up to the current day. The system updates the profiles
      generated by this method automatically daily.

   |image11|

Figure 6. Time Selection menu

POINTS SELECTION

This area shows a list of the Points selected from the Filters section.
Users can filter, rank and remove them from the Points Selection list.

|image12|

Figure 7. Points Selection

CALENDAR CONFIGURATION

This area shows a list of the Calendars already configured in the
Calendar Configuration page. Users can remove them from the Calendar
Configuration list.

|image13|

Figure 8. Calendar Configurations

The user can collapse/expand this section by clicking on the |image14|
button.

DATA ANALYSIS
-------------

This page allows the user to review and validate the telemetry data for
the Points selected in the Time and Points Selection page.

The main screen contains two sections:

1. Main Chart/Table

2. Time and Points Selection

Chart/Table
~~~~~~~~~~~

This section allows users to:

-  Chart: Show, edit and define exclusion periods for the selected
      telemetry data.

-  Table: Show and edit the selected telemetry data.

CHART

The Chart shows the set of data corresponding to the selected signal and
the configured time selection (fixed or rolling). The data points are
coloured based on their quality: white means validated, the orange
estimated and blue manually edited.

|image15|

Figure 9. Time Series for a telemetry point

The time selector, at the bottom, allows the user to adjust the period
the data shown in the user interface. Users can change the zoom level by
using the mouse wheel or select a month/a week/a day by clicking once in
the time selector. Within this chart the user can:

-  Manually edit any value in the chart. This function is only available
      when the user selects data for 1 single-day. Users can to manually
      type the new values for each specific time.

-  Add Exclusion Periods\ |image16|: the user can select periods of
      non-relevant data that the system will not take into consideration
      in the calculations of the profiles. There are no limitations on
      the number of periods selected.

   |image17|

Figure 10. Adding exclusion periods

-  Reset the Chart zoom |image18|

-  Save points edition |image19|

-  Cancel points edition |image20|

-  Shift to Table view |image21|

TABLE

The Table shows the set of data corresponding to the selected signal and
the configured time selection (fixed or rolling) in tabular format. The
data grid shows the following fields

-  Source System.

-  Point ID.

-  Point description.

-  Date.

-  Value.

-  Arrival Date.

-  Validity: the system classifies the data in Valid (blank), Invalid
      (red alarm icon), Missing (yellow alarm icon) and Not Validated
      (orange question mark icon).

-  Estimated: checkmark when the Validation and Estimation estimated
      automatically the value.

-  Edited: checkmark when a user manually edited the value.

-  Validation Function: name of the function applied automatically for
      validating the data

-  Estimation Function: name of the function applied automatically for
      estimating the data

   |image22|

Figure 11. Table for data analysis

From this Table the user can:

-  Manually edit any value in the chart. Users can manually type the new
      values for each specific time

-  Save points edition |image23|

-  Cancel points edition |image24|

-  Change filter mode |image25|

-  Clear Filter |image26|

-  Shift to Chart view |image27|

.. _time-and-points-selection-2:

Time and Points Selection
~~~~~~~~~~~~~~~~~~~~~~~~~

This section allows users to:

-  Visualize the set of data configured for the profile creation (Only
      Read).

-  Select the Point that the system will show in the Chart/Table
      section.

-  Check the Calendars already configured.

TIME SELECTION

This area allows users to visualize the time configuration for the set
of data that the system uses for the profile calculations.

|image28|

Figure 12. Time Selection menu

POINTS SELECTION

This area shows a list of the Points selected from the Filters section
of the Time and Points Selection page. Users can filter and rank them
from the Points Selection list. The Main Chart/Table will show the data
for the point selected from this list.

|image29|

Figure 13. Points Selection

CALENDAR CONFIGURATION

This area shows a list of the Calendars already configured in the
Calendar Configuration page. Users can remove them from the Calendar
Configuration list.

|image30|

Figure 14. Calendar Configurations

The user can collapse/expand this section by clicking on the |image31|
button.

CALENDAR CONFIGURATION
----------------------

This page allows the user to create calendars that will apply to the
previous selection of data. These calendars allow the
inclusion/exclusion of day types, seasons (available in
Configuration/Seasons) and special days (already configured in
Configuration/Calendars). Once the configuration finishes, the system
will only apply them to those days that match the kind of days set in
the calendar. For instance, if the user creates a profile based on
rolling data for the last 60 days and in the calendar selects Working
days and Autumn, then the system only will take into consideration the
data for days that match both criteria. Then, the system will apply only
this profile to generate alarms when the current day matches the same
criteria.

The main screen possesses two sections:

1. Calendar Configuration

2. Time and Points Selection

.. _calendar-configuration-1:

Calendar Configuration
~~~~~~~~~~~~~~~~~~~~~~

This section contains five areas:

1. Name for the new calendar configuration.

2. Day Types: the user can select among Working days and Weekends. If no
   day type is selected, the system uses the complete period.

3. Seasons: the user can select among the seasons already defined in the
   Configuration/Seasons page. If no season is selected, the system uses
   the complete period.

4. Available Calendars: the user can select among the calendars already
   defined in the Configuration/Calendars page. The system assigns
   calendars by clicking on the Add button |image32|

5. Assigned Calendars: once the user assigns the calendar, the user can
   select if the days in that calendar are exclusive or inclusive. When
   exclusive, the system does not take into consideration the days
   contained in the calendar the calculation of the profile. On the
   other hand, when inclusive, the system considers those days in that
   calculation.

|image33|

Figure 15. Calendar Configuration areas

Note that if no actions are taken in sections 2 to 5, the system will
not apply any filter and will use all day types in the profiles
calculations.

From this page the user can:

-  Go to Calendars\ |image34|

-  Go to Seasons |image35|

-  Save calendar configuration |image36|

-  Cancel Save calendar configuration |image37|

.. _time-and-points-selection-3:

Time and Points Selection
~~~~~~~~~~~~~~~~~~~~~~~~~

This section allows users to:

-  Visualize the set of data configured for the profile creation (Only
      Read).

-  Visualize the list of configured points.

-  Check the Calendars already configured.

TIME SELECTION

This area allows users to visualize the time configuration for the set
of data that the system will use for the profile calculations.

|image38|

Figure 16. Time Selection menu

POINTS SELECTION

This area shows a list of the Points selected from the Filters section
of the Time and Points Selection page. Users can filter and rank them
from the Points Selection list.

|image39|

Figure 17. Points Selection

CALENDAR CONFIGURATION

This area shows a list of the Calendars already set in the Calendar
Configuration page. This list automatically updated every time a new
calendar is saved from the top-right menu. Once the calendars are in the
list, the user can select them to check their configuration and modify
it if needed. Users can also remove them from the list.

|image40|

Figure 18. Calendar Configurations

The user can collapse/expand this section by clicking on the |image41|
button.

PROFILES AND ENVELOPES
----------------------

This page allows the user to apply envelopes to the profiles created by
the configuration of the previous steps. The main screen possesses two
sections:

1. Profiles and Envelopes.

2. Time and Points Selection.

.. _profiles-and-envelopes-1:

Profiles and Envelopes
~~~~~~~~~~~~~~~~~~~~~~

This section contains three areas:

1. Profiles List.

2. Profiles and envelopes.

3. Profiles status.

   |image42|

Figure 19. Profiles and Envelopes areas

PROFILES LIST

The main grid possesses the following fields:

-  Point ID.

-  Point Description.

-  Calendar Configuration.

Users can filter, rank and remove them from the Profiles list.

PROFILES AND ENVELOPES

This area initially shows the calculated daily profile for the profile
selected in the list. User can apply envelopes to all these profiles by
clicking on the configure envelopes button on the top-right menu:
|image43|. The user has to define the following parameters:

-  Mode

-  Adaptative Envelope: when the user selects this method, the system
      applies increments (Hi and HiHi) or decrements (Lo and LoLo) to
      the value of the profiles by the percentage defined for each
      envelope.

-  Flat Absolute Envelope: when the user selects this method, the system
      applies envelopes defined by the user as a fixed value to the
      profiles.

-  Flat Relative Envelope: when the user selects this method, the system
      applies increments (Hi and HiHi envelopes) or decrements (Lo and
      LoLo envelopes) to the profiles by a fixed value. The system
      calculates these values as a percentage of the average, minimum,
      maximum, absolute minimum or absolute maximum values. If the user
      selects the average, the minimum or the maximum, then the system
      performs the calculation taking into consideration the 24 daily
      values of the profile. On the other hand, if the user selects the
      absolute maximum or minimum, then the system performs the
      calculations taking into consideration all the data of the time
      series used for the profile calculation.

-  Thresholds

-  Values: percentages or fixed values that the system applies in the
      calculation of the envelopes. When the user selects the Flat
      Relative Envelope method, the user has also to select the value to
      which the envelopes refer to. Absolute Maximum and Minimum only
      are available for HiHi and LoLo envelopes.

-  Severity: it defines the criticality of the alarm. Users can select
      among Low, Medium, High and Critical. The system will colour the
      envelopes accordingly.

-  Persistency. The time before trigging an alarm to avoid false alerts.
      Users have to define the duration and the units of measurement.

   |image44|

Figure 20. Envelopes configuration

PROFILES STATUS

This bar shows a summary of the status of the created profiles. There
are three categories:

-  Active Valid: profiles ready to be used.

-  Parked Valid: profiles calculated using rolling data that are
      temporally parked because the current season is different from the
      one for which the system calculated the profiles, so there is no
      available data for creating the profile.

-  Invalid: the system did not calculate the profile because there was
      no valid data for the selected period (rolling or fixed).

   |image45|\ |image46|

Figure 21. Profiles status summary

From the top-right menu the user can:

-  Reset chart zoom\ |image47|.

-  Cancel profiles calculation |image48|: by clicking this button, users
      can cancel the profiles creation process.

-  Configure envelopes\ |image49|.

-  Change Filter mode\ |image50|.

-  Clear filter\ |image51|.

.. _time-and-points-selection-4:

Time and Points Selection
~~~~~~~~~~~~~~~~~~~~~~~~~

This section allows users to:

-  Visualize the set of data configured for the profile creation (Only
      Read).

-  Visualize the list of configured points.

-  Check the Calendars already configured.

TIME SELECTION

This area allows users to visualize the time configuration for the set
of data that the system uses for the profile calculations.

|image52|

Figure 22. Time Selection menu

POINTS SELECTION

This area shows a list of the Points selected from the Filters section
of the Time and Points Selection page. Users can filter and rank them
from the Points Selection list.

|image53|

Figure 23. Points Selection

CALENDAR CONFIGURATION

This area shows a list of the Calendars already configured in the
Calendar Configuration page.

|image54|

Figure 24. Calendar Configurations

The user can collapse/expand this section by clicking on the |image55|
button.

PROFILES CONFIRMATION
---------------------

This page allows the user to visualize all the profiles created during
the process described in the previous steps. It also allows the user to
manage the parking of the profiles.

Profiles
~~~~~~~~

The table shows the following information:

-  Profile Name

-  Is Valid?

-  Point Id

-  Point Description

-  Dimension

-  Time Mode: rolling or fixed

-  Rolling Days

-  Is Parked?

-  Parking Start Date

-  Parking End Date

-  Parking Type: Automatic in case the profiles the system parks the
      profile during the creating process or Manual if the user has
      parked it.

-  Parking Comments

|image56|

Figure 25. Profiles configuration table

From the top-right menu the user can:

-  Edit parking profile\ |image57|. The user can park (indefinitely or
      temporally by defining an end date) the profiles created.

   |image58|

Figure 26. Editing parking

-  Save profiles\ |image59|: the user can save all the profiles created.

-  Cancel profiles creation |image60|: the user can cancel the entire
      process of profiles creation and delete all the parameters
      configured in all the pages of the wizard.

-  Change Filter mode\ |image61|

-  Clear filter\ |image62|

.. _time-and-points-selection-5:

Time and Points Selection
~~~~~~~~~~~~~~~~~~~~~~~~~

This section allows users to:

-  Visualize the set of data configured for the profile creation (Only
      Read).

-  Visualize the list of configured points.

-  Check the Calendars already configured.

TIME SELECTION

This area allows users to visualize the time configuration for the set
of data that the system uses for the profile calculations.

|image63|

Figure 27. Time Selection menu

POINTS SELECTION

This area shows a list of the Points selected from the Filters section
of the Time and Points Selection page. Users can filter and rank them
from the Points Selection list.

|image64|

Figure 28. Points Selection

CALENDAR CONFIGURATION

This area shows a list of the Calendars already configured in the
Calendar Configuration page.

|image65|

Figure 29. Calendar Configurations

The user can collapse/expand this section by clicking on the |image66|
button.

**HOW TO CREATE A SET OF ROLLING PROFILES FOR ALL THE FLOWMETERS related to A Hierarchical element OF THE NETWORK**
===================================================================================================================

-  Start a profiles creation process by accessing to the Telemetry
      Profiles Wizard Page.

-  Make the selection of points according to your needs from the Time
      and Points Selection page. In that case, select Flow from the
      Dimension panel, Hierarchy Elements level from Points Configured
      at and navigate to the desired hierarchical element in the
      hierarchical tree. Ensures that you check Search in descendants
      option to ensure that the system selects all the flow points in
      the zones belonging to the selected one.

   |image67|

Figure 30. Filtering area

-  Click on the filter button at the right-click menu.

-  Check that all the points are in the main table and then click on the
      select all button at the top-left of the table.

   |image68|

Figure 31. Selecting all the points

-  Check that all the points are in the Time and Points Selection
      section:

   |image69|

Figure 32. Points Selection

-  Configure the Time Mode as Rolling and some relevant days:

   |image70|

Figure 33. Time Selection

-  Move to Data Analysis page and review the data series by selecting
      points from the list in the Points Selection section. Add new
      exclusion periods and modify values manually if needed and save
      the changes.

   |image71|

Figure 34. Adding exclusion periods and editing values

-  Move to Calendar Configurations page and configure as many calendars
      as needed:

-  Type “Spring Working Days” in the Calendar Configuration box and
   check working day from Day Types and Spring (you might have different
   season names) from Seasons and add any of the available calendars if
   applies. Save the configuration.

   |image72|

Figure 35. Defining calendars

-  Repeat the process for as many different calendars as needed.

   |image73|

..

   Figure 36. Calendar Configurations

-  Move to the Profiles and Envelopes page and configure the Envelopes
      for the already calculated profiles. Select the Mode that adapts
      better to your needs and set the values that the system will apply
      and the Severity and Persistency and save the changes:

   |image74|

Figure 37. Configuring envelopes

-  Review the created envelopes and modify them if needed:

   |image75|

Figure 38. Profiles and envelopes

-  Move to the Profiles Confirmation page, park some profiles if needed
      and save the profiles:

   |image76|

Figure 39. Profiles Confirmation table

DATA VISUALIZATION
==================

This page is accessible from Left Main Menu/Data Access/Data
Visualization:

|image77|

Figure 40. Data Visualization Left Main Menu Location

The Data Visualization page allows the user to create charts and tables
with any combination of algorithms and telemetry points. There are no
limitations in the parameters of the query, being able to combine values
of any signal and results of algorithms, belonging to different zones
and hierarchical levels. Finally, the user can create templates and
workspaces, so they can reuse the configuration done for one zone and
apply to other zones in a single step.

The Data Visualization page contains four sections:

1. Algorithm & Telemetry Points selection

2. Series

3. Chart/Values

4. Manage Workspaces/Templates

..

   |image78|

Figure 41. Sections on Data Visualization page

ALGORITHM & TELEMETRY POINTS SELECTION
--------------------------------------

This section allows the user to select the Algorithms and Telemetry
points added to the cart in the Series section on this page to create
charts and tables and to define the range of dates for them. This
section possesses three areas: dates, algorithms and telemetry points.

DATES

The user can select the start and end date (including the
starting/ending hour, if needed) of the set of data that will generate
the charts and tables.

|image79|

Figure 42. Dates selection

ALGORITHMS

The system lists all the algorithms available in the system classified
by family:

|image80|

Figure 43. Families of algorithms.

The user can click on the arrow to get the complete list of algorithms
in every family. The algorithms are grouped depending on their
aggregation time: base, daily, weekly or monthly. These groups are
collapsed/expanded by clicking on the arrow next to the aggregation
name:

|image81|

Figure 44. Groups

The user can also apply filters to the algorithms. This filter looks at
both the algorithm name and short name and shows those containing the
typed characters in, at least, one of these attributes:

|image82|

Figure 45. Filters

From this list, the user can add, by clicking on the Add button,
algorithms to the cart in the Series section on this page.

|image83|

Figure 46. Adding algorithms

The user has to select the particular element/s for which the system
will add their algorithms to the cart. The Elements Selection window
helps the user to filter them. The filters on this window vary depending
on the kind of elements linked to the algorithm. If the algorithm
belongs to a hierarchical element, the user has to filter by “Hierarchy
Element Types” and, if needed, “Hierarchy Element”. The user can
check/uncheck all the element types by clicking on the “check all”
button |image84|. The user can collapse/extend the advance filter (by
“Hierarchy Element”) by clicking on the arrow.

|image85|

Figure 47. Elements selection.

On the other hand, if the algorithm pertains to a network element, the
user has to filter by “Network Element Types” and, if needed, “Hierarchy
Element”.

|image86|

Figure 48. Hierarchy element selection.

Filters are automatically applied every time a choice is done. The table
shows the records for the applied filter. The table contains the
following fields:

-  Selected: users can choose for which of the filtered elements the
      system will add their related algorithms to the cart. There is a
      “Select all” button at the top-left corner. This button allows the
      selection/deselection of all the elements filtered, including the
      ones listed in the following pages.

-  Type

-  Name

-  Description

-  Belong to: the hierarchy or the network element to which the listed
      element pertain.

|image87|

Figure 49. Elements table.

From the top-right menu the user can:

-  Add elements to the cart calendars by clicking on the Add button
      |image88|.

-  Change Filter mode\ |image89|

-  Clear filter\ |image90|

TELEMETRY POINTS

The system lists all the telemetry points available in the system:

|image91|

Figure 50. Telemetry Points.

The table possesses the following fields:

-  Point Id

-  Point Description

The user can add any telemetry point to the cart by clicking on the Add
button located at the top-right menu\ |image92|. It is also possible to
get access to a Point Advance Filter where the user can apply different
filters to get a selection of telemetry points. This function is
available from the “point advanced filter” button at the top-right menu
|image93|. If, when the user clicks on this button, there is a telemetry
point already selected in the list, the system will ask the user if it
has to add that selection to the cart.

|image94|

Figure 51. Adding points to the cart.

In the Point Advanced Filter windows, users have to select at least one
“Dimension” and then by “Points Configured at”, by “Network Element
Types”, by “Hierarchy Element” or a combination of them.

|image95|

Figure 52. Point advanced filter.

The Points main grid at the left side of the window contains the
following fields:

-  Selected: users can choose which of the filtered elements the system
      will add to the cart. There is a “Select all” button at the
      top-left corner. This button allows the selection/deselection of
      all the elements filtered, including the ones listed in the
      following pages

-  Point ID

-  Point Description

-  Unit

-  Source

-  Point of Interest

The left side of the windows shows a table containing detailed
information for all the elements with the selected telemetry point
configured. The table possesses the following fields:

-  Point ID

-  Point Description

-  Element Type

-  Element Name

-  Category

From the top-right menu the user can:

-  Filter |image96|

-  Add |image97|. By clicking on the Add button, the system annexes the
      selected telemetry points to the cart in the Series section of
      this page.

-  Change Filter mode\ |image98|

-  Clear filter\ |image99|

SERIES
------

This section allows the user to generate charts and tables from the
telemetry points and algorithms previously added to the cart. This
section contains two separate tabs:

1. Algorithms Series

2. Telemetry Points Series.

**Algorithms Series**
~~~~~~~~~~~~~~~~~~~~~

The Algorithms Series table possesses the following fields:

-  Selected: users can choose for which of the series in the cart the
      system will create a chart and/or a table. There is a “Select all”
      button at the top-left corner. This button allows the
      selection/deselection of all the elements, including the ones
      listed in the following pages.

-  Element Name: hierarchy element to which the selected algorithm
      belongs to.

-  Algorithm Name

-  Algorithm Short Name

-  Dimension Type: flow, pressure, level etc.

-  Start Date: according to the selection done in the Algorithm &
      Telemetry Points Selection section.

-  End Date: idem.

   |image100|

Figure 53. Algorithm series.

**Telemetry Point Series**
~~~~~~~~~~~~~~~~~~~~~~~~~~

The Telemetry Point Series table contains the following fields:

-  Selected: users can choose for which of the series in the cart the
      system will create a chart and/or a table. There is a “Select all”
      button at the top-left corner. This button allows the
      selection/deselection of all the elements, including the ones
      listed in the following pages.

-  Point Id.

-  Point Description.

-  Dimension Type: flow, pressure, level etc.

-  Start Date: according to the selection done in the Algorithm &
      Telemetry Points Selection section.

-  End Date: idem.

   |image101|

Figure 54. Telemetry point series.

From the top-right menu of this section the user can:

-  Load a chart for the selected algorithms and telemetry points
      |image102|.

-  Load an algorithms values table |image103|.

-  Load a telemetry points values table\ |image104|.

-  Remove the selected series |image105|.

-  Edit selected series period |image106|. The system will modify the
      start and end date of the algorithms and telemetry points
      selected.

   |image107|

Figure 55. Editing dates.

-  Change Filter mode\ |image108|

-  Clear filter\ |image109|

The user can collapse/expand this section by clicking on the |image110|
button beside the Show Series text.

CHART/VALUES
------------

This section allows the user to visualize the charts and tables
generated from the Series section of this page. This section contains
three separate tabs:

1. Chart

2. Algorithms Values

3. Telemetry Points Values.

Algorithms and Telemetry Points Values tabs are only read tables. On the
contrary, the Chart tab allows the user to customize the appearance of
the chart.

**Chart**
~~~~~~~~~

This tab allows the user to visualize and configure all the graphical
information related to the algorithms and telemetry points selected in
the Series section of this page. The chart tab contains 4 main areas:

1. Time-series

2. Events

3. Time Selector

4. Top-right buttons

   |image111|

Figure 56. Chart areas.

TIME-SERIES

The time-series area shows the trend of all the series selected by the
user. The user can enable/disable the visualization of the series by
clicking on the coloured circle beside the series name. The system shows
a tooltip with the values of the series when the user hovers the mouse
over them.

|image112|

Figure 57. Time-series area

EVENTS

The system shows all the events related to the selected series. It
includes not only the hierarchical/network elements to which the
selected series belong to but also all those hierarchical elements that
include in their configuration the selected telemetry points. For
instance, if the user selects only a flow telemetry signal, the system
will show the events of its flow meter but also the events of all the
DMAs that have this signal as a boundary meter. The user can
enable/disable the visualization of the event types by clicking on
events name. The system can represent in this area the following types
of events (if available):

-  Burst Main Leaks.

-  Other Leaks.

-  Activities.

-  Alarms.

-  Meter Faults.

Events and time-series areas are synchronised, the system highlight in
the time-series areas the events selected from the events area. The
system also shows information related to the events by hovering the
mouse over them.

|image113|

Figure 58. Events.

TIME SELECTOR

it allows the user to fine-tune the period that the system will show in
the time-series and events areas.

TOP-RIGHT BUTTONS

The edit chart configuration button allows the user to customize the
appearance of the charts. The customization window contains 3 tabs:

-  Series

-  Charts

-  Axes

|image114|

Figure 59. Tabs in the chart customization menu.

The **series** tab is divided into two areas. The left one showing a
list of all the series in the chart. The right allowing the modification
of parameter (Title, Axis and Color) of the series selected at the left
side of the window. The user can activate the right menu by selecting
one series and clicking on the edit series button |image115|.

-  Title: the user can modify it by typing the alternative name in the
      box.

-  Colour: the user can modify the by default colour by selecting a new
      one from the drop-down menu.

-  Axis: the user can assign the series to an alternative axis, if
      available, of the same dimension. The system by default assigns
      axes to the different series according to the configuration set at
      the Configuration/Unit of Measurements menu. The selection of
      series in the chart might involve multiple axes of the same
      dimension. This menu allows the user to unify them. On the hand,
      under certain circumstances, it might worth to add a new axis. The
      user can do it by clicking on the add axis button |image116|.

   |image117|

Figure 60. Editing series.

Finally, from the top-right menu, the user can:

-  Save all the changes in the series configuration |image118|.

-  Cancel all the changes in the series configuration |image119|.

The **chart** tab is divided into two areas, Chart and Event Chart
configuration. The Chart Customization area contents the following
parameters:

-  Title: it allows the user to modify the title of the chart.

-  Show Legend: it allows the user to enable/disable the visualization
      of the chart legend.

-  Show Labels: it allows the user to enable/disable the visualization
      of the data labels.

-  Show Series Chart: it allows the user to enable/disable the
      visualization of the series chart area.

-  Show Time Bar: it allows the user to enable/disable the visualization
      of the time bar.

-  Minimum Time Bar Period: it allows the user to define the minimum
      selectable zoom (in days) in the Time bar.

-  Default Selected Period: it is the default period that the system
      shows in the time-series and events areas

-  Default Visible Period: it is the default period available in the
      time bar.

   |image120|

Figure 61. Default Selected/Visible configuration.

On the other hand, the Events Chart Customization area contents the
following parameters:

-  Show Events: it allows the user to enable/disable the visualization
      of all the events types listed below.

-  Show Burst Main Leaks.

-  Show Other Leaks.

-  Show Activities.

-  Show Alarms.

-  Show Meter Faults.

   |image121|

Figure 62. Editing chart.

The **Axes** tab is divided into two areas contains two areas. The left
one showing a list of all the Axes in the chart, including verticals and
horizontal (time). The right allowing the modification of parameter
(Title, Colors, Unit, Show UoM and Scale) of the axis selected at the
left side of the window. The user can activate the right menu by
selecting one series and clicking on the edit series button
|image122|\ **.**

-  Title: the user can add a title by typing the name in the box.

-  Title Color: the user can modify the by default colour for the title
      by selecting a new one from the drop-down menu.

-  Label Color: the user can modify the by default colour for labels in
      the axis by selecting a new one from the drop-down menu.

-  Units: the user can modify the unit assigned by the system to the
      axis by any other of the units available in the system for the
      dimension of the axis (flow, pressure etc.)

-  Show UoM: the user can select if include or not the units in the
      title of the axis.

-  Scale: the system automatically applies scales to the series based on
      their values. The user can modify those values manually. The
      configurable parameters depend on the orientation (horizontal or
      vertical) of the axis. If vertical, the user has to define the
      minimum and maximum value of the axis and step size. If
      horizontal, the user has to define the maximum and minimum date,
      step size and the step unit (day, week, month, etc.).

|image123|

Figure 63. Axes configuration

Finally, from the top-right menu, the user can:

-  Save all the changes in the axes configuration |image124|.

-  Cancel all the changes in the axes configuration |image125|.

When the user finishes the configuration of the three tabs can save the
modifications by clicking on the Save button at the top-right corner of
the window\ |image126|.

From the top-right menu the users can also:

-  Hide all the series in the chart |image127|.

-  Turn data points on/off\ |image128|.

-  Turn data validation points on/off\ |image129|.

-  Export to image\ |image130|.

-  Export to pdf |image131|.

**Algorithms Values**
~~~~~~~~~~~~~~~~~~~~~

This tab allows the user to visualize, in a tabular format, all the
information related to the algorithms selected in the series section of
this page. The Algorithms Series table possesses the following fields:

-  Algorithm

-  Element Name

-  Element Description

-  Date

-  Value: this column shows the values of each algorithm according to
      the UoM of the configuration of the user.

-  Value (I.S.): this column shows all the values of all the algorithm
      in the International System UoM to allow the user to rank and
      filter them.

-  Dimension Type

-  Merge Status

-  Estimated

-  Edited

-  Previous Value

-  Reason for Edit

|image132|

Figure 64. Algorithm values table.

From the top-right menu, the user can:

-  Change Filter mode\ |image133|.

-  Clear filter\ |image134|.

**Telemetry Points Values.**
~~~~~~~~~~~~~~~~~~~~~~~~~~~~

This tab allows the user to visualize, in a tabular format, all the
information related to the telemetry points selected in the series
section of this page. The Telemetry Points Series table contains the
following fields:

-  Source System.

-  Point Id.

-  Point Description.

-  Date: timestamp of the value.

-  Value: this column shows the values of each telemetry point according
      to the UoM of the configuration of the user.

-  Arrival Date: data of the reception of the value in the system.

-  Value (I.S.): this column shows all the values of all the telemetry
      point in the International System UoM to allow the user to rank
      and filter them.

-  Dimension Type.

-  Validity.

-  Estimated.

-  Edited.

-  Estimation Function.

-  Validation Function.

|image135|

Figure 65. Telemetry Points values

From the top-right menu, the user can:

-  Change Filter mode\ |image136|.

-  Clear filter\ |image137|.

MANAGE WORKSPACES/TEMPLATES
---------------------------

This section allows the user to create and manage workspaces and
templates. Workspaces allow users to save (in a private or public mode)
a combination of algorithms and telemetry points for a specific period
(or for a rolling period) so that the user will have them available each
time that access to the systems. Templates allow users to reuse the
configuration done in a specific DMA to other DMAs. For instance, if for
a DMA the user has selected to show the daily leakage and distribution
input algorithms and also the flow boundary signals for a rolling period
of the last 15 days, the user can save this configuration as a template
and apply it to any other DMA in the system automatically.

From the top-right menu the user can:

3. Save template

4. Save workspace

5. Open the templates and workspaces manager

6. Open data export manager

SAVE TEMPLATE

This button allows the user to save a template with the configuration in
the chart area. The user can set:

-  Name of the template

-  Description of the template.

-  Time mode. Two options are available. If the user selects Fixed, then
      the system allows to keep the current dates in the series
      selection or to define a new period (generic dates). If the user
      chooses Rolling, then it is needed to set the Time units (daily,
      weekly or monthly), the Offset (number of time units in the past
      for the period start date calculation) and the Period (duration of
      the period). For instance, if the template is configured in
      rolling mode and the user sets a daily time unit, an offset of 7
      days and a period of 5 days, the system will apply the template to
      the selected hierarchical element starting 7 days ago and with a
      duration of 5 days. If the offset is equal to the period the
      system will apply the template for the number of days in these
      parameters.

   |image138|

Figure 66. Template configuration

-  Privacy: the system will share the template with the other users if
      the user selects Public. On the contrary, if selects Private only
      the creator of the template can use it.

-  Include: the user can select to include in the template the flow
      boundary telemetry points and/or the pressure points within the
      hierarchical elements where the user applies the template.

-  Algorithms: the system shows a list of the algorithms included in the
      template.

From the top-right menu the user can:

-  Save template |image139|.

-  Cancel |image140|.

SAVE WORKSPACE

This button allows the user to save a template with the configuration in
the chart area. The user can set:

-  Name of the workspace.

-  Description of the workspace.

-  Time mode. Two options are available. If the user selects Fixed, then
      the system allows to keep the current dates in the series
      selection or to define a new period (generic dates). If the user
      chooses Rolling, then it is needed to set the Time units (daily,
      weekly or monthly), the Offset (number of time units in the past
      for the period start date calculation) and the Period (duration).

   |image141|

Figure 67. Workspace configuration.

-  Privacy: the system will share the workspace with the other users if
      the user selects Public. On the contrary, if selects Private only
      the creator of the workspace can use it.

From the top-right menu the user can:

-  Save workspace |image142|.

-  Cancel |image143|.

TEMPLATES AND WORKSPACE MANAGER

This window allows the user to manage the templates and workspaces in
the system. It contains two separate tabs: Templates and Workspaces.

The table in the templates tab contains the following fields related to
their configuration:

-  Name.

-  Description.

-  Time information: fixed or rolling and the configuration parameters.

-  Is Public.

-  Last Update.

-  Boundary Points Included.

-  Pressure Points Included.

   |image144|

Figure 68. Managing a template

The user can select any of the templates in the list and, by using the
button at the top-right menu, load it. The system checks if the chart
area is filled and asks the user whether to overwrite or append to the
current chart the series selected by the template.

|image145|

Figure 69. Overwriting or appending to the chart.

Then the system opens a hierarchical elements filter that allows the
user to select the area/s in which will apply the template. If the user
selects more than one element then the system adds all the algorithms
and telemetry points belonging to them to the new chart.

|image146|

Figure 70. Hierarchical elements filter.

From the top-right menu the user can:

-  Edit the template |image147|.

-  Delete the template |image148|.

On the other hand, the table in the workspaces tab contains the
following fields:

-  Name.

-  Description.

-  Time information: fixed or rolling and the configuration parameters.

-  Is Public.

-  Last Update.

   |image149|

Figure 71. Managing a workspace

From the top-right menu the user can:

-  Load workspace\ |image150|. The system checks if the chart area is
      filled and asks the user whether to overwrite or append to the
      current chart the series in the workspace.

-  Edit the workspace |image151|.

-  Delete the workspace |image152|.

TEMPLATES AND WORKSPACE MANAGER

This window allows the user to export to Excel the algorithms and
telemetry point values in the chart/values section.

|image153|

Figure 72. Exporting data

The table shows a list of the available reports for downloading. The
table contains the following fields:

-  Export File Name.

-  Export Creation Date. Date and hour when the user requested the
      creation of the export data file.

-  Status Update Date. Date and hour from when the export data files are
      available for download.

-  Status: Scheduled (the user as requested the system to create the
      data export file), Running (the system is creating the file), Done
      (file is available for download) and Failed (the system has not
      been able to create the file). When the file is Done the user can
      download it by clicking on the Status icon |image154|.

From the top-right menu the user can:

-  Export Selected algorithms Values\ |image155|. The user has to define
      the Export File Name and to export data\ |image156|.

   |image157|

Figure 73. Data Export Manager

-  Export Selected Telemetry Points values\ |image158|. The user has to
      define the Export File Name and to export data\ |image159|.

-  Clear filter\ |image160|.

**HOW TO…**
===========

-  XXX

ALARMS PERFORMANCE
==================

This page is accessible from Left Main Menu/Monitoring/Alarms
Performance:

|image161|

Figure 74. Alarms Performance Left Main Menu Location

The Alarms Performance page allows the user to check the performance of
all the alarms created in the system including profiles, algorithm
simple and complex alarms. The users can also manage these alarms from
this page.

The Alarms Performance page contains three sections:

1. Selection

2. Alarms

3. Manage Alarms

   |image162|

Figure 75. Sections on Alarms Performance page

SELECTION
---------

This section allows the user to filter alarms that the system will load
in the Alarms section. Users have to select at least one “Dimension” and
then by “Points Configured at”, by “Network Element Types”, by
“Hierarchy Element” or a combination of them. The user can check/uncheck
all the element types by clicking on the “check all” button |image163|.

|image164|

Figure 76.Filtering area

The user can collapse/expand this section by clicking on the |image165|
button.

ALARMS
------

The following fields are available in the Points main grid:

-  Selected: users can choose to which ones of the filtered alarms will
      apply different actions from the Manage Alarms section (top-right
      menu) including acknowledging and parking them, navigating to Data
      Validation, load historical information etc. There is a select all
      button at the top-left corner. This button picks all the alarms,
      including the ones listed in the following pages.

-  Alarm Name.

-  Is Active: an alarm could be “Active” meaning that there are events
      on it, “no active” meaning that there are no live events on it, or
      “Null” that means that user has acknowledged it but the system
      does not have updated yet the database.

-  Alarm Type: it depends on how and where the alarm has been
      configured. Algorithm Simple if the user set it in Network
      Elements. Complex if the user configured it from
      Configuration/Alarms. Profiles if the user set it from Telemetry
      Profiles Wizard.

-  Alarm Severity: Critical, High, Medium and Low depending on the user
      configuration. The colour of the raws in this table is coloured
      based on the severity configured for the alarm. The system
      automatically assigns the font colour to enable the readability of
      the table. When the user has checked all the activations of one
      alarm as acknowledged the system shifts the colour to a mostly
      muted one. The system represents active alarms in bold font,
      non-active alarms are shown in regular font.

-  Alarm Start Date: one single alarm might be activated several times.
      The system keeps records of all of them and shows the start date
      of the most recent active activation among the most severe ones.

-  Alarm End Date: shows the end date of the above alarm.

-  Alarm Trigger Point: shows the value that triggered the alarm for the
      most recent and severe activation of the alarm.

-  Number of Conditions.

-  Times Activated on the Last 7 Days.

-  Times Activated on the Last 30 Days.

-  Times Activated on the Last 90 Days.

-  Times Activated on the Last 365 Days.

-  Alarm Ack Date: the system shows the date of the most recent
      acknowledged among the most severe activations.

-  Alarm Ack Comment: shows the comment of the above activation.

-  Alarm Ack By: shows the user that acknowledged the above activation.

-  Related Elements: network and hierarchical elements with the selected
      alarm configured.

The user can obtain more information in the expanded row of every Alarm
in the grid. The system possesses three tabs to capture and display the
most relevant information:

1. Historical Activations: it shows all the historical activations of
   the alarm including the acknowledged ones. The table shows the
   following fields:

-  Selected

-  Alarm Name.

-  Severity.

-  Start Date.

-  End Date.

-  Trigger Point.

-  Ack Date.

-  ACK by.

-  ACK Comment.

   |image166|

Figure 77. Historical Activations tab

The colours of the activations within this table follow the same rule of
the main table, based on the severity and on the acknowledge status.
From the top-right menu the user can:

-  Acknowledge selected alarms |image167|. It allows the user to
      acknowledge the activations selected from the first column. The
      user could (not mandatory) add a comment to the acknowledgement
      and then save changes |image168|.

   |image169|

Figure 78. Acknowledging historical activations

-  Undo selected alarms acknowledgement |image170|. It allows the user
      to undo the acknowledgement for the activations selected from the
      first column.

-  Navigate to Alarmed Elements |image171|. It allows the user to
      navigate to the Alarmed Elements page that will be filtered by the
      elements related to the activations selected the first column.

-  Disable severity colours\ |image172|. It allows the user to visualize
      a non-coloured table. The system represents active activations in
      bold.

   |image173|

Figure 79. Disabling severity colours

-  Change Filter mode\ |image174|.

-  Clear filter\ |image175|.

2. Alarm Configuration: it allows the user to visualize and edit if
   needed the configuration of the alarm. The information showed in this
   tab will depend on the alarm type. The user can edit the
   configuration by clicking on the Edit button at the top-right menu.

   |image176|

Figure 80. Alarm Configuration

3. Related Elements: It allows the user to visualize and edit the
   elements related to the selected alarm. The table shows the following
   fields:

-  Element Name.

-  Element Description.

-  Element Type.

   |image177|

Figure 81. Related elements

From the top-right menu the user can: Edit related elements |image178|.

-  Change Filter mode\ |image179|.

-  Clear filter\ |image180|.

-  Filter

MANAGE ALARMS
-------------

This section allows the user to:

-  Load Filtered Elements |image181|. It allows the user to filter the
      alarms table by the network and/or the hierarchy elements checked
      in the Selection section. The system looks at the related elements
      of each alarm, filtering only those that belong to one of the
      element types choose.

-  Load Historical Information |image182|. It allows the user to
      navigate to a chart window where the system shows historical
      information of the alarm selected from the table. The system
      generates a chart for individual alarm selection. The chart
      includes both time-series and events that the user can customize
      as any other chart created in the Data Visualization page. The
      time-series and the events that the system loads in the chart
      depend on the related elements of the alarm that the user has
      selected:

   **PROFILES**

   a. if the related element is a **hierarchy element**, the system will
         upload to the chart the following information:

-  The time-series of signal that has generated the alarm (Note: The
      system, by default, hides all the series except for the one
      generating the alarm).

-  The time-series of all the other pressure and flow signals linked to
      the hierarchy element.

-  The time-series for the DDI and DL algorithms.

-  The events of the hierarchy element.

-  The events of all the network elements (flowmeters, pressure gauges
      etc.) belonging to that hierarchy element.

-  The events of the element to which any of the time-series in the
      chart belong to.

   |image183|

Figure 82. Historical information for an alarm related to a DMA

a. if the target element is a **network element**, the system will
      upload to the chart the following information:

-  The time-series of the signal generating the alarm.

-  The time-series of the other signals belonging to the same network
      element (if any).

-  The time-series of all the signals of all the network elements in
      which the target network element is configured.

-  The time-series of the DLNE and DNFNE algorithms of the related
      element. DLARS, DSWORPS, MLARS, MSWORPS Site

-  The events of the target network element.

-  The events of the hierarchical elements to which the network element
      belong to.

-  The events of the element to which any of the time-series in the
      chart belong to.

   a. It usually happens that there is more than one related element. In
         those cases, the system will upload all the time-series and
         events related to them according to the above rules.

-  Show active alarms\ |image184|: it allows the user to enable/disable
      the visualization of the inactive alarms. The system considers
      inactive alarms those for which the user has acknowledged all the
      activations, or it has never been activated.

-  Acknowledge selected alarms\ |image185|. It allows the user to
      acknowledge all the activations of the alarms that the user has
      selected from the table. The system pop-ups a window from where
      the user can add comments to the acknowledgement:

   |image186|

Figure 83.Acknownledging alarms

-  Edit parking profiles\ |image187|: it allows the user to unpark/park
      (indefinitely or temporally) the alarm profile selected from the
      table. If the user parks an alarm, the system will disable the
      activation of the parked alarms during the configured period.

   |image188|

Figure 84. Editing a parking profile

-  Delete selected elements |image189|: it allows the user to
      permanently delete the configuration of the alarms that the user
      has selected from the table. The system will also delete all the
      historical activations of the alarms.

   |image190|

Figure 85. Deleting alarms

-  Navigate to Alarmed Elements |image191|. It allows the user to
      navigate to Alarmed Elements page. The system automatically
      filters the page by the related elements of the selected alarms in
      the Alarms Performance page.

-  Navigate to map |image192|: it allows the user to navigate to the Map
      page. The system loads the map with the meter layer (pressure
      gauge or flowmeter) of the signal activating the alarm that the
      user has selected from the table. The map highlights and zooms to
      the selected element.

-  Navigate to data validation |image193|: it allows the user to the
      Data Validation page. The system loads the page with the telemetry
      signals activating the alarms that the user has selected from the
      table.

-  Configure severity colours\ |image194|: it allows the user to modify
      the by default colours for each one of the severity categories in
      the system.

   |image195|

Figure 86. Configuring severity colours

-  Disable severity colours\ |image196|: it allows the user to visualize
      non-coloured the alarms. The system keeps representing active
      alarms in bold font and the Non-active alarms in regular font.

-  Change Filter mode\ |image197|.

-  Clear filter\ |image198|.

-  Export to Excel\ |image199|: it allows the user to export to Excel
      the set of alarms that the user has filtered in the table. It
      exports the columns visible in the table.

-  Export to Word\ |image200| it allows the user to export to Word in
      table format the set of alarms that the user has filtered in the
      table. It exports the columns visible in the table.

-  Export to CSV\ |image201|: it allows the user to export to CSV format
      the set of alarms that the user has filtered in the table. It
      exports the columns visible in the table

-  Manage columns\ |image202|.

ALARMED ELEMENTS
================

This page is accessible from Left Main Menu/Monitoring/Alarmed Elements:

|image203|

Figure 87. Alarmed Elements Left Main Menu Location

The Alarmed Elements page allows the user to check the alarms of all the
network elements (flow meters, pressure meters etc.) and hierarchical
elements (DMAs, distribution zones etc.) of the network. The users can
also manage these alarms from this page.

The Alarms Performance page contains three sections:

1. Selection

2. Elements

3. Manage Elements

|image204|

Figure 88. Sections on Alarmed Elements page

.. _selection-1:

SELECTION
---------

This section allows the user to filter elements that the system will
load in the Elements section. Users can make a selection by “Hierarchy
Element type” and/or “Network Element Types”. The user can narrow-down
that selection by filtering by “Hierarchy Element”. The user can
check/uncheck all the element types by clicking on the “check all”
button |image205|.

|image206|

Figure 89.Filtering area

The user can collapse/expand this section by clicking on the |image207|
button.

ELEMENTS
--------

The following fields are available in the Elements main grid:

-  Selected: users can choose to which ones of the filtered elements
      will apply different actions from the Manage Elements section
      (top-right menu) including acknowledging their alarms, navigating
      to Data Validation, load historical information etc. There is a
      select all button at the top-left corner. This button picks all
      the elements, including the ones listed in the following pages.

-  Element Name

-  Element Type: flow meter, DMA, etc.

-  Alarm Name: the system shows the name of the most recent alarm among
      the most severe ones related to the element in the table.

-  Is Active: an element could be “Active” meaning that there are events
      on it, “no active” meaning that there are no live events on it, or
      “Null” that means that user has acknowledged the events but the
      system does not have updated yet the database.

-  Alarm Severity: Critical, High, Medium and Low depending on the user
      configuration. The colour of the raws in this table is coloured
      based on the severity configured for the alarms. The system
      automatically assigns the font colour to enable the readability of
      the table. When the user has checked all the activations on an
      element as acknowledged, the system shifts the colour to a mostly
      muted one. The system represents active elements in bold font,
      non-active elements are shown in regular font.

-  Alarm Start Date: one single element could have related alarms that
      might be activated several times. The system keeps records of all
      of them and shows the start date of the most recent active
      activation among the most severe ones.

-  Alarm End Date: shows the end date of the above alarm.

-  Alarm Trigger Point: shows the value that triggered the alarm for the
      most recent and severe activation of the alarms.

-  Alarm Ack Date: the system shows the date of the most recent
      acknowledged among the most severe activations.

-  Alarm Ack Comment: shows the comment of the above activation.

-  Alarm Ack By: shows the user that acknowledged the above activation.

-  Times Activated on the Last 7 Days: number of activations of all the
      alarms related to the selected element on the last week.

-  Times Activated on the Last 30 Days number of activations of all the
      alarms related to the selected element on the last month.

-  Times Activated on the Last 90 Days: number of activations of all the
      alarms related to the selected element on the last quarter.

-  Times Activated on the Last 365 Days number of activations of all the
      alarms related to the selected element on the last year.

The user can obtain more information in the expanded row of every
Element in the grid. The system possesses one tab to capture and display
the most relevant information:

1. Historical Activations: it shows all the historical activations of
   all the alarms related to the element, including the acknowledged
   ones. The table shows the following fields:

-  Selected.

-  Alarm Name.

-  Alarm Type.

-  Severity.

-  Start Date.

-  End Date.

-  Trigger Point.

-  Ack Date.

-  ACK by.

-  ACK Comment.

   |image208|

Figure 90. Historical Activations tab

The colours of the activations within this table follow the same rule of
the main table, based on the severity and on the acknowledge status.
From the top-right menu the user can:

-  Acknowledge selected alarms |image209|. It allows the user to
      acknowledge the activations selected from the first column. The
      user could (not mandatory) add a comment to the acknowledgement
      and then save changes |image210|.

   |image211|

Figure 91. Acknowledging historical activations

-  Undo selected alarms acknowledgement |image212|. It allows the user
      to undo the acknowledgement for the activations selected from the
      first column.

-  Navigate to Alarms Performance\ |image213|. It allows the user to
      navigate to the Alarms Performance page that will be filtered by
      the Alarms related to the activations selected in the first
      column.

-  Disable severity colours\ |image214|. It allows the user to visualize
      a non-coloured table. The system represents active activations in
      bold.

   |image215|

Figure 92. Disabling severity colours

-  Change Filter mode\ |image216|.

-  Clear filter\ |image217|.

MANAGE ELEMENTS
---------------

This section allows the user to:

-  Load Filtered Elements |image218|. It allows the user to filter the
      alarms table by the network and/or the hierarchy elements checked
      in the Selection section. The system looks at the related elements
      of each alarm, filtering only those that belong to one of the
      element types choose.

-  Load Historical Information |image219|. It allows the user to
      navigate to a chart window where the system shows historical
      information of the element selected from the table. The system
      generates a chart for individual element selection. The chart
      includes both time-series and events that the user can customize
      as any other chart created in the Data Visualization page. The
      time-series and the events that the system loads in the chart
      depend on the related elements of the alarm that the user has
      selected:

   **PROFILES**

   a. if the related element is a **hierarchy element**, the system will
         upload to the chart the following information:

-  The time-series of signal that has generated the alarm (Note: The
      system, by default, hides all the series except for the one
      generating the alarm).

-  The time-series of all the other pressure and flow signals linked to
      the hierarchy element.

-  The time-series for the DDI and DL algorithms.

-  The events of the hierarchy element.

-  The events of all the network elements (flowmeters, pressure gauges
      etc.) belonging to that hierarchy element.

-  The events of the element to which any of the time-series in the
      chart belong to.

   |image220| |image221|

   |image222|

Figure 93. Historical Information for a DMA. (captura??)

a. if the target element is a **network element**, the system will
      upload to the chart the following information:

-  The time-series of the signal generating the alarm.

-  The time-series of the other signals belonging to the same network
      element (if any).

-  The time-series of all the signals of all the network elements in
      which the target network element is configured.

-  The time-series of the DLNE and DNFNE algorithms of the related
      element. DLARS, DSWORPS, MLARS, MSWORPS Site

-  The events of the target network element.

-  The events of the hierarchical elements to which the network element
      belong to.

-  The events of the element to which any of the time-series in the
      chart belong to.

   a. It usually happens that there is more than one related element. In
         those cases, the system will upload all the time-series and
         events related to them according to the above rules.

-  Show active alarms\ |image223|: it allows the user to enable/disable
      the visualization of the inactive elements. The system considers
      inactive elements those for which the user has acknowledged all
      the activations.

-  Acknowledge selected alarms\ |image224|. It allows the user to
      acknowledge all the activations of the elements that the user has
      selected from the table. The system pop-ups a window from where
      the user can add comments to the acknowledgement:

   |image225|

Figure 94. Acknowledging alarms

-  Navigate to Alarms Performance |image226|. It allows the user to
      navigate to the Alarms Performance page. The system automatically
      filters the page by the related alarms of the selected elements in
      the Alarmed Elements page.

-  Navigate to map |image227|: it allows the user to navigate to the Map
      page. The system loads the map with the layer of the element that
      the user has selected from the table. The map highlights and zooms
      to the selected element.

-  Navigate to data validation |image228|: it allows the user to the
      Data Validation page. The system loads the page with the telemetry
      signals related to the element/s that the user has selected from
      the table.

-  Configure severity colours\ |image229|: it allows the user to modify
      the by default colours for each one of the severity categories in
      the system.

   |image230|

Figure 95. Configuring severity colours

-  Disable severity colours\ |image231|: it allows the user to visualize
      non-coloured the alarms. The system keeps representing active
      alarms in bold font and the Non-active alarms in regular font.

-  Change Filter mode\ |image232|.

-  Clear filter\ |image233|.

-  Export to Excel\ |image234|: it allows the user to export to Excel
      the set of elements that the user has filtered in the table. It
      exports the columns visible in the table.

-  Export to Word\ |image235| it allows the user to export to Word in
      table format the set of elements that the user has filtered in the
      table. It exports the columns visible in the table.

-  Export to CSV\ |image236|: it allows the user to export to CSV format
      the set of elements that the user has filtered in the table. It
      exports the columns visible in the table

-  Manage columns\ |image237|.

4. .. rubric:: HISTORICAL CONFIGURATION (NETWORK ELEMENTS)
      :name: historical-configuration-network-elements

5. .. rubric:: WEEKLY PARK (?)
      :name: weekly-park

.. |image1| image:: /_static/media/image1.emf
   :width: 1in
.. |image2| image:: /_static/media/image2.png
   :width: 1.95833in
   :height: 7.24674in
.. |image3| image:: /_static/media/image3.png
   :width: 6.5in
   :height: 0.69722in
.. |image4| image:: /_static/media/image4.png
   :width: 6.44167in
   :height: 3.09097in
.. |image5| image:: /_static/media/image5.png
   :width: 0.20653in
   :height: 0.19625in
.. |image6| image:: /_static/media/image5.png
   :width: 0.20653in
   :height: 0.19625in
.. |image7| image:: /_static/media/image5.png
   :width: 0.20653in
   :height: 0.19625in
.. |image8| image:: /_static/media/image6.png
   :width: 0.18898in
   :height: 0.19685in
.. |image9| image:: /_static/media/image7.png
   :width: 6.44306in
   :height: 1.07153in
.. |image10| image:: /_static/media/image8.png
   :width: 6.44306in
   :height: 1.75139in
.. |image11| image:: /_static/media/image9.png
   :width: 2.13542in
   :height: 1.5625in
.. |image12| image:: /_static/media/image10.png
   :width: 2.1875in
   :height: 4in
.. |image13| image:: /_static/media/image11.png
   :width: 2.15625in
   :height: 2.07292in
.. |image14| image:: /_static/media/image12.png
   :width: 0.20866in
   :height: 0.19685in
.. |image15| image:: /_static/media/image13.png
   :width: 6.44306in
   :height: 3.63889in
.. |image16| image:: /_static/media/image14.png
   :width: 0.17331in
   :height: 0.22845in
.. |image17| image:: /_static/media/image15.png
   :width: 6.44306in
   :height: 3.64931in
.. |image18| image:: /_static/media/image14.png
   :width: 0.172in
   :height: 0.19645in
.. |image19| image:: /_static/media/image14.png
   :width: 0.172in
   :height: 0.19645in
.. |image20| image:: /_static/media/image14.png
   :width: 0.172in
   :height: 0.19645in
.. |image21| image:: /_static/media/image14.png
   :width: 0.14961in
   :height: 0.19685in
.. |image22| image:: /_static/media/image16.png
   :width: 5.75129in
   :height: 2.98958in
.. |image23| image:: /_static/media/image14.png
   :width: 0.172in
   :height: 0.19645in
.. |image24| image:: /_static/media/image14.png
   :width: 0.172in
   :height: 0.19645in
.. |image25| image:: /_static/media/image17.png
   :width: 0.20449in
   :height: 0.19635in
.. |image26| image:: /_static/media/image17.png
   :width: 0.20449in
   :height: 0.19635in
.. |image27| image:: /_static/media/image17.png
   :width: 0.20449in
   :height: 0.19635in
.. |image28| image:: /_static/media/image18.png
   :width: 2.20833in
   :height: 1.55208in
.. |image29| image:: /_static/media/image19.png
   :width: 2.72917in
   :height: 4.61458in
.. |image30| image:: /_static/media/image11.png
   :width: 2.15625in
   :height: 2.07292in
.. |image31| image:: /_static/media/image12.png
   :width: 0.20866in
   :height: 0.19685in
.. |image32| image:: /_static/media/image20.png
   :width: 0.19685in
   :height: 0.19685in
.. |image33| image:: /_static/media/image21.png
   :width: 6.44028in
   :height: 2.07986in
.. |image34| image:: /_static/media/image22.png
   :width: 0.21173in
   :height: 0.19636in
.. |image35| image:: /_static/media/image22.png
   :width: 0.21173in
   :height: 0.19636in
.. |image36| image:: /_static/media/image14.png
   :width: 0.172in
   :height: 0.19645in
.. |image37| image:: /_static/media/image14.png
   :width: 0.172in
   :height: 0.19645in
.. |image38| image:: /_static/media/image18.png
   :width: 2.20833in
   :height: 1.55208in
.. |image39| image:: /_static/media/image19.png
   :width: 2.72917in
   :height: 4.61458in
.. |image40| image:: /_static/media/image11.png
   :width: 2.15625in
   :height: 2.07292in
.. |image41| image:: /_static/media/image12.png
   :width: 0.20866in
   :height: 0.19685in
.. |image42| image:: /_static/media/image23.png
   :width: 6.4375in
   :height: 3.625in
.. |image43| image:: /_static/media/image24.png
   :width: 0.24171in
   :height: 0.23918in
.. |image44| image:: /_static/media/image25.png
   :width: 5.96707in
   :height: 3.00347in
.. |image45| image:: /_static/media/image26.png
   :width: 4.08333in
   :height: 0.48157in
.. |image46| image:: /_static/media/image27.png
   :width: 4.08333in
   :height: 0.53125in
.. |image47| image:: /_static/media/image24.png
   :width: 0.24171in
   :height: 0.23918in
.. |image48| image:: /_static/media/image28.png
   :width: 0.19685in
   :height: 0.19685in
.. |image49| image:: /_static/media/image24.png
   :width: 0.24171in
   :height: 0.23918in
.. |image50| image:: /_static/media/image24.png
   :width: 0.24171in
   :height: 0.23918in
.. |image51| image:: /_static/media/image24.png
   :width: 0.24171in
   :height: 0.23918in
.. |image52| image:: /_static/media/image18.png
   :width: 2.20833in
   :height: 1.55208in
.. |image53| image:: /_static/media/image19.png
   :width: 2.72917in
   :height: 4.61458in
.. |image54| image:: /_static/media/image11.png
   :width: 2.15625in
   :height: 2.07292in
.. |image55| image:: /_static/media/image12.png
   :width: 0.20866in
   :height: 0.19685in
.. |image56| image:: /_static/media/image29.png
   :width: 6.44306in
   :height: 3.00208in
.. |image57| image:: /_static/media/image30.png
   :width: 0.20299in
   :height: 0.19653in
.. |image58| image:: /_static/media/image31.png
   :width: 3.35751in
   :height: 2.6944in
.. |image59| image:: /_static/media/image30.png
   :width: 0.20299in
   :height: 0.19653in
.. |image60| image:: /_static/media/image30.png
   :width: 0.20299in
   :height: 0.19653in
.. |image61| image:: /_static/media/image24.png
   :width: 0.24171in
   :height: 0.23918in
.. |image62| image:: /_static/media/image24.png
   :width: 0.24171in
   :height: 0.23918in
.. |image63| image:: /_static/media/image18.png
   :width: 2.20833in
   :height: 1.55208in
.. |image64| image:: /_static/media/image19.png
   :width: 2.72917in
   :height: 4.61458in
.. |image65| image:: /_static/media/image11.png
   :width: 2.15625in
   :height: 2.07292in
.. |image66| image:: /_static/media/image12.png
   :width: 0.20866in
   :height: 0.19685in
.. |image67| image:: /_static/media/image32.png
   :width: 5.81117in
   :height: 1.11551in
.. |image68| image:: /_static/media/image33.png
   :width: 5.90973in
   :height: 1.08422in
.. |image69| image:: /_static/media/image34.png
   :width: 2.19792in
   :height: 4in
.. |image70| image:: /_static/media/image35.png
   :width: 2.21875in
   :height: 1.58333in
.. |image71| image:: /_static/media/image36.png
   :width: 5.83262in
   :height: 2.85847in
.. |image72| image:: /_static/media/image37.png
   :width: 5.1159in
   :height: 2.49233in
.. |image73| image:: /_static/media/image38.png
   :width: 2.23958in
   :height: 2.05208in
.. |image74| image:: /_static/media/image39.png
   :width: 4.10904in
   :height: 2.01352in
.. |image75| image:: /_static/media/image40.png
   :width: 5.77117in
   :height: 2.76864in
.. |image76| image:: /_static/media/image41.png
   :width: 5.87953in
   :height: 2.70403in
.. |image77| image:: /_static/media/image42.png
   :width: 2.21875in
   :height: 5.48958in
.. |image78| image:: /_static/media/image43.png
   :width: 6.12068in
   :height: 3.44659in
.. |image79| image:: /_static/media/image44.png
   :width: 4.84375in
   :height: 2.48958in
.. |image80| image:: /_static/media/image45.png
   :width: 3.46875in
   :height: 5.29167in
.. |image81| image:: /_static/media/image46.png
   :width: 3.48958in
   :height: 8.58333in
.. |image82| image:: /_static/media/image47.png
   :width: 3.51042in
   :height: 5.44792in
.. |image83| image:: /_static/media/image48.png
   :width: 3.89583in
   :height: 3.0814in
.. |image84| image:: /_static/media/image6.png
   :width: 0.18898in
   :height: 0.19685in
.. |image85| image:: /_static/media/image49.png
   :width: 6.44306in
   :height: 2.97986in
.. |image86| image:: /_static/media/image50.png
   :width: 6.44306in
   :height: 2.76111in
.. |image87| image:: /_static/media/image52.png
   :width: 6.33963in
   :height: 3.44723in
.. |image88| image:: /_static/media/image20.png
   :width: 0.19685in
   :height: 0.19685in
.. |image89| image:: /_static/media/image5.png
   :width: 0.20653in
   :height: 0.19625in
.. |image90| image:: /_static/media/image5.png
   :width: 0.20653in
   :height: 0.19625in
.. |image91| image:: /_static/media/image53.png
   :width: 3.22318in
   :height: 6.81148in
.. |image92| image:: /_static/media/image20.png
   :width: 0.19685in
   :height: 0.19685in
.. |image93| image:: /_static/media/image54.png
   :width: 0.18898in
   :height: 0.19685in
.. |image94| image:: /_static/media/image55.png
   :width: 3.36458in
   :height: 1.28125in
.. |image95| image:: /_static/media/image56.png
   :width: 6.44306in
   :height: 2.94097in
.. |image96| image:: /_static/media/image5.png
   :width: 0.20653in
   :height: 0.19625in
.. |image97| image:: /_static/media/image20.png
   :width: 0.19685in
   :height: 0.19685in
.. |image98| image:: /_static/media/image5.png
   :width: 0.20653in
   :height: 0.19625in
.. |image99| image:: /_static/media/image5.png
   :width: 0.20653in
   :height: 0.19625in
.. |image100| image:: /_static/media/image57.png
   :width: 5.84709in
   :height: 1.57868in
.. |image101| image:: /_static/media/image58.png
   :width: 5.81503in
   :height: 1.66717in
.. |image102| image:: /_static/media/image59.png
   :width: 0.21875in
   :height: 0.22257in
.. |image103| image:: /_static/media/image59.png
   :width: 0.21875in
   :height: 0.22257in
.. |image104| image:: /_static/media/image59.png
   :width: 0.21875in
   :height: 0.22257in
.. |image105| image:: /_static/media/image59.png
   :width: 0.21875in
   :height: 0.22257in
.. |image106| image:: /_static/media/image59.png
   :width: 0.17919in
   :height: 0.22222in
.. |image107| image:: /_static/media/image60.png
   :width: 3.54167in
   :height: 1.44792in
.. |image108| image:: /_static/media/image5.png
   :width: 0.20653in
   :height: 0.19625in
.. |image109| image:: /_static/media/image5.png
   :width: 0.20653in
   :height: 0.19625in
.. |image110| image:: /_static/media/image61.png
   :width: 0.19685in
   :height: 0.19685in
.. |image111| image:: /_static/media/image62.png
   :width: 6.33738in
   :height: 2.47744in
.. |image112| image:: /_static/media/image63.png
   :width: 6.44306in
   :height: 1.79236in
.. |image113| image:: /_static/media/image64.png
   :width: 6.34484in
   :height: 3.61926in
.. |image114| image:: /_static/media/image65.png
   :width: 6.44306in
   :height: 0.82075in
.. |image115| image:: /_static/media/image66.png
   :width: 0.20079in
   :height: 0.19685in
.. |image116| image:: /_static/media/image67.png
   :width: 0.21654in
   :height: 0.19685in
.. |image117| image:: /_static/media/image68.png
   :width: 5.76317in
   :height: 2.59026in
.. |image118| image:: /_static/media/image69.png
   :width: 0.1991in
   :height: 0.19653in
.. |image119| image:: /_static/media/image69.png
   :width: 0.1991in
   :height: 0.19653in
.. |image120| image:: /_static/media/image70.png
   :width: 5.71248in
   :height: 2.51517in
.. |image121| image:: /_static/media/image71.png
   :width: 5.70757in
   :height: 3.81161in
.. |image122| image:: /_static/media/image66.png
   :width: 0.20079in
   :height: 0.19685in
.. |image123| image:: /_static/media/image72.png
   :width: 6.44306in
   :height: 3.29306in
.. |image124| image:: /_static/media/image69.png
   :width: 0.1991in
   :height: 0.19653in
.. |image125| image:: /_static/media/image69.png
   :width: 0.1991in
   :height: 0.19653in
.. |image126| image:: /_static/media/image69.png
   :width: 0.1991in
   :height: 0.19653in
.. |image127| image:: /_static/media/image73.png
   :width: 0.19905in
   :height: 0.19653in
.. |image128| image:: /_static/media/image73.png
   :width: 0.23264in
   :height: 0.19651in
.. |image129| image:: /_static/media/image73.png
   :width: 0.19861in
   :height: 0.1964in
.. |image130| image:: /_static/media/image73.png
   :width: 0.19861in
   :height: 0.1964in
.. |image131| image:: /_static/media/image73.png
   :width: 0.18667in
   :height: 0.19653in
.. |image132| image:: /_static/media/image75.png
   :width: 6.44306in
   :height: 2.66389in
.. |image133| image:: /_static/media/image5.png
   :width: 0.20653in
   :height: 0.19625in
.. |image134| image:: /_static/media/image5.png
   :width: 0.20653in
   :height: 0.19625in
.. |image135| image:: /_static/media/image76.png
   :width: 6.44306in
   :height: 2.66042in
.. |image136| image:: /_static/media/image5.png
   :width: 0.20653in
   :height: 0.19625in
.. |image137| image:: /_static/media/image5.png
   :width: 0.20653in
   :height: 0.19625in
.. |image138| image:: /_static/media/image77.png
   :width: 5.90184in
   :height: 2.38542in
.. |image139| image:: /_static/media/image14.png
   :width: 0.172in
   :height: 0.19645in
.. |image140| image:: /_static/media/image14.png
   :width: 0.172in
   :height: 0.19645in
.. |image141| image:: /_static/media/image78.png
   :width: 4.25in
   :height: 4.17708in
.. |image142| image:: /_static/media/image14.png
   :width: 0.172in
   :height: 0.19645in
.. |image143| image:: /_static/media/image14.png
   :width: 0.172in
   :height: 0.19645in
.. |image144| image:: /_static/media/image79.png
   :width: 5.98472in
   :height: 3.32198in
.. |image145| image:: /_static/media/image80.png
   :width: 3.375in
   :height: 1.34375in
.. |image146| image:: /_static/media/image81.png
   :width: 6.44306in
   :height: 3.61597in
.. |image147| image:: /_static/media/image82.png
   :width: 0.23121in
   :height: 0.19653in
.. |image148| image:: /_static/media/image82.png
   :width: 0.1941in
   :height: 0.19597in
.. |image149| image:: /_static/media/image83.png
   :width: 5.80196in
   :height: 2.2625in
.. |image150| image:: /_static/media/image82.png
   :width: 0.23121in
   :height: 0.19653in
.. |image151| image:: /_static/media/image82.png
   :width: 0.23121in
   :height: 0.19653in
.. |image152| image:: /_static/media/image82.png
   :width: 0.1941in
   :height: 0.19597in
.. |image153| image:: /_static/media/image84.png
   :width: 6.44028in
   :height: 2.94375in
.. |image154| image:: /_static/media/image85.png
   :width: 0.18504in
   :height: 0.19685in
.. |image155| image:: /_static/media/image86.png
   :width: 0.21041in
   :height: 0.19653in
.. |image156| image:: /_static/media/image87.png
   :width: 0.19307in
   :height: 0.23762in
.. |image157| image:: /_static/media/image88.png
   :width: 5.828in
   :height: 1.23935in
.. |image158| image:: /_static/media/image86.png
   :width: 0.20718in
   :height: 0.21107in
.. |image159| image:: /_static/media/image87.png
   :width: 0.18194in
   :height: 0.17708in
.. |image160| image:: /_static/media/image5.png
   :width: 0.20653in
   :height: 0.19625in
.. |image161| image:: /_static/media/image89.png
   :width: 2.25in
   :height: 6.13542in
.. |image162| image:: /_static/media/image90.png
   :width: 5.9886in
   :height: 2.90672in
.. |image163| image:: /_static/media/image6.png
   :width: 0.18898in
   :height: 0.19685in
.. |image164| image:: /_static/media/image7.png
   :width: 6.44306in
   :height: 1.07153in
.. |image165| image:: /_static/media/image12.png
   :width: 0.20866in
   :height: 0.19685in
.. |image166| image:: /_static/media/image92.png
   :width: 6.44306in
   :height: 1.53889in
.. |image167| image:: /_static/media/image93.png
   :width: 0.22835in
   :height: 0.19685in
.. |image168| image:: /_static/media/image14.png
   :width: 0.172in
   :height: 0.19645in
.. |image169| image:: /_static/media/image94.png
   :width: 5.82468in
   :height: 1.98416in
.. |image170| image:: /_static/media/image93.png
   :width: 0.22835in
   :height: 0.19685in
.. |image171| image:: /_static/media/image93.png
   :width: 0.22835in
   :height: 0.19685in
.. |image172| image:: /_static/media/image93.png
   :width: 0.22835in
   :height: 0.19685in
.. |image173| image:: /_static/media/image95.png
   :width: 5.94453in
   :height: 1.5486in
.. |image174| image:: /_static/media/image5.png
   :width: 0.20653in
   :height: 0.19625in
.. |image175| image:: /_static/media/image5.png
   :width: 0.20653in
   :height: 0.19625in
.. |image176| image:: /_static/media/image96.png
   :width: 6.44306in
   :height: 1.66181in
.. |image177| image:: /_static/media/image97.png
   :width: 6.44306in
   :height: 1.01875in
.. |image178| image:: /_static/media/image82.png
   :width: 0.23121in
   :height: 0.19653in
.. |image179| image:: /_static/media/image5.png
   :width: 0.20653in
   :height: 0.19625in
.. |image180| image:: /_static/media/image5.png
   :width: 0.20653in
   :height: 0.19625in
.. |image181| image:: /_static/media/image100.png
   :width: 0.21654in
   :height: 0.19685in
.. |image182| image:: /_static/media/image100.png
   :width: 0.21654in
   :height: 0.19685in
.. |image183| image:: /_static/media/image101.png
   :width: 5.69811in
   :height: 2.79317in
.. |image184| image:: /_static/media/image100.png
   :width: 0.21654in
   :height: 0.19685in
.. |image185| image:: /_static/media/image100.png
   :width: 0.21654in
   :height: 0.19685in
.. |image186| image:: /_static/media/image102.png
   :width: 5.82558in
   :height: 3.68887in
.. |image187| image:: /_static/media/image100.png
   :width: 0.21654in
   :height: 0.19685in
.. |image188| image:: /_static/media/image103.png
   :width: 4.16667in
   :height: 3.35417in
.. |image189| image:: /_static/media/image100.png
   :width: 0.21654in
   :height: 0.19685in
.. |image190| image:: /_static/media/image104.png
   :width: 3.29167in
   :height: 1.30208in
.. |image191| image:: /_static/media/image100.png
   :width: 0.21654in
   :height: 0.19685in
.. |image192| image:: /_static/media/image100.png
   :width: 0.21654in
   :height: 0.19685in
.. |image193| image:: /_static/media/image100.png
   :width: 0.21654in
   :height: 0.19685in
.. |image194| image:: /_static/media/image100.png
   :width: 0.21654in
   :height: 0.19685in
.. |image195| image:: /_static/media/image105.png
   :width: 3.22917in
   :height: 3.35417in
.. |image196| image:: /_static/media/image100.png
   :width: 0.21654in
   :height: 0.19685in
.. |image197| image:: /_static/media/image5.png
   :width: 0.20653in
   :height: 0.19625in
.. |image198| image:: /_static/media/image5.png
   :width: 0.20653in
   :height: 0.19625in
.. |image199| image:: /_static/media/image100.png
   :width: 0.21654in
   :height: 0.19685in
.. |image200| image:: /_static/media/image100.png
   :width: 0.21654in
   :height: 0.19685in
.. |image201| image:: /_static/media/image100.png
   :width: 0.21654in
   :height: 0.19685in
.. |image202| image:: /_static/media/image100.png
   :width: 0.21654in
   :height: 0.19685in
.. |image203| image:: /_static/media/image106.png
   :width: 2.17708in
   :height: 6.05208in
.. |image204| image:: /_static/media/image107.png
   :width: 6.4in
   :height: 3in
.. |image205| image:: /_static/media/image6.png
   :width: 0.18898in
   :height: 0.19685in
.. |image206| image:: /_static/media/image108.png
   :width: 6.44306in
   :height: 0.65417in
.. |image207| image:: /_static/media/image12.png
   :width: 0.20866in
   :height: 0.19685in
.. |image208| image:: /_static/media/image109.png
   :width: 6.44306in
   :height: 1.19375in
.. |image209| image:: /_static/media/image93.png
   :width: 0.22835in
   :height: 0.19685in
.. |image210| image:: /_static/media/image14.png
   :width: 0.172in
   :height: 0.19645in
.. |image211| image:: /_static/media/image94.png
   :width: 5.82468in
   :height: 1.98416in
.. |image212| image:: /_static/media/image93.png
   :width: 0.22835in
   :height: 0.19685in
.. |image213| image:: /_static/media/image110.png
   :width: 0.19685in
   :height: 0.19685in
.. |image214| image:: /_static/media/image93.png
   :width: 0.22835in
   :height: 0.19685in
.. |image215| image:: /_static/media/image111.png
   :width: 5.76522in
   :height: 1.19555in
.. |image216| image:: /_static/media/image5.png
   :width: 0.20653in
   :height: 0.19625in
.. |image217| image:: /_static/media/image5.png
   :width: 0.20653in
   :height: 0.19625in
.. |image218| image:: /_static/media/image100.png
   :width: 0.21654in
   :height: 0.19685in
.. |image219| image:: /_static/media/image100.png
   :width: 0.21654in
   :height: 0.19685in
.. |image220| image:: /_static/media/image112.png
   :width: 3.07692in
   :height: 2.41206in
.. |image221| image:: /_static/media/image113.png
   :width: 3.16436in
   :height: 2.27317in
.. |image222| image:: /_static/media/image101.png
   :width: 5.69811in
   :height: 2.79317in
.. |image223| image:: /_static/media/image100.png
   :width: 0.21654in
   :height: 0.19685in
.. |image224| image:: /_static/media/image100.png
   :width: 0.21654in
   :height: 0.19685in
.. |image225| image:: /_static/media/image114.png
   :width: 5.83751in
   :height: 3.69767in
.. |image226| image:: /_static/media/image100.png
   :width: 0.21654in
   :height: 0.19685in
.. |image227| image:: /_static/media/image100.png
   :width: 0.21654in
   :height: 0.19685in
.. |image228| image:: /_static/media/image100.png
   :width: 0.21654in
   :height: 0.19685in
.. |image229| image:: /_static/media/image100.png
   :width: 0.21654in
   :height: 0.19685in
.. |image230| image:: /_static/media/image105.png
   :width: 3.22917in
   :height: 3.35417in
.. |image231| image:: /_static/media/image100.png
   :width: 0.21654in
   :height: 0.19685in
.. |image232| image:: /_static/media/image5.png
   :width: 0.20653in
   :height: 0.19625in
.. |image233| image:: /_static/media/image5.png
   :width: 0.20653in
   :height: 0.19625in
.. |image234| image:: /_static/media/image100.png
   :width: 0.21654in
   :height: 0.19685in
.. |image235| image:: /_static/media/image100.png
   :width: 0.21654in
   :height: 0.19685in
.. |image236| image:: /_static/media/image100.png
   :width: 0.21654in
   :height: 0.19685in
.. |image237| image:: /_static/media/image100.png
   :width: 0.21654in
   :height: 0.19685in
