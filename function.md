# JavaScript Function Assignment: Analyzing Real-life Data
[#codeWithJSK](https://twitter.com/hashtag/codewithjsk?src=hashtag_click&f=live)

## Objective:
Create a JavaScript program that defines and utilizes functions to analyze a real-life dataset. The dataset is a list of transactions from an online store and movies, and your task is to create functions that extract meaningful information from this dataset.

  ```javascript
  const transactions = [
  {
    id: 1,
    product: 'Laptop',
    amount: 1200,
    category: 'Electronics',
  },
  {
    id: 2,
    product: 'Headphones',
    amount: 80,
    category: 'Electronics',
  },
  {
    id: 3,
    product: 'T-shirt',
    amount: 20,
    category: 'Clothing',
  },
  {
    id: 4,
    product: 'Smartphone',
    amount: 800,
    category: 'Electronics',
  },
  {
    id: 5,
    product: 'Sneakers',
    amount: 50,
    category: 'Footwear',
  },
  {
    id: 6,
    product: 'Camera',
    amount: 600,
    category: 'Electronics',
  },
  {
    id: 7,
    product: 'Jeans',
    amount: 40,
    category: 'Clothing',
  },
  {
    id: 8,
    product: 'Watch',
    amount: 300,
    category: 'Accessories',
  },
  {
    id: 9,
    product: 'Gaming Console',
    amount: 400,
    category: 'Electronics',
  },
  {
    id: 10,
    product: 'Dress Shoes',
    amount: 70,
    category: 'Footwear',
  },
  {
    id: 11,
    product: 'Tablet',
    amount: 500,
    category: 'Electronics',
  },
  {
    id: 12,
    product: 'Jacket',
    amount: 90,
    category: 'Clothing',
  },
  {
    id: 13,
    product: 'TV',
    amount: 1500,
    category: 'Electronics',
  },
  {
    id: 14,
    product: 'Skirt',
    amount: 30,
    category: 'Clothing',
  },
  {
    id: 15,
    product: 'Running Shoes',
    amount: 60,
    category: 'Footwear',
  },
  {
    id: 16,
    product: 'Printer',
    amount: 200,
    category: 'Electronics',
  },
  {
    id: 17,
    product: 'Hoodie',
    amount: 35,
    category: 'Clothing',
  },
  {
    id: 18,
    product: 'Fitness Tracker',
    amount: 100,
    category: 'Electronics',
  },
  {
    id: 19,
    product: 'Dress',
    amount: 80,
    category: 'Clothing',
  },
  {
    id: 20,
    product: 'Sandals',
    amount: 25,
    category: 'Footwear',
  },
  {
    id: 21,
    product: 'External Hard Drive',
    amount: 120,
    category: 'Electronics',
  },
  {
    id: 22,
    product: 'Polo Shirt',
    amount: 25,
    category: 'Clothing',
  },
  {
    id: 23,
    product: 'Wireless Earbuds',
    amount: 150,
    category: 'Electronics',
  },
  {
    id: 24,
    product: 'Dress Pants',
    amount: 50,
    category: 'Clothing',
  },
  {
    id: 25,
    product: 'Backpack',
    amount: 70,
    category: 'Accessories',
  },
  {
    id: 26,
    product: 'Mouse',
    amount: 20,
    category: 'Electronics',
  },
  {
    id: 27,
    product: 'Sweater',
    amount: 45,
    category: 'Clothing',
  },
  {
    id: 28,
    product: 'Smartwatch',
    amount: 250,
    category: 'Electronics',
  },
  {
    id: 29,
    product: 'Formal Shirt',
    amount: 60,
    category: 'Clothing',
  },
  {
    id: 30,
    product: 'Slippers',
    amount: 15,
    category: 'Footwear',
  },
  // Add more transactions to reach the desired count
];

  ```
##

```javascript
const movies = [
  {
    title: "Inception",
    director: "Christopher Nolan",
    year: 2010,
    genre: "Science Fiction",
    rating: 8.8,
  },
  {
    title: "The Shawshank Redemption",
    director: "Frank Darabont",
    year: 1994,
    genre: "Drama",
    rating: 9.3,
  },
  {
    title: "The Godfather",
    director: "Francis Ford Coppola",
    year: 1972,
    genre: "Crime",
    rating: 9.2,
  },
  {
    title: "Pulp Fiction",
    director: "Quentin Tarantino",
    year: 1994,
    genre: "Crime",
    rating: 8.9,
  },
  {
    title: "Forrest Gump",
    director: "Robert Zemeckis",
    year: 1994,
    genre: "Drama",
    rating: 8.8,
  },
  {
    title: "The Dark Knight",
    director: "Christopher Nolan",
    year: 2008,
    genre: "Action",
    rating: 9.0,
  },
  {
    title: "Fight Club",
    director: "David Fincher",
    year: 1999,
    genre: "Drama",
    rating: 8.8,
  },
  {
    title: "The Matrix",
    director: "Lana Wachowski, Lilly Wachowski",
    year: 1999,
    genre: "Science Fiction",
    rating: 8.7,
  },
  {
    title: "Goodfellas",
    director: "Martin Scorsese",
    year: 1990,
    genre: "Crime",
    rating: 8.7,
  },
  {
    title: "The Lord of the Rings: The Return of the King",
    director: "Peter Jackson",
    year: 2003,
    genre: "Fantasy",
    rating: 8.9,
  },
  {
    title: "Inglourious Basterds",
    director: "Quentin Tarantino",
    year: 2009,
    genre: "War",
    rating: 8.3,
  },
  {
    title: "The Silence of the Lambs",
    director: "Jonathan Demme",
    year: 1991,
    genre: "Thriller",
    rating: 8.6,
  },
  {
    title: "Schindler's List",
    director: "Steven Spielberg",
    year: 1993,
    genre: "Biography",
    rating: 8.9,
  },
  {
    title: "The Departed",
    director: "Martin Scorsese",
    year: 2006,
    genre: "Crime",
    rating: 8.5,
  },
  {
    title: "The Social Network",
    director: "David Fincher",
    year: 2010,
    genre: "Biography",
    rating: 7.7,
  },
  // English movies above

  // Hindi movies below
  {
    title: "Dilwale Dulhania Le Jayenge",
    director: "Aditya Chopra",
    year: 1995,
    genre: "Romance",
    rating: 8.1,
  },
  {
    title: "3 Idiots",
    director: "Rajkumar Hirani",
    year: 2009,
    genre: "Comedy",
    rating: 8.4,
  },
  {
    title: "Sholay",
    director: "Ramesh Sippy",
    year: 1975,
    genre: "Action",
    rating: 8.2,
  },
  {
    title: "Lagaan",
    director: "Ashutosh Gowariker",
    year: 2001,
    genre: "Drama",
    rating: 8.1,
  },
  {
    title: "Swades",
    director: "Ashutosh Gowariker",
    year: 2004,
    genre: "Drama",
    rating: 8.2,
  },
  {
    title: "Taare Zameen Par",
    director: "Aamir Khan",
    year: 2007,
    genre: "Drama",
    rating: 8.4,
  },
  {
    title: "Andaz Apna Apna",
    director: "Rajkumar Santoshi",
    year: 1994,
    genre: "Comedy",
    rating: 8.2,
  },
  {
    title: "Mughal-e-Azam",
    director: "K. Asif",
    year: 1960,
    genre: "Drama",
    rating: 8.4,
  },
  {
    title: "Gully Boy",
    director: "Zoya Akhtar",
    year: 2019,
    genre: "Drama",
    rating: 8.2,
  },
  {
    title: "Queen",
    director: "Vikas Bahl",
    year: 2013,
    genre: "Comedy-drama",
    rating: 8.2,
  },
  // Add more movies to reach the desired count
];


```

## Tasks:

### 1. Function to Calculate Total:
- Write a function `calculateTotalSales` that takes the `transactions` array as a parameter and returns the total sales amount.
- Create a function that takes in the movie dataset and a director's name as parameters. It should return an array of movies directed by that director.

### 2. Function to Filter:
- Write a function `filterTransactionsByCategory` that takes the `transactions` array and a `category` as parameters, and returns an array of transactions belonging to the specified category.
- Write a function to filter all movies with ratings above 8.5
### 3. Function with Default Values:
- Write a function `getTransactionDetails` that takes a `transaction` object as a parameter and logs the product name, amount, and category. Use default values for category (set it to 'Other' if not provided).
- Develop a function that lists all movies released after a given year. The default year should be set to 2000 if no year is provided
### 4. Anonymous Function and Callback:
- Write a function `calculateAverageAmount` that takes the `transactions` array and a callback function as parameters. The callback function should define the logic to extract the amount from each transaction. The main function should use the callback to calculate and return the average amount.

### 5. IIFE (Immediately Invoked Function Expression):
- Use an IIFE to create a function that logs the number of transactions in the dataset without explicitly calling it.
- Write an IIFE that calculates and displays the average rating of all the movies in the dataset.

### 6. Pass-by-Value:
Write a function `updateTransactionAmount` that takes a `transaction` object and an `updatedAmount` parameter. Inside the function, update the amount property of the transaction. Check if the original `transactions` array is modified outside the function.

## Good luck, and have fun coding!
