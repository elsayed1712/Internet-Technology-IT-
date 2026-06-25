# 📚 Book Fair & Literature — Web Application

A full-featured front-end web application for a **Book Fair & Literature platform**, built with vanilla HTML, CSS, and JavaScript. The platform supports user authentication, book browsing, community features, and a complete admin panel — all powered by `localStorage` with no backend required.

---

## 🌟 Features

### 👤 User Side
- **Authentication** — Register, Login, Logout with role-based access (Admin / User)
- **Home Page** — Featured books display with dynamic rendering
- **Book Browsing** — Browse and search through the book catalog
- **Book Details** — View full book info, add to Cart or Wishlist
- **New Releases** — Dedicated page for latest book arrivals
- **Blog** — Read and explore literature-related blog posts
- **Forum** — Community discussion board with post creation and replies
- **Feedback** — Submit user feedback directly from the site
- **Profile** — View and manage user profile
- **Messaging** — Internal messaging system between users

### 🛠️ Admin Side
- **Admin Panel** — Manage books, users, and blog posts
- **Book Management** — Add, edit, delete books from the catalog
- **User Management** — View and manage registered users
- **Blog Management** — Create and manage blog content

### 🌐 Multilingual Support
- Full **Arabic / English** toggle with RTL/LTR layout switching
- All UI elements translated via a centralized `translations.js`

---

## 🗂️ Project Structure

```
IT Project/
│
├── home.html / home.css / home.js         # Landing page with featured books
├── login.html / login.css / login.js      # User login
├── register.html / register.css / register.js  # User registration
├── books.html / books.js                  # Book catalog
├── book-details.html / book-details.css / book-details.js  # Book detail view
├── search.html / search.css / search.js   # Search functionality
├── release.html / release.css / release.js  # New releases
├── blog.html / blog.css / blog.js         # Blog page
├── forum.html / forum.css / forum.js      # Community forum
├── feed back.html / feed back.css / feed back.js  # Feedback form
├── profile.html / profile.css / profile.js  # User profile
├── messages.html / messages.js            # Messaging system
├── Admin.html / Admin.css / admin.js      # Admin panel
├── blog-management.html / blog-management.js  # Admin blog management
├── users.html / users.js                  # Admin user management
├── navbar.js                              # Shared navbar logic & auth state
├── translations.js                        # AR/EN translation strings
├── config.js                              # Global config & localStorage keys
└── *.jpg                                  # Book cover images
```

---

## 🛠️ Tech Stack

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)

- **HTML5** — Semantic page structure
- **CSS3** — Custom styling per page
- **Vanilla JavaScript** — DOM manipulation, event handling, localStorage
- **Font Awesome** — Icons via CDN
- **localStorage** — Client-side data persistence (users, books, cart, wishlist)

---

## 🚀 How to Run

No installation or server required.

1. Clone or download the repository
2. Open `home.html` in any modern browser

```bash
git clone https://github.com/your-username/your-repo.git
cd "IT Project"
# Open home.html in your browser
```

> 💡 For the best experience, use **Live Server** extension in VS Code or any local server to avoid `localStorage` cross-origin issues.

---

## 🔐 User Roles

| Role  | Access |
|-------|--------|
| Guest | Browse books, search, read blog |
| User  | All above + forum, feedback, profile, wishlist, cart, messages |
| Admin | All above + Admin Panel (manage books, users, blog) |

---

## 📌 Notes

- All data is stored in the browser's `localStorage` — no backend or database needed
- Admin panel is only visible to users with admin privileges
- Supports bilingual UI (English 🇬🇧 / Arabic 🇸🇦) with automatic RTL layout
