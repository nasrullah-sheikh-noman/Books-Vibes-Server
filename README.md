# Book API Mock Data

This repository contains mock JSON data for a book management system.


## Features
- 20 sample book objects
- Category: Story, Tech, Science
- Book details included:
  - id
  - title
  - author
  - description
  - category
  - available_quantity
  - image_url

## usages
Use this API as a fake backend for frontend projects such as:
- Next.js
- React.js
- JavaScript practice projects

## Related project
- Frontend: https://github.com/nasrullah-sheikh-noman/BooksVibes
- Live site: https://books-vibes-theta.vercel.app/

## API Endpoint

```bash
https://books-vibes-server.onrender.com/Books
```

```javascript
const res = await fetch("https://books-vibes-server.onrender.com/Books");
const books = res.json();

console.log(books);
```

## Purpose:
Mock book API with JSON data for frontend development, testing, and portfolio/demo purposes.