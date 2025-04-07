# Task 1 – Data Cleaning and Preprocessing

## Dataset
**Medical Appointment No Shows**  
- Source: [Kaggle Dataset](https://www.kaggle.com/datasets/joniarroba/noshowappointments)

## What I Did
- Loaded the dataset using Pandas
- Cleaned column names (lowercase, underscores)
- Converted `no_show` to binary (0 = show, 1 = no-show)
- Converted date columns (`scheduledday`, `appointmentday`) to datetime
- Removed duplicate rows
- Dropped rows with invalid age entries (age < 0)
- Added new column: `appointment_weekday`

## Files Included
- `KaggleV2-May-2016`: dataset
- `Medical_Appointment_No_Shows.ipynb`: Python code used
- `README.md`: This documentation

## Tools Used
- Python
- Pandas
- Google Colab

## Author
- Sai Kiranmai Manthripragada
