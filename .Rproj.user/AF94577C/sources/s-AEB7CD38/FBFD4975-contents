# Libraries
library(tidyverse)
library(janitor)


members <- readr::read_csv('https://raw.githubusercontent.com/rfordatascience/tidytuesday/master/data/2020/2020-09-22/members.csv')
expeditions <- readr::read_csv('https://raw.githubusercontent.com/rfordatascience/tidytuesday/master/data/2020/2020-09-22/expeditions.csv')
peaks <- readr::read_csv('https://raw.githubusercontent.com/rfordatascience/tidytuesday/master/data/2020/2020-09-22/peaks.csv')


write_csv(members, "raw_data/members.csv")
write_csv(expeditions, "raw_data/expeditions.csv")
write_csv(peaks, "raw_data/peaks.csv")


### Write to CSV
write_csv(expeditions, "clean_data/expeditions.csv")
write_csv(members, "clean_data/members.csv")
write_csv(peaks, "clean_data/peaks.csv")
