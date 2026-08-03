# MB5370 Module 1 Workshop 4

Workshop 4: The developer’s toolbox and AI focuses on integrating AI assisted coding tools with core programming concepts to build efficient automated analytical workflows. Using the palmer penguins dataset, the workshop introduced github copilot to generate a multi-variable scatter plot of bill length against bill depth that was coloured by species. Other graphs that were created was a boxplot of flipper length by species faceted by island, and a scatter plot of body mass against flipper length that had linear regression trend lines fitted for each specie. Both of these graphs used custom colour palettes and labelled visualisations.

The workshop then introduced chattr as an AI engine embedded within R studio which helped to demonstrate its use alongside traditional logic. This included simple statements like checking sea surface temperature against marine heatwave threshold as well as vectorized alternatives using dplyr::if_else() and dplyr::case_when() to classify coral monitoring sites by depth zone and marine stations by salinity-based environment type.

Automation and iteration were covered next, comparing traditional base R for-loops with functional programming alternatives from the purr package. The examples used in the workshop included looping through transect lengths and site areas, calculating summary statistics (e.g. species means from fish count data) using both a for-loop and the equivalent map_dbl() function, and applying map() to iterate a summary function. 

The workshop then covered writing custom functions, using a coral mortality rate calculation as a worked example and a temperature conversion function (Celsius to Fahrenheit) as a practice task which included basic input validation and error handling (e.g. rejecting physically impossible temperatures).

Overall, this workshop combined AI-assisted coding tools with conditional logic, iteration, and custom function-writing, equipping students with practical, scalable approaches to building automated and error-safe analytical workflows in R.

