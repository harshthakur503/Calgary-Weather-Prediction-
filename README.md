# Calgary Weather Prediction Dash App

**Overview:**
This project involves building a Dash web application for predicting weather conditions in Calgary. The app fetches real-time weather data from an external API, stores it in a SQL database, makes predictions using a machine learning model, and displays the predictions in a user-friendly interface.

**Tech Stack:**
- **Python:** Programming language used for backend development.
- **Dash:** Python framework for building web applications.
- **Pandas:** Data manipulation and analysis library.
- **PyODBC:** Python library for connecting to ODBC-compliant databases.
- **SQLAlchemy:** SQL toolkit and Object-Relational Mapping (ORM) library for Python.
- **Requests:** HTTP library for making requests to external APIs.

**Key Components:**
1. **Data Fetching and Storage:**
   - Utilizes the `fetch_and_store_data` function to retrieve weather data from the Open-Meteo API.
   - Parses the API response and stores the data in an Azure SQL Database.

2. **Data Processing and Prediction:**
   - Defines the `fetch_data_and_make_predictions` function to fetch recent weather data from the SQL database and make temperature predictions.
   - Uses a pre-trained machine learning model to generate predictions based on weather parameters.

3. **Dash App Layout:**
   - Creates a Dash application layout with a title, header, and content area.
   - Includes a button to trigger the generation of weather predictions.

4. **Dash Callbacks:**
   - Implements a Dash callback to update the predictions table when the "Generate Weather Predictions" button is clicked.
   - Displays the predicted temperature, weather code, and weather condition in a Dash DataTable.

**Installation and Setup:**
1. Install the required Python libraries: `dash`, `pandas`, `pyodbc`, `sqlalchemy`, `requests`.
2. Ensure access to the Azure SQL Database and configure the connection string accordingly.
3. Run the Dash app using `python app.py`.

**Usage:**
1. Open the Dash app in a web browser.
2. Click the "Generate Weather Predictions" button to fetch recent weather data and display predictions.
3. View the predicted temperature, weather code, and weather condition in the table.

**Contributors:**
- [Your Name]
- [Additional Contributors]

**License:**
This project is licensed under the [MIT License](https://opensource.org/licenses/MIT). See the LICENSE file for more details.

**Acknowledgments:**
- Thanks to Open-Meteo for providing weather data via their API.
- Special thanks to [Your Supervisor/Mentor] for guidance and support.

**References:**
- Dash Documentation: https://dash.plotly.com/
- Open-Meteo API Documentation: [Link to API Documentation]
- SQLAlchemy Documentation: https://www.sqlalchemy.org/
- Microsoft Azure Documentation: https://docs.microsoft.com/en-us/azure/

**Note:**
Ensure that appr
