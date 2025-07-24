# Khaatabook 📘

A simple **account-book web app** built using **Node.js**, **Express**, and vanilla **HTML/CSS/JavaScript**.  
Easily **create**, **view**, **edit**, and **delete** records (“Hisaabs”) using a clean, file-based system.

---

## ✨ Features

- 🆕 Create new hisaab files
- 👁️ View list of all hisaabs
- ✏️ Edit existing hisaabs
- 🗑️ Delete hisaabs
- ✅ Dynamic filenames (no duplicates)
- 🔥 Simple & responsive UI with Tailwind CSS

---
## 📸 Screenshots
<img width="1884" height="906" alt="Screenshot 2025-07-24 154945" src="https://github.com/user-attachments/assets/02ebca33-c7ac-42f8-9c55-6ca9648dc710" />

<img width="1816" height="904" alt="Screenshot 2025-07-24 155007" src="https://github.com/user-attachments/assets/c53ee02a-a4d6-4a41-a4dc-2a38214af6fc" />

<img width="1886" height="858" alt="Screenshot 2025-07-24 155038" src="https://github.com/user-attachments/assets/5057f7e4-eb4f-4a75-a434-47e7373d56c2" />





## 🧩 Tech Stack

- **Backend**: Node.js + Express
- **Frontend**: HTML, CSS (Tailwind), JavaScript
- **Data Storage**: File system (EJS templates)

---


---

## ✅ Getting Started

1. **Clone the repository**
    ```bash
    git clone https://github.com/manumay1962/khatabook.git
    cd khatabook
    ```

2. **Install dependencies**
    ```bash
    npm install
    ```

3. **Add start script** in `package.json`:
    ```json
    "scripts": {
      "start": "node server.js"
    }
    ```

4. **Start the app**
    ```bash
    npm start
    ```

5. **Open in your browser**  
   Visit http://localhost:3000

---

## 🚀 How It Works

- **Create Hisaab**: Fill out a form → generates a file in `data/`
- **View Hisaabs**: Lists all files in `data/` with view/edit/delete links
- **Edit Hisaab**: Loads contents into form → overwrite file on submit
- **Delete Hisaab**: Removes the file from `data/`

---

## 🚀 Deployment Guide

To deploy your full-stack app:

- **Backend**: Use **Render / Railway** to host your Express server  
  - Build: `npm install`  
  - Start: `npm start`

*(No database required — storage is file-based.)*

---

## 🛠️ Customization Ideas

- ✅ Add **rich text editor** for hisaab content
- ✅ Add **date/time stamping**
- ✅ Integrate **proper database** (MongoDB or SQLite)
- ✅ Add **user authentication** (future upgrade)

---

## 🤝 Contributing

1. Fork it 🌱  
2. Create your feature branch (`git checkout -b feature/AwesomeFeature`)  
3. Commit changes (`git commit -m 'Add awesome feature'`)  
4. Push (`git push origin feature/AwesomeFeature`)  
5. Open a Pull Request — feedback is welcome!

---



## 👋 Author

**ManuMay** – Full-stack Web Developer  
GitHub: [@manumay1962](https://github.com/manumay1962)

---

> Build simple, beautiful tools — keep your records on track!  
