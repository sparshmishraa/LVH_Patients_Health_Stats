# LVH Patients Health Stats
Analysis of Heart failure prediction dataset using Excel and Tableau

![Heart-Xray-Chest_1000x600-1000x600 (1)](https://github.com/SparshMishra42/Heart_Health_Analysis/assets/143194226/b76818df-f838-4c02-937a-a44a22d5ec1d)


# Details about the LVH or Left Ventricular Hypertrophy condition:

LVH, or Left Ventricular Hypertrophy, is a condition that occurs when the heart's left ventricle muscle thickens and enlarges.

The left ventricle pumps blood into the aorta (the largest artery in the body), which sends this oxygenated blood to tissues throughout your body.

Thicker walls in the left ventricle can interfere with your heart’s ability to pump blood into the aorta.

**SOURCES**: https://my.clevelandclinic.org/health/diseases/21883-left-ventricular-hypertrophy.
         https://www.heart.org/en/health-topics/heart-valve-problems-and-disease/heart-valve-problems-and-causes/what-is-left-ventricular-hypertrophy-lvh
         
# Data Cleaning & Preparation

## Data Cleaning:

1  Check for duplicate values- No duplicates found

2  Blank and formatting- No blank values found and formatting is fine.

## Preparation:

1 Age is in numbers which is of little or no use. So, i created column called age groups and group the age into 3 main groups naming: Young, Middle and old aged.

2 Change wordings in sex column from M to Male and F to Female for better readability.

3 Change wordings in ‘Chest Pain Type’ Column column from TA to Typical Anginal Pain, ATA to Atypical Anginal Pain, NAP to Non-Anginal Pain and ASY to Asymptomatic Pain for better readability.

# Exploratory Data Analysis:

For analysis I will use **Tableau** for creating charts to finding insights.

I filtered the entire dataset to show stats for only LVH Patients.

First I imported the data to tableau.

1. Then I created an bar chart that shows number of people suffering from heart disease by age-group.

2. Created a bar chart which shows median cholesterol levels by gender and age groups.

4. Created a pie chart to show composition of people out of total experienced chest pain filtered by age group and gender.

5. To check if there is a correlation between age and Resting BP I created a scatterplot filtered by gender and heart disease.

6. Lastly, I created another scatter plot to check if there is any correlation between age of patients and their max heart rate.


# Key Insights

1. **Age and Heart Disease Prevalence**: A significant 85.6% of heart disease cases are found in the elderly, while 13.3% are in the middle-aged group, and only 1% affect young individuals.

2. **Cholesterol Levels by Gender**: Half of all females have cholesterol levels exceeding 267 mg/dL, while 50% of males have levels over 239 mg/dL.

3. **Pain Type Distribution**: Asymptomatic cases dominate, with 54.3% of patients reporting no pain, followed by 25% experiencing non-anginal pain, 12.2% with atypical anginal pain, and the rest showing typical anginal pain.

4. **Age and Blood Pressure**: There is a positive correlation between age and resting blood pressure, indicating that older patients tend to have higher BP levels.

5. **Age and Max Heart Rate**: A negative correlation exists, as maximum heart rate decreases with age.

   <div class='tableauPlaceholder' id='viz1730795188404' style='position: relative'><noscript><a href='#'><img alt='LVH Patients Health Stats ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;He&#47;HealthStatsofLVHPatients&#47;Dashboard1&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='HealthStatsofLVHPatients&#47;Dashboard1' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;He&#47;HealthStatsofLVHPatients&#47;Dashboard1&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /></object></div>                <script type='text/javascript'>                    var divElement = document.getElementById('viz1730795188404');                    var vizElement = divElement.getElementsByTagName('object')[0];                    if ( divElement.offsetWidth > 800 ) { vizElement.style.width='1400px';vizElement.style.height='827px';} else if ( divElement.offsetWidth > 500 ) { vizElement.style.width='1400px';vizElement.style.height='827px';} else { vizElement.style.width='100%';vizElement.style.height='1977px';}                     var scriptElement = document.createElement('script');                    scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    vizElement.parentNode.insertBefore(scriptElement, vizElement);                </script>

