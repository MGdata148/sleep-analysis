# Sleep analysis

### Background
The ability to sleep is a superpower. When we sleep, our physical and mental activity, as well as consciousness are reduced, helping to restore the basic properties of the body’s systems. Sleep is essential for human survival and affects crucial processes and aspects of organism functioning: neurodevelopment, synaptic plasticity, mental health, memory consolidation, metabolic functions, immune system and general well-being [(Miletinova and Buskowa, 2021)](https://pmc.ncbi.nlm.nih.gov/articles/PMC8820572/). Sleep deprivation can lead to physical and cognitive function impairment and is linked to higher risk of health problems [(Liew and Aung, 2021)](https://www.sciencedirect.com/science/article/pii/S1389945720303701?via%3Dihub). Therefore, it is particularly important to recognize factors contributing to sleep quality in order to provide meaningful insights for healthcare providers and people willing to improve their lifestyle.

### Project aim
The aim of this project is to identify the association between lifestyle patterns and sleep in the examined population and to compare the obtained results with the literature data.

### About dataset
The dataset `lifestyle_info` originally called [Sleep, Health & Lifestyle](https://www.kaggle.com/datasets/henryshan/sleep-health-and-lifestyle) was obtained from [Kaggle](https://www.kaggle.com/) and contains information associated with sleep, health and physical activity of 373 individuals.

#### The variables are as follows:
- `id` - a unique identifier for each participant
- `gender` - the participant's gender (Male/Female)
- `age` - the participant's age in years
- `occupation` - the job or career of the participant
- `sleep_duration` - the daily sleep duration of the participant in hours
- `sleep_quality` - a subjective assessment of sleep quality on a scale from 1 to 10
- `physical_activity_level` - the daily duration of physical activity for the participant, measured in minutes
- `stress_level` - a subjective assessment of the participant's stress level on a scale from 1 to 10
- `bmi_category` - the participant's BMI classification (e.g., Underweight, Normal, Overweight)
- `blood_pressure` - the participant's blood pressure, represented as systolic pressure over diastolic pressure
- `heart_rate` - the participant's resting heart rate, measured in beats per minute
- `daily_steps` - the number of steps the participant takes each day
- `sleep_disorder` - the presence or absence of a sleep disorder in the participant (None, Insomnia, Sleep Apnea)

### Research questions
1.	Who sleeps better considering age, gender and occupation?
2.	How stress, physical activity and basic health indicators associate with sleep parameters?
3.	What are the differences between healthy individuals and those with sleeping disorder?

### Data analysis and visualisation
Data was analyzed using [PostgreSQL](https://www.postgresql.org/) and visualised in [Tableau](https://public.tableau.com/app/discover). 
- [Data cleaning and analysis](https://github.com/MGdata148/sleep-analysis/blob/main/code)
- [Results](https://github.com/MGdata148/sleep-analysis/blob/main/results.docx)
- Visualisation

### Discussion

#### 1.	Who sleeps better considering age, gender and occupation?

In this population sleep parameters were strongly related - the longer the sleep, the better the reported sleep quality. Sleep parameters showed a moderate positive correlation with age with the best results in the oldest age categories, however scientific studies conducted on large cohorts do not prove the existence of a clear relationship, pointing to the optimal sleep duration of 7-8h for adults of any age [(Chaput et al., 2020)](https://cdnsciencepub.com/doi/full/10.1139/apnm-2020-0034). In general, sleep parameters were better in females than in males, but comparison of sleep in different age categories revealed opposite tendency due to age bias - males were on average younger than females with the two oldest age categories reporting the best sleep parameters consisting only of females. Large cohort literature data indicates that females tend to have worse sleep quality than males [(Fatima, Doi et al., 2016)](http://www.clinmedres.org/content/14/3-4/138.short).
Considering occupation, there were differences in sleep parameters, possibly influenced by occupation-dependent stress level, however some categories were strongly underrepresented, therefore occupation influence was not further analyzed.

#### 2.	How stress, physical activity and basic health indicators associate with sleep parameters?

#### 3.	What are the differences between healthy individuals and those with sleeping disorder?

### Conclusions








