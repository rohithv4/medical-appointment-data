# medical-appointment-data
this task involved cleaning and preprocessing a raw patient dataset using python(pandas) . the original data set may contain missing values and potential duplicates and inconsistent formatting
📂 Dataset Used
File Name: KaggleV2-May-2016.csv
Source: sample patient
![day1 excel](https://github.com/user-attachments/assets/b47544ab-0569-4f63-928c-85955a15f256)
 Data from Kaggle

🧪 Steps Performed
Loaded the Dataset
Handled encoding issues using ISO-8859-1.

Inspected Data

Checked shape, missing values, and duplicates.
Cleaned Data

Removed duplicates using drop_duplicates()
Filled missing numeric values with column mean
Filled missing categorical values with column mode
Converted all string columns to lowercase and removed extra whitespace
Formatted Date Columns

Converted ORDERDATE column to datetime format using pd.to_datetime()
Exported Clean Dataset

Saved the cleaned dataset as patient appointment sample.csv
![day1 load data](https://github.com/user-attachments/assets/863677fa-775f-4312-9f07-b73e3f4c5d9f)
![day1 missing and duplicates](https://github.com/user-attachments/assets/9ffc45ff-cd49-44e1-b545-011ac8cd0d80)
![day1 convert,rename,fix ,save](https://github.com/user-attachments/assets/8a5ae407-3b95-49e5-9848-85eb2256c9ca)
