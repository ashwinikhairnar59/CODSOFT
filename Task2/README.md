# Movie Rating Prediction Project

## Features in the Dataset:
- **Name**: The name of the movie.
- **Year**: The year of release (may need cleaning as it contains extra characters).
- **Duration**: Movie duration (in minutes, but includes "min"; requires cleaning).
- **Genre**: Categories of the movie (e.g., Drama, Comedy).
- **Rating**: The target variable, representing the movie rating.
- **Votes**: Number of votes for the rating (numerical).
- **Director**: The director's name (categorical).
- **Actor 1, Actor 2, Actor 3**: Names of the main actors (categorical).

---

## Next Steps:

### Clean the Dataset:
1. **Remove extra characters**:
   - Brackets in `Year`.
   - "min" in `Duration`.
2. **Handle missing values**:
   - Fill missing values in `Rating` and `Votes`.

### Prepare Data for Modeling:
1. **Encode categorical features**:
   - Encode `Genre`, `Director`, and `Actor 1` into machine-readable format.
2. **Convert `Duration` to numerical**.

### Build a Regression Model:
- Use regression techniques like **Linear Regression** or **Random Forest**.

---

## Observations from the Data Summary:

### Missing Values:
- Significant missing values exist in:
  - `Rating`
  - `Votes`
  - `Duration`
  - Actor-related columns.

### Data Types:
- `Votes` is stored as an object but should be numerical.
- Other columns (`Year`, `Duration`, `Rating`, `Votes`) require imputation for missing values.

---

## Cleaning and Preparing Data:

### Convert `Votes` to Numeric:
- Remove any non-numeric characters and convert to float.

### Handle Missing Values:
1. Use strategies like **mean/median imputation** for numerical columns:
   - `Duration`
   - `Rating`
   - `Votes`
2. Use mode or `"Unknown"` for categorical features:
   - `Director`
   - `Genre`
   - Actor-related columns.

### Prepare for Encoding:
- Convert categorical variables (`Genre`, `Director`, `Actor 1`) into a machine-readable format using:
  - **One-Hot Encoding** or **Label Encoding**.
