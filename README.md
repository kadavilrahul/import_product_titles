# Import Product Titles

## Overview
This project is designed to import product titles from various sources and process them for further analysis or integration with other systems. It is tailored for Nion developers to ensure seamless integration with Nion's ecosystem.


## Clone the repository:
   ```bash
   git clone https://github.com/kadavilrahul/import_product_titles.git && cd import_product_titles
   ```

## Setup python 
1. Run the main script to import and process product titles:
   ```bash
   python main.py
   ```
2. To start fresh or reset the data collection:
   ```bash
   python3 -c "from reset_script import reset_script; reset_script()"
   ```

## Setup nodejs
1. Install dependencies:
   ```bash
   npm init -y
   ```
   ```bash
   npm install @woocommerce/woocommerce-rest-api
   ```

2. Run the Node.js script to import and process product titles:
   ```bash
   node main.js
   ```

3. To start fresh, simply delete the generated files:
   ```bash
   rm products.csv current_page.txt
   ```

## Contributing
Contributions are welcome! Please follow these steps:
1. Fork the repository.
2. Create a new branch for your feature or bugfix.
3. Commit your changes with descriptive messages.
4. Submit a pull request.
