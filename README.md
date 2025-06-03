
```markdown
# 📝 PHP Blog Website

A full-featured blogging platform built with **PHP**, **MySQL**, **Bootstrap**, and **jQuery**. Users can register, log in, read blog posts, comment, like, and interact with content. Admins can manage blog posts, categories, users, and moderate comments.

---

## 🚀 Features

- 🔐 User Authentication (Login, Signup, Logout)
- 📰 Blog Post Listing with Cover Images
- 🗨️ Commenting System
- 👍 Like/Unlike Functionality (AJAX)
- 🧑‍💼 Admin Dashboard:
  - Manage Users
  - Manage Blog Posts (CRUD)
  - Manage Categories (CRUD)
  - Moderate Comments
- 🖼️ Rich Text Editor for Post Creation
- 🎨 Responsive Design with Bootstrap
- 🧰 Secure with PDO, input validation & session handling

---

## 🛠️ Technologies Used

- **Backend:** PHP (Procedural), PDO
- **Frontend:** HTML5, CSS3, Bootstrap 5, jQuery
- **Database:** MySQL (Workbench)
- **Extras:** AJAX, Rich Text Editor

---

## 🧾 Folder Structure

```

php-blog-website/
├── admin/              # Admin dashboard files
│   ├── data/           # DB logic (Post.php, Comment.php, etc.)
│   ├── inc/            # Includes (sidebar, navbar)
│   ├── req/            # Request handlers (CRUD)
├── css/                # Custom styles
├── js/                 # JavaScript & rich text editor plugin
├── img/                # User/default images
├── php/                # User login/signup/comment logic
├── upload/blog/        # Blog post cover images
├── inc/                # Shared navbars
├── db\_conn.php         # PDO DB connection
├── login.php, signup.php, blog.php, index.php, etc.

````

---

## 🗃️ Database

Create a database named `blog_db` and import the schema manually or via Workbench. The main tables include:

- `users` - Registered users
- `admin` - Admin credentials
- `post` - Blog content
- `category` - Blog categories
- `comment` - User comments
- `likes` - Likes for posts

Use `password_hash()` and `password_verify()` for secure password storage.

---

## ⚙️ Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/MyatThuraSoe/Blog-PHP-Mysql.git
````

2. Import the `blog_db` schema into MySQL using MySQL Workbench or `phpMyAdmin`.

3. Edit `db_conn.php` with your local DB credentials:

   ```php
   $sName = "localhost";
   $uName = "root";
   $pass  = "your_password";
   $db_name = "blog_db";
   ```

4. Place the project in your XAMPP `htdocs/` folder.

5. Run it in the browser:

   ```
   http://localhost/php-blog-website/
   ```

---

## 📸 Screenshots

> (You can add screenshots here using: `![Home Page](screenshots/home.png)`)

---

## ✅ Best Practices Followed

* PDO prepared statements for DB queries
* XSS prevention via `htmlspecialchars()`
* Error redirection and alert messages
* Modular folder structure

---

## 🔮 Future Improvements

* ✅ Pagination and search
* ✅ REST API integration
* ✅ Profile picture & user dashboard
* ✅ WYSIWYG editor with media support
* ✅ Laravel migration

---

## 🧑‍💻 Author

Built by [Myat Thura Soe](https://github.com/MyatThuraSoe)
Special thanks to [Elias Abdurrahman](https://github.com/codingWithElias) for tutorial inspiration.

---

## 📄 License

This project is licensed under the MIT License.

```

---


```
