# -library-book-inventory
A modular Python CLI app to manage book inventory, track borrowings, and calculate overdue fines using JSON storage

## Features

### 1. Book Inventory Management (CRUD)
* **Add New Books**: Register books with details including ISBN, title, author, and available copy count[span_0](start_span)[span_0](end_span).
* **Catalog Search & Retrieval**: Search the library catalog instantly by ISBN, title, or author name[span_1](start_span)[span_1](end_span).
* **Update & Delete Entries**: Modify book details or remove outdated records from the system[span_2](start_span)[span_2](end_span).

### 2. Check-Out & Return Engine
* **Issue Books**: Process book check-outs while automatically verifying copy availability[span_3](start_span)[span_3](end_span).
* **Process Returns**: Handle returned items and automatically restore the available stock count[span_4](start_span)[span_4](end_span).
* **Stock Tracking**: Prevent over-borrowing by enforcing real-time copy limits[span_5](start_span)[span_5](end_span).

### 3. Borrower & Fine Management
* **Member History**: Maintain records of member details and their actively borrowed books[span_6](start_span)[span_6](end_span).
* **Overdue Fine Calculation**: Automatically calculate late return penalties based on overdue days[span_7](start_span)[span_7](end_span).
* **Local Data Persistence**: Save all inventory and transaction records to JSON files without requiring external databases[span_8](start_span)[span_8](end_span).
