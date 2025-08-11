📌 Features

    Interactive UI to input lifestyle habits:

        Monthly electricity usage (kWh)

        Weekly kilometers driven

        Flights taken per year

        Monthly waste generation

        Diet type (Vegan, Vegetarian, Omnivore)

    Machine learning model (Random Forest Regressor) trained on synthetic data with >100 data points

    On-screen results showing the estimated monthly carbon footprint (kg CO₂ equivalent)

    Synthetic dataset included as an Excel file for reproducibility

    Expandable data preview inside the app

📂 Project Structure

Carbon-Footprint-Estimator-App/
│
├── carbon_footprint_app.py          # Streamlit application code
├── synthetic_carbon_footprint_dataset.xlsx  # Generated synthetic dataset
└── README.md                        # Project documentation

🛠 Installation & Setup

    Clone this repository:

git clone https://github.com/your-username/Carbon-Footprint-Estimator-App.git
cd Carbon-Footprint-Estimator-App

Install dependencies:

pip install streamlit scikit-learn pandas numpy openpyxl

Run the application:

    streamlit run carbon_footprint_app.py

    Open the provided URL (default: http://localhost:8501) in your browser.

📊 Dataset

The synthetic dataset contains 200 samples with the following columns:
Column	Description
monthly_energy_kwh	Monthly electricity consumption in kilowatt-hours
weekly_km_driven	Weekly car travel distance in kilometers
flights_per_year	Number of flights taken in a year
diet_type	Type of diet (Vegan, Vegetarian, Omnivore)
monthly_waste_kg	Monthly waste produced in kilograms
diet_factor	Numeric factor representing diet-related carbon impact
carbon_footprint	Calculated monthly carbon footprint (kg CO₂ equivalent)

Download Dataset:
📂 synthetic_carbon_footprint_dataset.xlsx
🧮 Model

    Algorithm: Random Forest Regressor

    Features: Energy use, transportation habits, waste generation, diet factor

    Target: Monthly carbon footprint

    Performance Metric: Mean Squared Error (MSE) shown in-app

📌 Notes

    This project uses synthetic data for demonstration and is not intended for real-world carbon tracking.

    The synthetic carbon footprint formula is illustrative and does not reflect precise environmental science.
    Author
    Name
    Github

📜 License

This project is licensed under the MIT License.
