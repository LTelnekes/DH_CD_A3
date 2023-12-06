## Terrorism in the United States 2001 - 2016 
### Collecting Data Assignment 3a 

For this assignment, I will be exploring a dataset on terrorist attacks in the United States post-9/11 until 2016. I gathered the date from Kaggle, from the collaborator New America. The data is accessible in this Github Repository and on [Kaggle](https://www.kaggle.com/datasets/newamerica/terrorist-activity/data.) 

The data includes two sets, one on the plots and one on the suspects. I will make use of both sets for this assignment. 

  - **'plots.csv':** Contains the terrorist attacks which took place or were prevented between 2011 and 2016
  - **'suspects.csv':** Contains all the suspects of the (prevented) attacks

The creator described the curated datasets as follows: *"The data in this report consists of individuals accused of terrorism and related crimes since September 11, 2001, who are either American citizens or who engaged in terrorist activity within the United States. The data includes some individuals who died before being charged with a crime, but were widely reported to have engaged in terrorist activity."*

### Data Overview

**plots.csv**

| Variable      | Description                                  |
| ------------- | -------------------------------------------- |
| plot_ID       | ID number of the plot                        |
| plot_name     | Year and location of the plot              |
| plot_ideology  | Ideology of the plot                     |
| plot_status          | If the plot was prevented or not   |
| prevention_method       | How the plot was prevented                      |
| attack_date    | The date of the Attack    |
| victims_wounded           | The amount of victims wounded                         |
| victims_killed           | The amount of victims killed                         |

**suspects.csv**

| Variable      | Description                                  |
| ------------- | -------------------------------------------- |
| suspect_ID       | ID number of the suspect                        |
| first_name     | The first name of the suspect              |
| last_name  | The last name of the suspect                     |
| full_name          | The full name of the suspect  |
| sex       | The sex of the suspect                     |
| age    | The age of the suspect  |
| marital_status           | The marital status of the suspect                         |
| last_residence           | The last residence of the suspect                      |
| plot_ID       | ID number of the plot                        |
| terror_plot     | The year and location of the plot they are suspect for             |
| terror_plot2           | The second year and location of the plot they are suspect for         |
| informant_use           | Yes or no                       |
| public_tip       | Yes or no                       |
| family/community_tip     | Yes or no            |
| israel/judaism_target           | Yes or no                         |
| military_target          | Yes or no                         |
| awlaki_contact           | None or ties                     |
| foreign_militant_contact       | Yes or no                       |
| online_radicalization   | Yes or no             |
| overseas_military_training          | Yes or no                         |
| us_military_experience           | Yes or no                          |
| suspect_status       | Status of the suspect's charge                       |
| date_charged   | The date the suspect was charged             |
| state_charged       | The state in which the suspect was charged                     |
| state_charged2   | The second state in which the suspect was charged           |



