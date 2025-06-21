

---

````markdown
# 📚 Book REST API with Node.js and Express

This project is a simple RESTful API for managing a list of books using **Node.js** and **Express**. The book data is stored **in memory** (no database), making it ideal for learning and testing CRUD operations using tools like **Postman**.

---

## 🚀 Features

- **GET /books** – Retrieve all books
- **GET /books/:id** – Get a single book by ID
- **POST /books** – Add a new book
- **PUT /books/:id** – Update a book's details
- **DELETE /books/:id** – Remove a book

---

## 🛠️ Tools Used

- [Node.js](https://nodejs.org/)
- [Express.js](https://expressjs.com/)
- [Postman](https://www.postman.com/) (for testing API endpoints)
- [VS Code](https://code.visualstudio.com/) (or any preferred code editor)

---

## 📦 Installation

1. Clone the repository or download the files.

```bash
git clone https://github.com/your-username/book-api.git
cd book-api
````

2. Install dependencies:

```bash
npm install
```

3. Run the server:

```bash
node server.js
```

The server will start at: `http://localhost:3000`

---

## 📘 Example Book Object

```json
{
  "title": "The Great Gatsby",
  "author": "F. Scott Fitzgerald"
}
```

---

## 📬 API Endpoints

| Method | Endpoint    | Description       |
| ------ | ----------- | ----------------- |
| GET    | /books      | Get all books     |
| GET    | /books/\:id | Get book by ID    |
| POST   | /books      | Add a new book    |
| PUT    | /books/\:id | Update book by ID |
| DELETE | /books/\:id | Delete book by ID |

---

## 📌 Notes

* Data is stored in memory, so restarting the server will reset the book list.
* Ensure `Content-Type: application/json` is set in the headers when sending POST/PUT requests.

---

## 🤝 License

This project is open-source and free to use for educational purposes.

---

## 👨‍💻 Author

**Adityan P**
Feel free to fork or star the repository if you find it useful!

```

---


