# data_visualization_with-_ggplot_using_R
# this file is coming from DQLAB 
# first I am going to share how to make pivot

-library(tidyr
-library(dplyr)
-glimpse(road)
-road <- 
-road %>% 
-pivot_longer(   
-cols = starts_with("way"),
 names_to = "condition",
 names_prefix = "way",
 values_to = "long"
 )
-glimpse(road)
