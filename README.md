# Store-Sales-Analysis-using-python

This Python script performs an analysis on store sales data using various data manipulation and visualization techniques. The key functionalities include:

### 1. Data Setup

- **Data Structure:** The data is organized into a Pandas DataFrame with information about different products, including product names, wholesale prices, retail prices, and sales quantities.

### 2. Analysis and Calculations

- **Total Profit Calculation:** The script calculates the total profit for each product using the formula: `net_revenue_per_product = (retail_price - wholesale_price) * sales`.

- **Total Revenue:** Calculates the total net revenue received from all sales.

- **Products with High Profit Margin:** Identifies products where the retail price is more than twice the wholesale price.

- **Revenue by Category:** Determines how much revenue the store made from different categories, such as food, computers, and books.

- **Discount Calculation:** Simulates a 30% discount negotiation on the wholesale price of goods, resulting in new net revenue.

- **Tax Impact:** Calculates the net income under different sales tax rates (15%, 20%, and 25%).

### 3. Visualizations

- **Bar Chart:** Displays a bar chart showing the net revenue per product.

- **Violin Plot:** Visualizes the distribution of retail prices for each product using a violin plot.

### 4. Code Organization

- **Modular Structure:** The code is organized into functions for better readability and maintainability.

- **Tabulated Results:** Uses the `tabulate` library to display tabulated results for better readability in the console.

### 5. Execution

- **User Interaction:** The script interacts with the user by accepting input for encryption or decryption and shift values. The user can also stop the program by entering the 'stop' command.

### 6. Dependencies

- **Libraries Used:** The script utilizes Pandas for data manipulation, Matplotlib for plotting, Seaborn for additional visualization (violin plot), and Tabulate for tabulated result display.

### Author
- HELDANA NATNAEL AMBAW
