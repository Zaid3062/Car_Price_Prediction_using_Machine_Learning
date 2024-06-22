###Car Price Prediction Using Machine Learning 

### Data Preparation and Initial Exploration

1. **Loading the Dataset**:
   - The dataset containing various attributes of cars was loaded.

2. **Initial Data Inspection**:
   - Displayed the first few rows of the dataset.
   - Checked the shape of the dataset to understand the number of rows and columns.
   - Described the dataset to get summary statistics for each column.
   - Checked the data types of each column and ensured there were no missing values.

3. **Data Cleaning**:
   - Extracted and corrected the `CompanyName` from the `CarName` column.
   - Standardized the `CompanyName` by converting all names to lowercase and correcting misspellings.

4. **Exploratory Data Analysis (EDA)**:
   - **Price Distribution**:
     - Plotted the distribution and box plot of car prices to understand their spread and distribution.
     - Provided descriptive statistics for the `price` column, including percentiles.
   - **Categorical Features Analysis**:
     - Plotted histograms and box plots for `CompanyName`, `fueltype`, and `carbody` to see their distributions and relationship with the price.
   - **Symboling**:
     - Plotted the distribution of the `symboling` attribute and its relationship with the price.
   - **Engine Type**:
     - Analyzed the distribution and average price for different `enginetype` values.
   - **Company Name vs. Price**:
     - Analyzed the average price for different car companies.
   - **Fuel Type and Car Type vs. Price**:
     - Analyzed how fuel types and car types impact the average car price.
   - **Other Attributes**:
     - Plotted distributions and box plots for `doornumber` and `aspiration`.

### Additional Analysis

5. **Feature Relationships**:
   - Plotted scatter plots for various continuous features like `carlength`, `carwidth`, `curbweight`, etc., against `price` to explore their relationships.
   - Plotted pair plots to visualize relationships between multiple features and the price.

6. **Derived Features**:
   - Calculated `fueleconomy` using city and highway mileage.
   - Binned car companies into `Budget`, `Medium`, and `Highend` categories based on the average price.

7. **Visualizations**:
   - Created scatter plots to explore the relationship between `fueleconomy` and `price`, colored by `drivewheel`.
   - Plotted bar charts to show the average price for different combinations of `fuelsystem`, `drivewheel`, and `carsrange`.

8. **Feature Encoding**:
   - Applied one-hot encoding to categorical variables to prepare the dataset for machine learning algorithms.

### Conclusion

The analysis provided insights into the following aspects:
- Distribution and spread of car prices.
- Influence of categorical features like `CompanyName`, `fueltype`, `carbody`, and `enginetype` on car prices.
- Relationships between continuous features and car prices.
- The impact of fuel economy on car prices.
- Prepared the dataset by encoding categorical features, making it ready for further modeling.

This exploratory data analysis helps in understanding the key factors affecting car prices and prepares the data for predictive modeling or more in-depth statistical analysis.
