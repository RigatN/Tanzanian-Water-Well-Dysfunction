# ![wells image](https://github.com/RigatN/Tanzanian-Water-Well-Dysfunction/blob/main/Images/well2.PNG)

# Tanzanian Water Well Dysfunction

## Overview

The machine learning model developed for this project will be trained to classify water pumps into one of three categories: functional, in need of repairs, or non-functional. The predictions made by the model will include identifying non-functional pumps, thus aiding in prioritizing maintenance efforts to address issues promptly and ensure a sustainable and reliable water supply for communities.

## Business Understanding

In Tanzania, ensuring the accessibility and functionality of water pumps is vital for delivering clean and potable water to communities. Many rural areas rely on these pumps for their water supply. However, issues such as pump malfunctions and breakdowns can lead to water scarcity, impacting public health, agriculture, and overall community well-being.

The primary goal of this project is to develop a predictive maintenance model for water pumps, enabling proactive identification of pumps at risk of dysfunctionality. By leveraging machine learning, we aim to optimize maintenance operations, prioritize interventions, and minimize downtime for non-functional pumps.

## Data Understanding

The dataset, sourced from Taarifa and the Tanzanian Ministry of Water, consists of 59,400 records capturing various variables related to water pumps. The dataset encompasses diverse variables, including operational characteristics, installation details, and management practices. Key features such as the amount of water pumped, pump type, installation year, geographical location, and management group provide valuable insights. The target variable, functionality status, exhibits an imbalance with 27,435 functional, 19,386 non-functional, and 3,321 in need of repair instances. Understanding this distribution is crucial for model development, evaluation, and addressing the specific challenges posed by imbalanced classes.

# ![Data understanding](https://github.com/RigatN/Tanzanian-Water-Well-Dysfunction/blob/main/Images/well_tab.PNG)



## Data Preparation

The dataset underwent a review, involving cleaning, consolidation of databases and tables, and subsequent refinement to ensure a targeted focus on pertinent elements for the analysis. To consolidate the databases & tables, inner joins were used. Duplicates were removed by title, and then, because most movies have two or more genres, '.explode' was used on the dataframe in order to have one row per genre per movie. This allowed us to subset by the horror genre first.


## Results and Recommendations

#### Winning model

Our third recommendation emphasizes the adoption and implementation of a predictive model that exhibits commendable recall scores across all classes. This model, boasting a recall score of 72% for the "Functional" class, 73% for the "Non-Functional" class, and another 73% for the "Functional Needs Repair" class, demonstrates its effectiveness in correctly identifying and classifying instances within each category. A high recall score signifies the model's capability to capture a significant portion of the true positive cases, minimizing the chances of overlooking critical issues. By embracing this model, we can enhance our ability to identify and address water pump functionality concerns promptly.

# ![Different model score comparssion](https://github.com/RigatN/Tanzanian-Water-Well-Dysfunction/blob/main/Images/model_dis.PNG)

# ![Score of winning model](https://github.com/RigatN/Tanzanian-Water-Well-Dysfunction/blob/main/Images/score11.PNG)

the top important features selected by the winning model are

# ![Heat map](https://github.com/RigatN/Tanzanian-Water-Well-Dysfunction/blob/main/Images/heatmap.PNG)


#### Community involvement and awareness creation  

Enhance the impact of our initiative, we strongly recommend active community involvement and dedicated efforts toward raising awareness. Engaging with local communities is pivotal for the success of any project aiming to address water-related challenges. Establishing partnerships with community leaders, organizations, and local influencers will foster a sense of ownership and shared responsibility.
# ![Managmetn Vs Status groups](https://github.com/RigatN/Tanzanian-Water-Well-Dysfunction/blob/main/Images/schem.PNG)


#### Preventive maintenance Specially for old wells 

Establishing a comprehensive preventive maintenance program involves regular inspections, routine assessments, and timely repairs. This initiative not only addresses minor issues before they escalate but also extends the lifespan of the wells, reducing the likelihood of major breakdowns.

# ![Age of well VS status group](https://github.com/RigatN/Tanzanian-Water-Well-Dysfunction/blob/main/Images/age.PNG)

## Conclusion 

The high recall scores signify the model's robust capability to capture a significant proportion of true positive cases, thereby minimizing the risk of overlooking critical issues. Embracing this model holds the potential to enhance our responsiveness to water pump functionality concerns, contributing to the overall efficiency of our water management system. This strategic adoption underscores our commitment to ensuring accurate and timely interventions based on the model's reliable predictions, ultimately advancing our mission for sustainable and effective water resource management.

## Next Step

- Improve model
- Look into the depth of well
- Geographical impacts


## For More Information

Please see the full modeling notebooks in the [baseline_model](Notebooks) or the [Modeling2]().

## Repo Structure

```
├── Data
├── images
├── Notebooks
├── README.md
```
