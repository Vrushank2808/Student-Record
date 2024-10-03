# Student Record Management using LocalStorage

This project is a simple web application that allows users to manage student records using **LocalStorage** in the browser. It provides a user-friendly interface where you can add, search, and manage records such as student names and details, all stored locally in the browser. 

## Features

- **Add Records**: Enter the student's name and details to create a new record.
- **Search Records**: Search for existing records by name.
- **Date Logging**: Each record logs the date when it was added.
- **LocalStorage Support**: All records are stored locally in the browser using LocalStorage, so data persists even after refreshing the page.
- **Delete Records**: Remove records with the click of a button.
- **Responsive Design**: The interface is simple and adjusts for different screen sizes.

## Getting Started

### Prerequisites

To run this project, you will need:

- A modern web browser that supports LocalStorage (e.g., Chrome, Firefox, Edge).

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/Vrushank2808/Student-Record.git
   ```

2. Navigate to the project directory:
   ```bash
   cd Student-Record
   ```

3. Open the `index.html` file in a web browser to start the application.

   Alternatively, you can run a local server to serve the project using Python or any other server of your choice.

   For Python:
   ```bash
   python -m http.server
   ```
   Then, open `http://localhost:8000` in your web browser.

## Usage

- **Adding Records**: Type the student's name and details in the input fields and click the "Add Record" button to save the information.
- **Searching Records**: Use the search bar to filter records by name.
- **Deleting Records**: Click the delete button next to the record to remove it from storage.
  
Records will be saved in the browser’s LocalStorage and can be retrieved even after closing the tab or refreshing the page.

## Technologies Used

- **HTML5**
- **CSS3**
- **JavaScript (ES6+)**
- **LocalStorage**

## Screenshot

![Screenshot 2024-10-03 114046](https://github.com/user-attachments/assets/95bf7c72-8f9f-4750-9a12-94993b21c53f)


## Future Enhancements

- Export records to a CSV file.
- Add edit functionality for existing records.
- Implement a notification system to confirm actions like adding and deleting records.

## Contributing

If you would like to contribute to this project, please fork the repository and submit a pull request. Contributions are welcome!

## License

This project is licensed under the MIT License.

---
