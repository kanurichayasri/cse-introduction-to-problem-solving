# cse-introduction-to-problem-solving
APMC Mandi Billing SystemA Python-based command-line application designed to digitize the billing process in Agricultural Produce Market Committees (APMC).
This tool automates the generation of sales receipts for farmers, calculating totals, taxes, and net payable amounts while ensuring accurate record-keeping.
 Overview
In many local mandis, billing is still manual, leading to calculation errors and readable issues. This project solves that problem by providing a digital point-of-sale system that:
Captures details for Farmers and Traders.
Handles multiple crop entries in a single transaction.
Automatically calculates the Mandi Tax (2%).
Generates a formatted receipt with a timestamp.
Saves a permanent record to a text file.
Features
Dynamic Cart System: Add an unlimited number of crops (Wheat, Potato, etc.) to a single bill.
Automated Tax Calculation: Automatically deducts the standard 2% market fee from the total.
Unicode Support: Fully supports special characters and emojis (e.g., "Ramesh 🌾") using UTF-8 encoding.
Input Validation: Prevents errors by validating weights and prices (must be positive numbers).
File Persistence: Automatically saves every generated bill to farmer_bill.txt for record-keeping.
