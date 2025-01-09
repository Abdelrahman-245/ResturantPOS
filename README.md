# Restaurant POS System  

This is a simple Restaurant Point of Sale (POS) system built in Python. It allows users to manage a restaurant’s menu, create and track orders, and calculate totals. The system uses JSON files to store menu items and orders, ensuring data is persistent across sessions.  

## Features  
- **Menu Management**:  
  - Add new menu items with prices.  
  - View all available menu items.  

- **Order Management**:  
  - Create new orders and assign them to tables.  
  - Add items to orders and calculate totals.  
  - View all orders with details such as table number, items, total price, and timestamps.  

- **Data Persistence**:  
  - All menu items and orders are saved in `menu.json` and `orders.json` files.  

- **User-Friendly Console Interface**:  
  - Easy-to-navigate menu with clear instructions for each operation.  

## Technologies Used  
- **Programming Language**: Python  
- **Data Storage**: JSON files  

## How to Run the Project  
1. Make sure Python is installed on your system.  
2. Clone this repository or download the code files.  
3. Run the script in a terminal or command prompt:  
   ```bash
   python pos_system.py
   ```  
4. Follow the on-screen instructions to interact with the system.  

## File Structure  
- `pos_system.py`: The main Python script.  
- `menu.json`: Stores the restaurant’s menu data.  
- `orders.json`: Stores order details.  

## Future Enhancements  
- Add support for discounts and taxes.  
- Implement payment tracking (e.g., cash, card).  
- Improve error handling and input validation.  
- Add a graphical user interface (GUI).  

---
