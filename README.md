# Invoice Generator

A Python-based application to generate professional invoices effortlessly. This tool is ideal for businesses to streamline invoice creation with customer and product details sourced from CSV files.

# Features

1. Customer Selection

	•	Select a customer from a pre-defined list in customers.csv. <br>
	•	Automatically populates customer details like name, address, mobile number, and email.

2. Product Selection

	•	Choose one or more products from products.csv. <br>
	•	Specify quantities for each selected product.

3. Dynamic Invoice Generation

	•	Automatically calculates line totals and overall total. <br>
	•	Populates a PDF invoice with: <br>
	•	Company details <br>
	•	Customer details <br>
	•	A table of selected products with descriptions, quantities, unit prices, and totals.

4. PDF Export

	•	Generates a downloadable PDF invoice with a single click. <br>
	•	Preview the invoice directly within the app. 

5. Interactive Sidebar

	•	Select customers, products, and quantities conveniently. <br>
	•	Includes options to input custom quantities for each product.

# Requirements

	•	Python 3.x
	•	Required Python libraries:
	•	streamlit
	•	pandas
	•	fpdf
	•	Datasets:
	•	customers.csv: Contains customer details with columns:
customer_id, customer_name, address, mobile, email.
	•	products.csv: Contains product details with columns:
product_id, product_name, description, price.
	•	Company Logo:
Place a file named logo.png in the project directory to include your logo in the invoice.

# Installation

	1.	Clone this repository:

git clone https://github.com/yourusername/invoice-generator.git
cd invoice-generator


	

	2.	Ensure the following files are present in the project directory:
 
	•	customers.csv
	•	products.csv
	•	logo.png

# How to Run

	1.	Start the Streamlit app by running:

streamlit run invoice.py


	2.	Open the application in your browser (usually at http://localhost:8501).
	3.	Use the sidebar to:
	•	Select a customer.
	•	Choose products and specify their quantities.
	4.	Click “Generate Invoice” to create a PDF.
	•	Download the Invoice: Save the generated PDF.
	•	Preview the Invoice: View the invoice directly in the app.

# Outputs

The generated invoice includes:
	•	Company details: Name, address, contact information.
	•	Customer details: Name, address, mobile number, email.
	•	Invoice table: Product name, description, quantity, unit price, and line total.
	•	Grand total: Sum of all line totals.
