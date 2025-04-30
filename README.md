# 🌐 Sagar Kotrangi – Personal Portfolio Website

This is my personal portfolio website built using **Python (Flask)** and **Bootstrap 5**, designed to showcase my education, skills, projects, certifications, internship experience, and contact details.

> 💡 **Live Site**: *(Coming soon – will update once deployed on Render)*

---

## 🚀 Technologies Used

- **Python 3.11**
- **Flask (Micro web framework)**
- **HTML5 + CSS3 + Bootstrap 5**
- **JavaScript (for animations and dark mode)**
- **Render.com (for deployment)**

---

## 📂 Features

- 🔗 Fully responsive and mobile-friendly design  
- 🧠 About Me & Education section  
- 💼 Project highlights with clean cards  
- 📜 Certifications with direct links  
- 🛠 Skills (technical and personal)  
- 🏢 Internship Experience  
- 📎 Resume download  
- 📧 Contact info section  
- 🌙 Dark Mode toggle  
- ✨ Smooth fade-in animations on scroll  

---

## 🧪 How to Run This Project Locally

### 1. Clone the Repository
```bash
git clone https://github.com/your-username/sagar-portfolio.git
cd sagar-portfolio
```

### 2. Create a Virtual Environment and Install Dependencies
```bash
python -m venv venv
source venv/bin/activate # On Windows: venv\Scripts\activate
pip install -r requirements.txt
```

### 3. Run the Flask App
```bash
python app.py
```

### 4. Visit in Browser
Open: `http://127.0.0.1:5000`

---

## 📁 Folder Structure

```
sagar_portfolio/
├── app.py
├── requirements.txt
├── Procfile
├── README.md
│
├── static/
│ ├── style.css
│ ├── main.js
│ ├── Resume_Sagar_Kotrangi_2025.pdf
│ └── profile.jpg
│
└── templates/
    ├── base.html
    ├── index.html
    ├── about.html
    ├── skills.html
    ├── projects.html
    ├── certifications.html
    ├── internship.html
    ├── resume.html
    └── contact.html
```

---

## 🛠 Deployment Instructions (Render)

1. Create an account at [https://render.com](https://render.com)
2. Connect your GitHub repository
3. Select **New Web Service**
4. Set:
   - **Environment**: Python 3
   - **Start Command**: `gunicorn app:app`
5. Add a `Procfile` with:
   ```
   web: gunicorn app:app
   ```

---

## 👤 About Me

I'm **Sagar Kotrangi**, an EEE graduate passionate about solving real-world problems using technology. I love working with Python, IoT systems, and data-driven applications.

- 📧 Email: [sagar.kotrangi369@gmail.com](mailto:sagar.kotrangi369@gmail.com)
- 💼 LinkedIn: [linkedin.com/in/sagar-kotrangi369](https://linkedin.com/in/sagar-kotrangi369)
- 💻 GitHub: [github.com/sagarkotrangi014](https://github.com/sagarkotrangi014)

---

## 📜 License

This project is open-source and available under the [MIT License](LICENSE).
```
MIT License

Copyright (c) 2025 Sagar Kotrangi

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the “Software”), to deal
in the Software without restriction, including without limitation the rights  
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell  
copies of the Software, and to permit persons to whom the Software is  
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included  
in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED “AS IS”, WITHOUT WARRANTY OF ANY KIND,  
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES  
OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND  
NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT  
HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY,  
WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING  
FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE  
OR OTHER DEALINGS IN THE SOFTWARE.