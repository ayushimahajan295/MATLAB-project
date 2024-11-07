# MATLAB-project
Implementation of Traffic Data Analysis for Modeling and Prediction of Traffic Scenarios in MATLAB

**Pre requisites:**

Install the Deep Learning and Statistics and Machine Learning Toolboxes in MATLAB by following these steps:

1. **Open MATLAB and Access Add-Ons:**
   - Go to **Home > Add-Ons > Get Add-Ons**.

2. **Search for Toolboxes:**
   - In the Add-On Explorer, search for **Deep Learning Toolbox** and **Statistics and Machine Learning Toolbox**.

3. **Install Toolboxes:**
   - Click **Add** or **Install** for each toolbox. Sign in with your MathWorks account if prompted.

4. **Verify Installation:**
   - In the **Command Window**, type:
     ```matlab
     ver
     ```
   - Ensure the toolboxes are listed to confirm successful installation.

**Running Model:**
1. **Preprocess data:**
    - Run dact_data_processing.mlx to pre process the dataset: DACT Easy-Dataset.csv. It will create a new file with processed data and visualisation. (Processed_Traffic_Trajectory_Dataset.csv is an already preprocessed file for the dataset)

2. **Use the Implementation code to perform Analysis on the traffic data:**
    - Run implementation.mlx to preform analysis on the preprocessed dataset: Processed_Traffic_Trajectory_Dataset.csv. It will perform analysis on the pre processed file.

2. **Code Check:**
    - Provide correct file paths for the datasets in the code depending on where they are stored on your local device.