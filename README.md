**(Look Inside motorcycle_vs_car.ipynb)**

1.Created a tiny dataset with Pandas (engine_cc, weight_kg, label).

2.Saved dataset as CSV (tiny_vehicles.csv).

3.Visualized dataset with matplotlib scatter plot.

4.Observed clear separation between motorcycles and cars.



<img width="914" height="615" alt="image" src="https://github.com/user-attachments/assets/bd70ea1a-6d21-4250-9874-d216a5e4b066" />

## Step 2 — Train/Test Split

- Imported `train_test_split` from scikit-learn.
- Defined **features (X)** = `engine_cc`, `weight_kg`.
- Defined **labels (y)** = `label` (motorcycle or car).
- Split dataset into:
  - 70% training set
  - 30% testing set
- Used `stratify=y` to keep class balance.
- Confirmed split by printing training and testing sets.
<img width="1152" height="549" alt="image" src="https://github.com/user-attachments/assets/bd885e94-60c8-420e-98e5-8c59425c5eac" />
