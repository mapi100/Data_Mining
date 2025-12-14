# Coffee Pour Over Origin Classification

This project aims to predict the origin of coffee beans (Sprout or Rwanda)
based on pour-over brewing data collected from a smart scale.

## Files
- `coffee_combined_data.npz`: Labeled training dataset.
- `test_data.npz`: Unlabeled test samples (4 curves).
- `crafted_features.csv`: Human-crafted features extracted from the brewing curves.
- `coffee_project.ipynb`: Google Colab notebook containing all code (Task 1 and Task 2).

## How to Run
1. Open the Google Colab notebook `coffee_project.ipynb`.
2. Upload the files `coffee_combined_data.npz` and `test_data.npz` to the Colab environment.
3. Run all cells sequentially from top to bottom.
4. The notebook will:
   - Visualize the data
   - Extract human-crafted features
   - Train linear and stacked logistic regression models
   - Perform cross-validation
   - Predict the labels of the unlabeled samples
   - Export `crafted_features.csv`

## Output
- Classification accuracy for different models
- Predicted labels for the four unlabeled coffee samples
- CSV file containing the extracted human-crafted features
