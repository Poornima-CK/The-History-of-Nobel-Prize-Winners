# The-History-of-Nobel-Prize-Winners - Python

## Project description

The Nobel Prize has been among the most prestigious international awards since 1901. Each year, awards are bestowed in chemistry, literature, physics, physiology or medicine, economics, and peace. In addition to the honor, prestige, and substantial prize money, the recipient also gets a gold medal with an image of Alfred Nobel (1833 - 1896), who established the prize.

The Nobel Foundation has made a dataset available of all prize winners from the outset of the awards from 1901 to 2023. The dataset used in this project is from the Nobel Prize API and is available in the `nobel.csv` file in the `data` folder.

## Project Goal
Analyze Nobel prize winner data, explore data, identify patterns and answer several questions related to this prizewinning data. 

## Data
data/nobel.csv

## Steps involved
**Step 1:** 

Loading in required libraries

import pandas as pd
import seaborn as sns
import numpy as np

**Step 2:** 

Answer the given business questions

**Question 1:** 

What is the most commonly awarded gender and birth country?

- Store your answers as string variables `top_gender` and `top_country`.

**Question 2:** 

Which decade had the highest ratio of US-born Nobel Prize winners to total winners in all categories?

- Store this as an integer called `max_decade_usa`.

**Question 3:** 

Which decade and Nobel Prize category combination had the highest proportion of female laureates?

- Store this as a dictionary called `max_female_dict` where the decade is the key and the category is the value. There should only be one key:value pair.

**Question 4:** 

Who was the first woman to receive a Nobel Prize, and in what category?

- Save your string answers as `first_woman_name` and `first_woman_category`.

**Question 5:**

Which individuals or organizations have won more than one Nobel Prize throughout the years?

- Store the full names in a list named `repeat_list`.
