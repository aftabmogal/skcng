# Minimal Backend (Admin Login + Contact Form)

1) Create MySQL DB (e.g., `sk_auto_db`).
2) Edit DB creds in `inc/config.php`.
3) Upload all files to hosting (or put under `htdocs/` for XAMPP).
4) Run `https://yourdomain.com/admin/install.php` once.
5) Log in: `https://yourdomain.com/admin/login.php` (admin / admin123).
6) Point your contact form to `/admin/api/contact_submit.php` with fields: name, phone, email, subject, message.
7) View messages in `Admin → Messages`.
8) Delete `admin/install.php` after install, or disable it inside the file.
