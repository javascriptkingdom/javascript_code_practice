# JavaScript Array Operations: Real-Life Applications

## Objective

The objective of this assignment is to utilize JavaScript array methods (`push`, `pop`, `shift`, `unshift`, `length`, `includes`, `indexOf`, `splice`, `slice`, `Array.isArray`, `.concat`, `flat`), along with loops, to solve practical problems using real-life datasets.

### 1: Grocery Shopping List

You're developing an application to manage a grocery shopping list. Your task is to handle and manipulate the shopping list using JavaScript arrays.
#### Data set
```javascript

    "Basmati Rice",
    "Masoor Dal",
    "Paneer",
    "Turmeric Powder",
    "Ghee",
    "Mangoes",
    "Assam Tea",
    "Papadums",
    "Jaggery"

```
#### Tasks:

1. **Initialize Shopping List:**
    - Create an array `shoppingList` containing strings representing items needed for shopping.
    
2. **Add and Remove Items:**
    - Implement functionality to add items to the shopping list using `push` and remove items using `pop`.
    - Use `shift` and `unshift` to manage priority items (move items to the top or remove them).

###  2: Book Inventory Management

You're building a system to manage a bookstore's inventory. Your goal is to handle and update the book inventory using JavaScript arrays.
#### Data set
```javascript
const bookInventory = [
    ["The God of Small Things", "Arundhati Roy", 10],
    ["Train to Pakistan", "Khushwant Singh", 15],
    ["The White Tiger", "Aravind Adiga", 8],
    ["The Immortals of Meluha", "Amish Tripathi", 20],
    ["Midnight's Children", "Salman Rushdie", 12]
];
```
#### Tasks:

1. **Initialize Book Inventory:**
    - Create an array `bookInventory` containing nested arrays representing book details like title, author, and quantity.
    
2. **Update Inventory:**
    - Implement functionality to add new books using `concat`.
    - Use `splice` to update book details (change quantity or remove books).

### 3: Music Playlist Organization (jsk music)

You're working on a music streaming application. Your task is to manage a playlist and perform operations using JavaScript arrays.
#### Data set
```javascript

    "Chaiyya Chaiyya - Dil Se",
    "Maa Tujhe Salaam - A.R. Rahman",
    "Kabira - Yeh Jawaani Hai Deewani",
    "Kal Ho Naa Ho - Kal Ho Naa Ho",
    "Mile Sur Mera Tumhara - Doordarshan"

```
#### Tasks:

1. **Initialize Music Playlist:**
    - Create an array `musicPlaylist` containing strings representing song titles.
    
2. **Manipulate Playlist:**
    - Use loops to display the contents of `musicPlaylist`.
    - Implement `slice` to create a smaller playlist based on specific criteria (e.g., top 5 songs).

