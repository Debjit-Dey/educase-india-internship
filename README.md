# 📝 User Registration Form with React, Tailwind CSS & Appwrite

A complete user registration form built using **React.js**, **Tailwind CSS**, and **React Hook Form** for seamless input validation. The form is integrated with **Appwrite** for secure user authentication and account creation.

---

## 🚀 Features

- ⚛️ Built with React.js (Vite setup)
- 💨 Styled using Tailwind CSS
- ✅ Form validation using React Hook Form
- 🔐 User authentication and account creation with Appwrite
- 🔄 Real-time feedback for input validation
- 📱 Fully responsive UI

--

## 🛠️ Tech Stack

- **Frontend**: React.js, Tailwind CSS, React Hook Form
- **Backend/Auth**: Appwrite

---

## 📦 Installation

1. **Clone the repository**


git clone https://github.com/yourusername/your-repo-name.git
cd your-repo-name
Install dependencies

bash
Copy
Edit
npm install
Configure Appwrite

Create a project on Appwrite.

Enable Email & Password authentication.

Note down your Project ID and Endpoint.

Create a .env file in the root directory and add:

env
Copy
Edit
VITE_APPWRITE_ENDPOINT=https://cloud.appwrite.io/v1
VITE_APPWRITE_PROJECT_ID=your_project_id
Run the development server

bash
Copy
Edit
npm run dev
🧠 How It Works
Uses React Hook Form for efficient and performant form handling.

Validates inputs such as email and password in real-time.

On form submission, it communicates with Appwrite's account.create method to register users.

🐛 Known Issues
If you're facing CORS issues while calling Appwrite APIs locally:

Ensure you are using the Appwrite SDK (appwrite npm package) and not calling API endpoints directly.

Go to your Appwrite Project → Settings → Platforms → Add http://localhost:5173 as a Web platform.

Do not use https://cloud.appwrite.io/console/... in your API code — use https://cloud.appwrite.io/v1 and the SDK methods.

🤝 Contributing
Contributions, issues, and feature requests are welcome!
Feel free to open an issue or submit a pull request.

📄 License
This project is licensed under the MIT License.

🙌 Acknowledgements
React Hook Form

Tailwind CSS

Appwrite

✨ Author
Made with ❤️ by Debjit Dey
