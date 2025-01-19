
# Expense Tracker Application

A Python-based desktop application to manage your expenses. The application enables you to add, edit, delete, and visualize your expenses, along with generating PDF receipts.

## Features

- **Add Expenses**: Input date, category, and amount to track expenses.
- **Edit/Delete Expenses**: Modify or remove records directly from the table.
- **Visualize Data**: Generate bar charts to analyze spending patterns.
- **Generate PDF Receipts**: Create a PDF receipt containing tabular data and a chart visualization.
- **Context Menu**: Right-click on an expense entry to quickly edit or delete.

## Technologies Used

- **Python**: Core programming language.
- **Tkinter**: For the graphical user interface.
- **SQLite**: To store expense records.
- **Matplotlib**: For creating data visualizations.
- **ReportLab**: For generating PDF reports.

## How to Run

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/<your-username>/expense-tracker.git
   cd expense-tracker
   ```

2. **Install Dependencies**:
   Ensure the required Python libraries are installed:
   ```bash
   pip install matplotlib reportlab
   ```

3. **Run the Application**:
   Execute the Python script:
   ```bash
   python expense_tracker.py
   ```

## Usage

1. **Add Expense**:
   - Enter the **Date**, **Category**, and **Amount** in the respective fields.
   - Click `Add Expense` to save the record.

2. **Edit/Delete Expense**:
   - Select an entry from the table.
   - Use the context menu (right-click) to edit or delete the record.

3. **Visualize Data**:
   - Click `Visualize Data` to display a bar chart of expenses by date.

4. **Generate Receipt**:
   - Click `Generate Receipt` to create a PDF file named `expense-receipt.pdf`.

## Project Structure

- **Database**:
  - Uses an SQLite database (`expenses.db`) to store expense data persistently.
  - Automatically created on the first run.

- **Core Functionalities**:
  - Adding, editing, deleting, and displaying expenses in a table.
  - Visualizing expenses with a bar chart.
  - Generating detailed PDF receipts.

- **PDF Features**:
  - Tabular data representation.
  - Integrated bar chart visualization.

## Code Highlights

### Key Methods in the Application

- **`create_database`**: Sets up the SQLite database for storing expense records.
- **`add_expense`**: Saves new expense entries.
- **`edit_expense`**: Edits selected entries.
- **`delete_expense`**: Deletes selected records.
- **`visualize_data`**: Displays a bar chart using Matplotlib.
- **`generate_receipt`**: Creates a PDF file with expenses and their visualization.

### GUI Elements

- **Expense Form**: Input fields for date, category, and amount.
- **Expense Table**: Displays all recorded expenses.
- **Buttons**: For adding expenses, visualizing data, and generating receipts.
- **Context Menu**: Right-click options for editing or deleting entries.

## Screenshots

- **Main Interface**: Form and table layout for managing expenses.
- **Visualization**: Bar chart showcasing expense trends.
- **Generated Receipt**: PDF containing detailed data and visualization.

## Future Enhancements

- Add user authentication for secure, personalized tracking.
- Support exporting data to CSV and other formats.
- Include additional charts like pie or line graphs.

## License

This project is licensed under the MIT License. Feel free to use and enhance it.

---

### Clone this repository and start tracking your expenses today!
