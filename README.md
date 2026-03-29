# LexiVault 🚀

**Your Professional, Blazing-Fast Vocabulary Management System**

LexiVault is a top-tier, single-file PHP application designed to help you build, manage, and master your personal vocabulary. Built with a sleek, modern UI and powered by a robust MySQL backend, LexiVault is the ultimate tool for logophiles, students, writers, and lifelong learners.

---

## ✨ Top-Notch Features

LexiVault isn't just a list of words; it's a complete learning ecosystem:

*   **⚡ Single-File Architecture:** The entire application (HTML, CSS, JS, and PHP) is packed into a single `index.php` file for incredibly simple deployment.
*   **📖 Dictionary Auto-Fetch:** Simply type a word and click "Fetch." LexiVault automatically pulls the pronunciation, part of speech, definition, and an example sentence from a free dictionary API.
*   **🧠 Smart Learning Modes:**
    *   **Review Cards:** Interactive flashcards with space repetition concepts (Tracks "Mastered" and "Learning" statuses).
    *   **Quiz Mode:** Test your knowledge with dynamically generated multiple-choice quizzes to build your learning streak.
*   **📊 Dynamic Dashboard:** Get deep insights into your vocabulary growth with beautiful charts tracking words added per day, category distributions, and your "Word of the Day".
*   **🔊 Text-to-Speech (TTS):** Built-in browser TTS allows you to hear the pronunciation of any word in your vault with a single click.
*   **🌍 Public API Endpoint:** Seamlessly access your vocabulary from other apps or websites using the built-in, lightning-fast fuzzy-search API (`?pbw=word`).
*   **✉️ Daily Email Digests:** Setup SMTP to receive automated daily emails summarizing your newly added words to reinforce memory.
*   **🔄 Universal Import/Export:** Never lose your data. Export your vault as JSON, CSV, or SQL backups, and import existing JSON word lists effortlessly.
*   **🗂️ Advanced Organization:** Group words by Category, tag them with multiple tags, set difficulty levels, and mark your absolute favorites with a Star.
*   **🖨️ Print & Share:** Generate beautiful printable layouts for offline study, or share a word's full details via your device's native sharing capabilities.

---

## 🚀 Quick Setup & Installation

Getting LexiVault running takes less than 2 minutes.

1. **Requirements:** A web server running PHP (7.4+) and a MySQL/MariaDB database.
2. **Upload:** Upload the `index.php` file to your web directory (e.g., `/var/www/html/lexivault/`).
3. **Run Wizard:** Navigate to the folder in your web browser (e.g., `http://yourdomain.com/lexivault/`).
4. **Configure:** LexiVault will automatically detect it's a new installation and launch a beautiful Setup Wizard. Enter your database credentials and create your Admin account.

*That's it! LexiVault handles database creation, table setup, and default configurations automatically.*

---

## 📡 Public API Integration

LexiVault provides a public, CORS-enabled endpoint so you can fetch your words remotely without authentication.

**Endpoint:**
`GET /index.php?pbw={YOUR_SEARCH_TERM}&format=json`

**Features:**
*   **Fuzzy Matching:** Finds exact matches, words starting with the term, or words containing the term.
*   **Format:** Returns plain text by default, or structured JSON by appending `&format=json`.

---

## 🛡️ Security & Storage

*   Secure password hashing (Bcrypt) for user accounts.
*   Automated `.htaccess` generation to protect local data files.
*   Prepared SQL statements (PDO) to prevent SQL injection attacks.

---

## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details.

---

## 📬 Contact & Support

Developed with ❤️ by **Vineet**

If you have any questions, feature requests, or just want to say hi, feel free to reach out:

📧 **Email:** psvineet@zohomail.in
