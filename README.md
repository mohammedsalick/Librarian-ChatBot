# 📚 LIBRARIAN: Your Virtual Library Assistant

**Librarian** is a Flask-based chatbot designed to assist users with **book-related queries**. Whether you're looking for information on a specific book, its author, genre, availability, or seeking similar reads — Librarian has got you covered. The chatbot integrates with **Supabase** for user authentication and conversation storage, and uses the **Gemini API** for generating natural, helpful, and polite responses.

---

## 🌟 Features

- 🔐 **User Authentication**: Secure login and registration via Supabase.
- 💬 **Real-Time Chat**: Interact with the Librarian through a seamless web chat UI.
- 🧠 **AI-Powered Responses**: Book-specific answers generated via the Gemini API.
- 💾 **Chat History**: All conversations are stored in Supabase for future reference.
- ⚡ **Lightweight Backend**: Built using Flask for quick deployment and performance.

---

## 📋 Table of Contents

1. [Setup Instructions](#setup-instructions)
2. [Environment Variables](#environment-variables)
3. [Run the Application](#run-the-application)
4. [Using the Application](#using-the-application)
5. [Contributing](#contributing)
6. [License](#license)
7. [Contact](#contact)

---

## ⚙️ Setup Instructions

### 1. Clone the Repository

```bash
git clone https://github.com/mohammedsalick/LIBRARIAN.git
cd LIBRARIAN
```

### 2. Install Dependencies

Ensure you have Python installed (version 3.7 or above recommended).

```bash
pip install -r requirements.txt
```

---

## 🔐 Environment Variables

Create a `.env` file in the root directory and add the following credentials:

```
SUPABASE_URL=your_supabase_url
SUPABASE_KEY=your_supabase_key
GEMINI_API_KEY=your_gemini_api_key
FLASK_SECRET_KEY=your_flask_secret_key
```

> Replace each `your_*` with actual credentials from Supabase and Gemini.

---

## 🚀 Run the Application

Start the Flask development server by running:

```bash
python app.py
```

The application will be available at:  
**http://127.0.0.1:5000/**

---

## 🧑‍💻 Using the Application

1. Go to: `http://127.0.0.1:5000/home`
2. Register a new account or log in to an existing one.
3. Type in the name of a book to get:
   - ✍️ Author  
   - 🏷️ Genre  
   - ✅ Availability (Available or Not Available)  
   - 📚 Similar books or authors

4. If you ask a non-book-related question (e.g., life advice, tech support), the bot will respond:
   > "I'm here to help with library books only. Please ask about books, authors, or genres."

---

## 🤝 Contributing

We welcome your contributions!

1. Fork the repository.
2. Create a new branch:

```bash
git checkout -b feature-branch
```

3. Commit your changes:

```bash
git commit -m "Add new feature"
```

4. Push to GitHub:

```bash
git push origin feature-branch
```

5. Open a Pull Request for review.

---

## 📝 License

This project is licensed under the **MIT License**.  
See the [LICENSE](./LICENSE) file for more details.

---

## 📬 Contact

For any questions, feedback, or suggestions:

📧 Email: [mhmmdsalick@gmail.com](mailto:mhmmdsalick@gmail.com)  
💻 GitHub: [MohammedSalick](https://github.com/mohammedsalick)

---

## 🖼️ Screenshots

![WhatsApp Image 2025-04-07 at 21 20 00_ba787e36](https://github.com/user-attachments/assets/85d78c90-a738-48f7-96f6-49364612939c)
![WhatsApp Image 2025-04-07 at 21 21 43_8b215dab](https://github.com/user-attachments/assets/87b45522-1a09-4744-b26e-86b66071f0c3)
![WhatsApp Image 2025-04-07 at 21 21 14_b0ad470d](https://github.com/user-attachments/assets/7a446faf-77a7-44fd-874c-0e5fcdf47b97)
![WhatsApp Image 2025-04-07 at 21 29 51_84f05905](https://github.com/user-attachments/assets/e743c335-d7f8-46e5-82fc-fab4d263abb0)





---

Thank you for checking out **Librarian Chatbot**! Happy reading! 📖✨
```

Let me know if you want to add badges (e.g., `Made with Python`, `MIT License`, or deployment links), or if you plan to deploy it and need a section for that too.
