# master-thesis-codebase
Codebase for master thesis "Evaluating Marine Vessel Collision Risks Using Trajectory Prediction Regions And Clusters"

### 1. `data_cleaning.ipynb`
- Cleans the data files for each day.
- Joins the cleaned files into a consolidated dataset.
- Prepares the dataset for sequencing and modeling.

### 2. `model_check.ipynb`
- Compares various model variations.
- Evaluates models using metrics such as Mean Squared Error (MSE) and Mean Absolute Haversine Error (MAHE).
- Identifies the best-performing model for use in the `modelling.ipynb` script.

### 3. `modelling.ipynb`
- Performs sequencing and modeling of trajectories.
- Predicts future trajectories and generates prediction regions.
- Uses these regions for collision prediction.
- Includes results and analyses.

### 4. `modelling for real collision.ipynb`
- Extends the `modelling.ipynb` process to real collision data.
- Sequences real collision data and uses the sequences for trajectory prediction.
- Detects potential collisions based on trajectory predictions.
