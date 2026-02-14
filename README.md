# Safe Cracker - Web Game

Web-based password guessing game built with PHP and MySQL for the Web Development course at IFRS (Instituto Federal do Rio Grande do Sul). Players attempt to crack a safe's password within 10 attempts, earning points based on how quickly they succeed. Features user authentication and score tracking. Created in 2019.

## 🎮 Game Mechanics
- 10 attempts to guess the correct password
- Points awarded based on number of attempts (10 points for first try, decreasing to 1 point for tenth)
- Persistent score tracking across sessions
- Player statistics (total accumulated points, games played, last game score)

## 🛠️ Technologies
- **PHP** - Server-side logic and authentication
- **MySQL** - User data and score persistence
- **HTML/CSS** - Frontend interface
- **Sessions & Cookies** - User authentication management

## 📦 Project Structure
- `login.php` / `login.html` - User authentication
- `paginaPrincipal.html` - Main game interface
- `geraSenha.php` - Password generation logic
- `verificaSenha.php` - Password validation
- `inserePontuacao.php` - Score tracking
- `usuario.sql` - Database schema
- `actions/conexao.php` - Database connection handler

## 🔒 Features
- User registration and login system
- Cookie-based session management
- Password validation with attempt tracking
- Score accumulation across multiple games
- Player ranking system

## ⚠️ Security Note
This is an academic project from 2018. The authentication system uses basic security practices and should not be used in production without implementing proper password hashing, SQL injection prevention, and modern security standards.

## 🎓 Academic Context
Developed as a web development project demonstrating full-stack development with PHP and MySQL database integration.
