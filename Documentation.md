# Details about the LVH or Left Ventricular Hypertrophy Condition:

  LVH, or Left Ventricular Hypertrophy, is a medical condition characterized by the thickening and enlargement of the heart's left ventricular muscle. 
  The left ventricle plays a critical role in the cardiovascular system by pumping oxygen-rich blood into the aorta, the largest artery in the human body. 
  From the aorta, this oxygenated blood is distributed to tissues throughout the body.
  When the walls of the left ventricle thicken, it can hinder the heart's ability to pump blood efficiently into the aorta. 
  This can lead to a variety of complications, including reduced cardiac output and an increased risk of cardiovascular events. 
  Early detection and proper management are crucial in mitigating the risks associated with LVH.

# Data Cleaning & Preparation
  
  ## Data Cleaning:

     1. Check for Duplicate Values:
        A thorough check was performed to identify and remove any duplicate entries. No duplicates were found in the dataset.
     
     2. Blank Values and Formatting:
        The dataset was reviewed for any missing or blank values. None were identified.
     
     3. Formatting of the dataset was assessed, and it was found to be consistent and appropriate for analysis.

   ## Data Preparation:
     
     1. Age Grouping:
        Recognizing that raw age values offer limited analytical insight, an "Age Group" column was created. Age was categorized into three groups for clearer analysis:
        -- Young (18-35 years)
        -- Middle-aged (36-55 years)
        -- Elderly (56+ years)

     2. Improved Readability in Gender Column:
        The "Sex" column values were updated for clarity:
        -- "M" was changed to "Male"
        -- "F" was changed to "Female"

     3. Enhanced Readability in Chest Pain Type Column:
        The "Chest Pain Type" column was updated to use descriptive labels for better understanding:
        -- "TA" was changed to "Typical Anginal Pain"
        -- "ATA" was changed to "Atypical Anginal Pain"
        -- "NAP" was changed to "Non-Anginal Pain"
        -- "ASY" was changed to "Asymptomatic Pain"

# Exploratory Data Analysis (EDA):
  The dataset was analyzed using Tableau to uncover meaningful patterns and insights specific to LVH patients. The steps undertaken are detailed below:
   
 ## Filtering for LVH Patients:
    The entire dataset was filtered to focus exclusively on individuals diagnosed with LVH.

    ### Visualizations Created:
        
      1. Bar Chart:
         Displayed the number of individuals suffering from heart disease categorized by age group (Young, Middle-aged, and Elderly).

      2. Bar Chart for Cholesterol Levels:
         Showed the median cholesterol levels, segmented by gender and age groups, highlighting variations across different demographics.
      
      3. Pie Chart:
         Illustrated the composition of individuals experiencing chest pain, segmented by age group and gender.

      4. Scatter Plot for Resting Blood Pressure:
         Examined the correlation between age and resting blood pressure, filtered by gender and heart disease status.

      5. Scatter Plot for Max Heart Rate:
         Investigated the relationship between patients' age and their maximum heart rate, revealing trends filtered by gender.

These visualizations provided a detailed breakdown of how various factors correlate with LVH and its associated risks.

# Key Insights

  1. Age and Heart Disease Prevalence:
     A significant 85.6% of heart disease cases are found in the elderly, while 13.3% are in the middle-aged group, and only 1% affect young individuals.

  2. Cholesterol Levels by Gender:
     Half of all females have cholesterol levels exceeding 267 mg/dL, while 50% of males have levels over 239 mg/dL.

  3. Pain Type Distribution:
     Asymptomatic cases dominate, with 54.3% of patients reporting no pain, followed by 25% experiencing non-anginal pain, 12.2% with atypical anginal pain, and the rest showing typical anginal pain.
 
  4. Age and Blood Pressure:
     There is a positive correlation between age and resting blood pressure, indicating that older patients tend to have higher BP levels.

  5. Age and Max Heart Rate:
     A negative correlation exists, as maximum heart rate decreases with age.
