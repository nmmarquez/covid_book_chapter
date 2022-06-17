# contact steve goodreau
rm(list=ls())
library(tidyverse)

data_names <- "./Data/COVID-19_Case_Surveillance_" %>%
  str_c("Public_Use_Data_with_Geography.tsv") %>%
  read_tsv(n_max = 1) %>%
  names()

wa_df <- read_tsv("./Data/WA.tsv", col_names = data_names)

wa_df %>%
  head()
