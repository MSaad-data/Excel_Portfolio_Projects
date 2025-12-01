Training_and_development_dataset

## Dataset used
 <a href="https://github.com/MSaad-data/Excel_Portfolio_Projects/blob/main/Training_and_development_dataset.xlsx">Dataset view</a>

This dataset had around 3000 rows of employee training records. I used it to practice  Excel skills including math operations, comparison operators, and cell referencing. I calculated total cost with tax, created discount columns, and used absolute and mixed referencing to apply formulas across the dataset. I also created flags for long trainings, low-cost trainings, and passed vs not passed outcomes.

## The dataset has these main columns:
Employee ID
Training Date
Training Program Name
Training Type
Training Outcome
Location
Trainer
Training Duration (Days)
Training Cost 
I added new columns to help with the analysis.           
## New Columns I Created
Total Cost With Tax
Long Training
Low-Cost Training
Passed Training
Discount
Cost After Discount
Total Trainings by Trainer

## Formulas I Used               These are the formulas I used in the project:

### Low-Cost Training Check
=IF(J2 < 500, "Low", "Not Low")

### Passed Training Check
=IF(J2 = "Passed", 1, 0)

### Final Cost After Discount
=Cost - (Cost * Discount%)

### Total Trainings By Trainer
=COUNTIF($G:$G, G2)

## Visual 1: Low-Cost vs Not Low-Cost Trainings
I made a bar chart to see how many trainings cost less than $550.
Low-cost trainings: 1,313 (about 44%)
Not low-cost trainings: 1,687 (about 56%)
The company spends more on higher-cost trainings.
Low-cost trainings are still a big part of the total, but not the majority.
<img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/fceb7bd5-9870-49af-a267-8daf9f89e6dc" />

## Visual 2: Training Outcomes
I made a bar chart to count each training result.
Completed: 770
Passed: 739
Failed: 716
Incomplete: 775
The outcomes are almost equal.
Many people are completing or passing, but many are also failing or not finishing.
This shows that the training process may need review.
<img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/51b09f65-cf95-4d3a-9138-033fa06a1d71" />


## Visual 3: Total Cost by Training Outcome
I made a pie chart to see how money was spent for each outcome.
Total spending was about $1.67 million.
Completed: $430k (26%)
Passed: $415k (25%)
Failed: $399k (24%)
Incomplete: $430k (26%)
Money is spread almost evenly across all outcomes.
About half of the money went to failed or incomplete trainings.
This shows that the company is spending a lot but not always getting good results.
<img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/662de43e-37a3-49ad-9f4d-cae9dbfefd04" />
