# 🛒 Firebase Shopping List

A simple and interactive **shopping list web app** built using **HTML, CSS, and JavaScript**, powered by **Firebase Realtime Database**.  
It lets users add, view, and delete items from their list with **real-time updates** — no page refresh needed.

---

## 🚀 Features

- 📝 Add items instantly  
- ⚡ Real-time data sync using Firebase  
- 🗑️ Delete items by clicking on them  
- 💾 Data stored securely in the cloud  
- 💡 Clean and minimal UI  

---

## 🧠 How It Works

1. Type an item (e.g., “Milk”) and click **Add to cart**.  
2. The item is sent to Firebase Realtime Database.  
3. The app uses Firebase’s `onValue()` to automatically update the list whenever data changes.  
4. Clicking on any item deletes it from the database instantly.

---

## 🛠️ Tech Stack

- **HTML** – Structure  
- **CSS** – Styling  
- **JavaScript (ES Modules)** – Logic and Firebase integration  
- **Firebase Realtime Database** – Live data sync  

---

## ⚙️ Setup and Usage

1. **Clone the repo**

   Open the project

cd firebase-shopping-list


Add your Firebase Realtime Database URL

Go to your Firebase console → Realtime Database

Copy your database URL and replace this line in index.js:

const appSettings = {
    databaseURL: "your-database-url-here"
}


Run the project:-https://thriving-manatee-b3d254.netlify.app/

Simply open index.html in your browser 🚀
   ```bash
   git clone https://github.com/your-username/firebase-shopping-list.git

