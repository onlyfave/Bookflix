# Bookflix - Your Online E-Library

![Screenshot 2025-02-10 223700](https://github.com/user-attachments/assets/77541b6b-1df1-44e8-9e02-af0a60f3f0a9)

Bookflix is an online e-library website where users can browse a collection of books, search for specific titles, authors, or genres, and toggle between light and dark modes for a comfortable reading experience. The website is built using **HTML**, **CSS**, and **JavaScript**.

---

## Features

1. **Book Collection**:
   - Browse a curated collection of books with covers, titles, authors, and genres.
   - Books are displayed in a responsive grid layout.

2. **Search Functionality**:
   - Search for books by title, author, or genre.
   - Dynamic filtering of books based on the search query.

3. **Dark Mode**:
   - Toggle between light and dark modes for a better viewing experience.

4. **Load More Button**:
   - Initially, only a subset of books is displayed.
   - Click the "Load More" button to display additional books.

5. **Responsive Design**:
   - The website is fully responsive and works on all devices (desktop, tablet, and mobile).

---

## Technologies Used

- **HTML**: Structure of the website.
- **CSS**: Styling and layout.
- **JavaScript**: Dynamic functionality (search, dark mode, load more).
- **Placeholder Images**: Placeholder.com for book cover images.

---

## Setup Instructions

Follow these steps to set up and run the Bookflix website locally on your machine.

### Prerequisites

- A modern web browser (e.g., Chrome, Firefox, Edge).
- A code editor (e.g., VS Code, Sublime Text).

### Steps

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/your-username/bookflix.git
   cd bookflix
   ```

2. **Open the Project**:
   - Open the project folder in your code editor.

3. **Run the Website**:
   - Open the `index.html` file in your browser.
   - Alternatively, use a live server extension in your code editor to run the site.

4. **Customize**:
   - Replace placeholder book cover images with actual images by updating the `cover` property in the `books` array in `script.js`.
   - Add more books to the `books` array if needed.

---

## File Structure

```
bookflix/
├── index.html          # Main HTML file
├── styles.css          # CSS file for styling
├── script.js           # JavaScript file for functionality
├── images/             # Folder for book cover images (optional)
└── README.md           # This file
```

---

## How to Use

1. **Browse Books**:
   - The homepage displays a grid of featured books with their covers, titles, authors, and genres.

2. **Search for Books**:
   - Use the search bar at the top to search for books by title, author, or genre.
   - The results will update dynamically as you type.

3. **Toggle Dark Mode**:
   - Click the "Dark Mode" button in the header to switch between light and dark themes.

4. **Load More Books**:
   - Click the "Load More" button at the bottom of the book list to display additional books.

---

## Customization

### Adding More Books
To add more books, update the `books` array in `script.js`:
```javascript
const books = [
  {
    title: "Book Title",
    author: "Author Name",
    genre: "Genre",
    cover: "path/to/image.jpg" // Add the image URL or local path
  },
  // Add more books here
];
```

### Changing the Color Scheme
To change the color scheme, update the CSS variables in `styles.css`:
```css
:root {
  --primary-color: #FF0080; /* Vibrant pink */
  --secondary-color: #333; /* Dark gray */
  --background-color: #f4f4f4; /* Light gray */
  --text-color: #333; /* Dark text */
}

body.dark-mode {
  --primary-color: #FF0080; /* Keep the pink accent */
  --secondary-color: #1a1a1a; /* Darker gray */
  --background-color: #121212; /* Dark background */
  --text-color: #ffffff; /* White text */
}
```

### Replacing Placeholder Images
Replace the placeholder image URLs in the `books` array with actual book cover images. You can either:
- Use local images (store them in the `images/` folder and update the paths).
- Use external image URLs (ensure they are publicly accessible).

---

## Contributing

Contributions are welcome! If you'd like to contribute to this project, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes and commit them.
4. Submit a pull request.

---

## License

This project is licensed under the **MIT License**. See the [LICENSE](LICENSE) file for details.

---

## Acknowledgments

- **Placeholder.com**: For providing placeholder images.
- **Open Source Community**: For inspiration and resources.

---


Enjoy exploring **Bookflix**! 📚✨

---

