# 👾 Timemaru | タイムマル

<p align="center">
  <img src="https://img.shields.io/badge/Manifest-V3-purple?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Manifest V3" />
  <img src="https://img.shields.io/badge/JavaScript-Vanilla-yellow?style=for-the-badge&logo=javascript&logoColor=black" alt="Vanilla JS" />
  <img src="https://img.shields.io/badge/HTML5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5" />
  <img src="https://img.shields.io/badge/CSS3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3" />
</p>

---

`timemaru` is an interactive browser extension designed as a proof-of-concept for Manifest V3. It elegantly marries standard productivity tools—like schedules, tasks, and weather forecasting—with a charming, screen-roaming pixel art demon companion that reacts dynamically to webpage elements and user actions.

---

## 🔮 Core Features

Timemaru is split into two primary modules: the **Sidebar Panel** (for productivity) and the **Floating Companion** (for interactive fun and quick actions).

### 🎛️ Sidebar Panel
The central control hub for your productivity, opened easily by clicking the extension icon or clicking your floating companion.
* **📅 Today's Summary** – Get an at-a-glance view of your schedule and most urgent tasks for the day.
* **✅ To-Do List** – A clean, straightforward task manager equipped with due date tracking.
* **🗓️ Weekly Schedule** – Plan and visualize your entire week in a cohesive layout.
* **☀️ Weather Widget** – Real-time weather forecasting based on your designated location.
* **⚙️ Settings** – Personalize your demon companion's name and set your local city.
* **😈 Unleash a Demon** – Need more company? Spawn additional floating demons directly from the sidebar.

### 😈 Floating Companion (The Demon)
A pixel art companion that lives, roams, and interacts with the pages you browse.
* **🖱️ Interactive** – Click your demon companion to watch it bounce or to quickly toggle open the productivity sidebar.
* **🖐️ Draggable** – Drag and drop the demon anywhere across your active browser viewport.
* **🍴 Predator Mode** – Unleash multiple demons and watch them interact: older demons will consume newer ones, increasing in scale.
* **🖼️ Image Hunter** – When feeling hungry, the demon will slowly crawl towards nearby images on the web page.
* **❌ Banishment** – Right-click any demon companion to instantly banish them from the viewport.

---

## 💻 Tech Stack

- **Extension Architecture:** Manifest V3
- **Frontend & Styling:** HTML5 & CSS3 (featuring custom CSS Variables for themes and animations)
- **Logic & Interactions:** Vanilla JavaScript (ES6+) — pure browser performance without heavy external frameworks.

---

## 🚀 Installation & Sideloading

Since Timemaru is a developer proof-of-concept, it is loaded manually. Follow these quick steps to set it up:

1. **Download the Repository:** Clone this repository or download and extract the repository ZIP/RAR contents.
2. **Access Extension Management:** Navigate to the extensions page in your browser of choice:
   - **Chrome:** `chrome://extensions`
   - **Edge:** `edge://extensions`
   - **Brave:** `brave://extensions`
3. **Toggle Developer Mode:** Enable the **Developer mode** switch (typically located in the top-right corner).
4. **Load Unpacked:** Click **Load unpacked** and select the main `timemaru-extension` folder containing the unzipped files.
5. **Begin:** Pin the purple demon icon to your toolbar and watch your companion appear!

---

## 🛠️ How to Use

- **Toggle Sidebar:** Left-click the extension icon in your toolbar, or left-click any floating demon.
- **Manage Tasks:** Open the *To-Do List*, input your task and optional due date, and click **Add**.
- **Configure Weather:** Open *Settings*, input your city (e.g., `"Jakarta"`), and click **Save** to enable the weather widget.
- **Demon Actions:**
  - **Drag:** Hold left-click and move your mouse.
  - **Banish:** Right-click the demon.
  - **Multiply:** Click **Unleash a Demon** in the sidebar.

---

## 🇮🇩 (Bahasa Indonesia) Tentang Timemaru

Timemaru adalah ekstensi browser yang menggabungkan alat produktivitas harian Anda (jadwal, daftar tugas, cuaca) dengan teman virtual berupa iblis pixel art yang interaktif dan melayang di setiap halaman web.

### Cara Pemasangan:
Ikuti langkah-langkah pada bagian **Installation** di atas. Cukup muat folder ekstensi melalui halaman "Mode Pengembang" di browser Anda.

---

## 👨‍💻 Developer & Credits

Lovingly crafted by **Muqorrobin** ([@mqrbxn](https://github.com/mqrbxn) / [@beenspace](https://github.com/beenspace)).
