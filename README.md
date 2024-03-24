# Motor Vehicle Collisions Dashboard for New York City

This repository contains code for a Streamlit application that serves as a dashboard for analyzing motor vehicle collisions in New York City. The application utilizes several data visualization libraries such as Streamlit, Pandas, NumPy, Pydeck, and Plotly Express.

## Installation

To run the application locally, follow these steps:

1. Clone this repository to your local machine.
                                                                                                                                                                          
    ```bash
    git clone https://github.com/Antisource/MVC.git
    ```
2. Install the required dependencies using pip:

    ```bash
    pip install streamlit pandas numpy pydeck plotly
    ```

3. Navigate to the directory containing the code.
4. Run the Streamlit application:

    ```bash
    streamlit run app.py
    ```

## Data Source

The data used in this application is sourced from the [Motor Vehicle Collisions - Crashes dataset](https://data.cityofnewyork.us/Public-Safety/Motor-Vehicle-Collisions-Crashes/h9gi-nx95) provided by the City of New York. The dataset is included in the repository as `Motor_Vehicle_Collisions_-_Crashes.csv`.

## Functionality

The dashboard provides the following functionality:

1. **Where are the most people injured in NYC?**
   - Use the slider to select the number of persons injured in vehicle collisions.
   - The map will display locations where the number of injured persons meets or exceeds the selected threshold.

2. **How many collisions occur during a given time of day?**
   - Use the slider to select the hour of the day.
   - Displays a heatmap of collisions occurring during the selected hour.

3. **Breakdown by minute between selected hours**
   - Provides a breakdown of collisions by minute within the selected hour range.

4. **Top 5 dangerous streets by affected type**
   - Select a type of affected people (Pedestrians, Cyclists, or Motorists) from the dropdown menu.
   - Displays the top 5 dangerous streets based on the selected affected type.

5. **Show Raw Data**
   - Checkbox option to display the raw data used for analysis.

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, feel free to open an issue or submit a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgements

- Data Source: [NYC OpenData](https://data.cityofnewyork.us/Public-Safety/Motor-Vehicle-Collisions-Crashes/h9gi-nx95)
- Built with [Streamlit](https://streamlit.io/)
- Visualization with [Pydeck](https://deckgl.readthedocs.io/en/latest/) and [Plotly Express](https://plotly.com/python/plotly-express/)
