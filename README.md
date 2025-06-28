# PLP Bookstore MongoDB Operations

This project demonstrates various MongoDB operations including CRUD operations, advanced queries, aggregation pipelines, and indexing for the PLP Bookstore database.

## 📌 Prerequisites

- Node.js installed (v14+ recommended)
- MongoDB installed locally or access to a MongoDB Atlas cluster
- MongoDB Node.js driver (`mongodb` package)

## 🛠️ Setup Instructions

1. Clone this repository
2. Install dependencies:
   ```bash
   npm install mongodb
3. Set up your MongoDB connection:

For local MongoDB: Ensure MongoDB is running on mongodb://localhost:27017

For MongoDB Atlas: Replace the connection string in uri variable

📂 File Structure
index.js: Contains all MongoDB operations including:

Basic CRUD operations

Advanced queries with projection and sorting

Pagination implementation

Aggregation pipelines

Indexing and performance analysis

🚀 Running the Application
Execute the script with Node.js:

bash
node index.js
🔍 Operations Included
1. Basic CRUD Operations
Find books by genre (Fantasy)

Find books published in a specific year (1960)

Find books by author (George Orwell)

Update price of a book (The Alchemist)

Delete a book by title (Moby Dick)

2. Advanced Queries
Find books in stock and published after 2010

Projection to return only title, author, and price

Sorting books by price (ascending and descending)

Pagination with 5 books per page

3. Aggregation and Indexing
Created index on title field

Created compound index on author and published_year

Performance analysis using explain()

📊 Expected Output
The script will output:

Results of each query operation

Count of modified/deleted documents

Pagination results for multiple pages

Index creation confirmation

Query execution stats from explain()

🧪 Testing
To verify the operations:

Check console output for expected results

Examine your MongoDB collection after running to see changes

Compare execution times before/after indexing

📝 Notes
Ensure your MongoDB collection contains sufficient data (at least 10-15 books)

For pagination to work properly, you need more than 10 books in your collection

The connection string should be updated if using MongoDB Atlas

🤝 Contributing
Feel free to fork and modify this project for your own MongoDB learning purposes
- [MongoDB Node.js Driver](https://mongodb.github.io/node-mongodb-native/) 
