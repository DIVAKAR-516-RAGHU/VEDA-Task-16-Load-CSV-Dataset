# VEDA AI & ML Internship – Task 16

## Load a CSV Dataset

### Objective

Load a CSV dataset using Pandas, display the first and last records, and verify that the dataset has been loaded correctly.

### Dataset

**Dataset:** Iris Dataset  
**Source:** UCI Machine Learning Repository  
**Dataset Link:** https://archive.ics.uci.edu/dataset/53/iris

The Iris dataset contains **150 instances**, **4 numerical features**, and **3 classes** of Iris flowers.

### Technologies Used

- Python
- Pandas
- Jupyter Notebook

### Implementation

The Iris dataset was loaded directly from the UCI Machine Learning Repository using Pandas.

```python
import pandas as pd

url = "https://archive.ics.uci.edu/ml/machine-learning-databases/iris/iris.data"

df = pd.read_csv(
    url,
    header=None,
    names=[
        "SepalLengthCm",
        "SepalWidthCm",
        "PetalLengthCm",
        "PetalWidthCm",
        "Species"
    ]
)
````

### Dataset Verification

The following Pandas operations were used:

```python
df.head()
df.tail()
df.shape
df.columns
df.info()
df.isnull().sum()
```

### Results

* **Number of records:** 150
* **Number of columns:** 5
* **Numerical features:** 4
* **Target/Class column:** Species
* **Missing values:** 0

### Conclusion

The Iris CSV dataset was successfully loaded using Pandas. The first and last records were displayed, and the dataset was verified to contain 150 records and 5 columns with no missing values.

### Files

* `Task_16_Load_CSV_Dataset.ipynb` – Jupyter Notebook containing the complete implementation and results.

```

Available next action: :contentReference[oaicite:0]{index=0}
```
