# 🛒 Price Comparison Tool (C++ - Console-Based)

## 📌 Introduction
The **Price Comparison Tool** is a simple yet effective console-based C++ application designed to help users find the best prices for products across different online stores. It provides a clean interface and leverages efficient data structures to help users compare prices and make smart purchasing decisions — all without visiting multiple websites.

## 🎯 Objective
The primary goals of this project are to:
- 🔍 Compare prices for similar products from different stores.
- 💰 View the cheapest products based on their prices.

This tool helps users **save time** and **make informed decisions** when shopping online.

## ⚙️ Functionality

### 1. Add Product
- Users can input a product with its name, price, and store.
- Products are stored dynamically and organized by store using a hash map.

### 2. Display Cheapest Products
- A priority queue (min-heap) is used to track the cheapest products.
- Displays top **K cheapest products** for quick comparison.

### 3. Product Management
- Efficient internal management using:
  - **Dynamic arrays** for flexible product storage.
  - **Hash maps** for store-based categorization.
  - **Min-heaps** for rapid access to lowest-priced items.

## 🧰 Technology Stack

- **Language:** C++  
- **Interface:** Console-based  
- **Data Structures Used:**
  - 🔢 Dynamic Array: For scalable product storage.
  - 🧭 Hash Map (`unordered_map`): For store-wise product organization.
  - 🔽 Priority Queue (Min-Heap): For retrieving cheapest products.


