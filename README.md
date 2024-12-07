# Soil Monitoring System 🌱💧

A smart soil monitoring system designed to optimize irrigation schedules, reduce water consumption, and improve agricultural productivity. This project integrates sensor networks, machine learning, and a real-time dashboard to provide actionable insights for farmers.

---

## Features 🌟

- **Real-Time Monitoring:** Tracks soil moisture and temperature across multiple fields.
- **Sensor Network:** Arduino-based system using DHT11/DHT22 sensors for accurate data collection.
- **Machine Learning:** Predicts irrigation needs using regression and classification models.
- **Web Dashboard:** Visualizes real-time and historical data on soil conditions.
- **Resource Optimization:** Reduces water usage by up to 30% with smart scheduling.

---

## Technologies Used 🛠️

- **Arduino:** Microcontroller for sensor integration and data collection.
- **Python:** For data processing and machine learning.
- **Flask:** Backend framework for the web dashboard.
- **JavaScript & HTML:** For frontend development.
- **Matplotlib & Seaborn:** Data visualization tools.
- **SQL:** For storing and managing soil data.
- **DHT11/DHT22 Sensors:** For measuring soil moisture and temperature.

---

## Installation ⚙️

1. Clone the repository:
   ```bash
   git clone https://github.com/RobSaidov/SoilMonitoringSystem.git
   cd SoilMonitoringSystem
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Set up the Arduino sensors:
   - Connect the DHT11/DHT22 sensors to your Arduino.
   - Upload the `arduino_code.ino` file from the `arduino/` directory to your Arduino board.

4. Configure the database:
   - Import the `soil_data.sql` file into your SQL database.
   - Update the database connection details in `config.py`.

5. Start the web application:
   ```bash
   python app.py
   ```

6. Access the dashboard in your browser at `http://localhost:5000`.

---

## Usage 🚀

1. **Connect Sensors:**
   - Ensure that the Arduino board with connected sensors is running and collecting data.

2. **Monitor Conditions:**
   - View real-time soil conditions on the web dashboard.

3. **Analyze Data:**
   - Use historical trends and machine learning predictions to make informed irrigation decisions.

4. **Optimize Resources:**
   - Leverage system recommendations to reduce water consumption and improve crop health.

---

## File Structure 📁

```
SoilMonitoringSystem/
│
├── arduino/                   # Arduino code for sensor network
│   └── arduino_code.ino
├── static/                    # Static assets for the dashboard (CSS, JS)
├── templates/                 # HTML templates for Flask
├── data/                      # Sample datasets for training/testing
├── models/                    # Machine learning models
│   └── irrigation_predictor.py
├── scripts/
│   ├── data_processing.py     # Processes raw sensor data
│   ├── visualize_data.py      # Data visualization scripts
│   └── machine_learning.py    # Machine learning algorithms
├── config.py                  # Configuration for database and application
├── requirements.txt           # Python dependencies
├── app.py                     # Main Flask application
└── README.md                  # Project documentation
```

---

## Example Output 📊

- **Real-Time Dashboard:**  
![Dashboard Example](./assets/dashboard_example.png)

- **Soil Data Visualization:**  
![Visualization Example](./assets/visualization_example.png)

- **Irrigation Prediction:**  
![Prediction Example](./assets/prediction_example.png)

---

## Contributing 🤝

Contributions are welcome! To contribute:
1. Fork the repository.
2. Create a new branch: `git checkout -b feature-name`.
3. Commit your changes: `git commit -m 'Add some feature'`.
4. Push to the branch: `git push origin feature-name`.
5. Open a pull request.

---

## Future Improvements 🔮

- Expand support for additional sensors (e.g., pH, humidity).
- Integrate satellite imagery for advanced analytics.
- Develop a mobile app for field-level monitoring.
- Add predictive alerts for extreme conditions.

---

## License 📜

This project is licensed under the MIT License. See the [LICENSE](./LICENSE) file for details.

---

## Contact 📬

Developed by **Rob Saidov**.  
Feel free to reach out for questions or collaboration opportunities!

- **Email:** [robsaidov@gmail.com](mailto:robsaidov@gmail.com)
- **LinkedIn:** [linkedin.com/in/robsaidov](https://linkedin.com/in/robsaidov)
