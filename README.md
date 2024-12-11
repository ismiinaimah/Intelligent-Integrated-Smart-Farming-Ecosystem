# Intelligent Integrated Smart Farming Ecosystem

## Project Overview
This project demonstrates an **Intelligent Integrated Smart Farming Ecosystem** that utilizes IoT, AI, and blockchain technologies to optimize agricultural processes from planting to product distribution. The system integrates various enterprises and allows monitoring, transaction management, and purchase history tracking via a user-friendly interface built using **Gradio**.

## Key Features
1. **Sensor Monitoring**:
   - Monitors soil moisture, temperature, and humidity.
   - Recommends the optimal quantities of seeds, fertilizers, and pesticides based on sensor data.

2. **Transaction Management**:
   - Allows users to initiate transactions for agricultural products.
   - Updates the stock levels of products after each transaction.
   - Logs transaction details, including the product type, quantity, and seller.

3. **Purchase History**:
   - Displays a detailed log of past transactions.
   - Provides an easy-to-refresh interface for viewing real-time updates.

## System Components
### Enterprises Involved
- **PT AgriTech Solutions**: Provides IoT devices like weather and soil sensors.
- **PT Seed Innovators Indonesia**: Supplies high-quality seeds.
- **PT NutriGrow Fertilizers**: Distributes fertilizers and pesticides.
- **PT AgriMarket Network**: Manages the marketing and distribution of farm products.

### Core Functionalities
1. **Sensor Monitoring**:
   - Inputs: Soil moisture (%), Temperature (°C), Humidity (%).
   - Outputs: Recommended quantities of seeds, fertilizers, and pesticides.

2. **Transaction Management**:
   - Inputs: Product type (Seed, Fertilizer, Pesticide), Quantity.
   - Outputs: Transaction status, updated stock levels.

3. **Purchase History**:
   - Displays the transaction history, including the product type, quantity, and seller.

## How to Run the Project
### Prerequisites
- Python 3.7+
- Libraries: `gradio`, `pandas`

### Installation
1. Clone the repository.
2. Install the required libraries:
   ```bash
   pip install gradio pandas
   ```

3. Run the notebook:
   ```bash
   Smart_Farming.ipynb
   ```

### User Interface
1. **Sensor Monitoring Tab**:
   - Use sliders to input soil moisture, temperature, and humidity.
   - Click `Submit` to view recommendations for seeds, fertilizers, and pesticides.

2. **Transaction Management Tab**:
   - Select the product type and enter the quantity.
   - Click `Submit` to perform the transaction and view updated stock levels.

3. **Purchase History Tab**:
   - View the log of all transactions.
   - Use the `Refresh` button to update the history.

## Code Structure
- **`sensor_monitoring` Function**:
  - Processes soil conditions to recommend optimal product quantities.

- **`handle_transaction` Function**:
  - Manages stock updates and logs transaction details.

- **`transaction_tab` and `history_tab` Functions**:
  - Handle user interaction for transactions and history tracking.

- **Gradio Interface**:
  - Provides a clean and interactive UI with tabs for different functionalities.

## Sample Outputs
### Sensor Monitoring
| Seed (kg) | Fertilizer (kg) | Pesticide (kg) |
|-----------|-----------------|----------------|
| 50        | 20              | 10             |

### Updated Stock After Transaction
| Product    | Stock (kg) |
|------------|------------|
| Seed       | 950        |
| Fertilizer | 470        |
| Pesticide  | 190        |

### Purchase History
| Product Type | Quantity | Seller                        |
|--------------|----------|-------------------------------|
| Seed         | 50       | PT Seed Innovators Indonesia |
| Fertilizer   | 30       | PT NutriGrow Fertilizers     |

## Future Enhancements
- Add blockchain-based transaction validation for greater transparency.
- Implement AI-driven predictive analytics for better recommendations.
- Expand the database to include more products and companies.

## Contributors
- **Ismi Nurul Na'imah**

