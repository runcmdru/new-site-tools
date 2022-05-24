# new-site-tools
Различный код, который пригодится для любого нового проекта

HTML / PHP / .HTACCESS

-----------------------------------------------------------
.htaccess
HSTS (HTTP Strict Transport Security) Test
для прохождения валидации на сайте https://hstspreload.org/
добавить в .htaccess строчку:
Header always set Strict-Transport-Security "max-age=63072000; includeSubDomains; preload"
-----------------------------------------------------------
