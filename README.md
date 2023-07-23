# Simple Contact Form

The Simple Contact Form is a basic web application built using PHP, Bootstrap, JavaScript, and MySQL. It allows users to submit their contact information and messages, which are then stored in a MySQL database. Admin can see the sent messages.

## 🚀 Features

- User-friendly and responsive design with Bootstrap.
- Client-side validation using JavaScript to ensure data integrity.
- Server-side validation with PHP to prevent malicious submissions.
- Contact information and messages are stored in a MySQL database for future reference.
- Easy to customize and integrate into existing projects.

## 🛠️ Technologies Used

- Frontend: HTML5, CSS3, Bootstrap 5, JavaScript
- Backend: PHP
- Database: MySQL

## 📄 Database Schema

The MySQL database has the following table structure for storing contact form submissions:

```sql
CREATE TABLE entries (
    id INT AUTO_INCREMENT PRIMARY KEY,
    name VARCHAR(100) NOT NULL,
    email VARCHAR(100) NOT NULL,
    subject VARCHAR(200) NOT NULL,
    message TEXT NOT NULL
);
```

## 📝 Installation and Setup

1. Clone the repository:

```bash
git clone https://github.com/your-username/simple-contact-form.git
cd simple-contact-form
```

2. Import the uploaded database into the phpmyadmin.

3. Run index.php in the browser.

## 📷 Screenshots

![Admin Login Screen](https://github.com/Towkir7970/Simple-Contact-Us-Form/blob/98873a8003b00aeb61883cceaff768a35c9e5fde/contact%20us%20screenshots/admin%20login%20page.png)
![Database Records](https://github.com/Towkir7970/Simple-Contact-Us-Form/blob/98873a8003b00aeb61883cceaff768a35c9e5fde/contact%20us%20screenshots/after%20second%20entry.png)

## 📄 License

This project is licensed under the [MIT License](LICENSE).

## 🤝 Contributing

Contributions are welcome! If you find any bugs or want to add new features, please feel free to open an issue or submit a pull request.

## 📧 Contact

For any inquiries or feedback, please reach out to us at contact@example.com.

---
