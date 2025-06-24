
# 🖥️ CPU Scheduling Simulator

This project is a **web-based CPU Scheduling Simulator** that visually demonstrates how different CPU scheduling algorithms work using Gantt charts and interactive inputs.

---

## 📌 Features

- 🔁 **Multiple Algorithms Supported**
  - First-Come-First-Serve (FCFS)
  - Shortest Job First (SJF)
  - Round Robin (RR)
  - Priority Scheduling

- 📊 **Interactive Gantt Chart** Visualization  
- 🧠 **Dynamic Input Interface** for process burst time, arrival time, priority, and quantum  
- 📄 **Explanatory Pages** for theory and working of each algorithm  
- 🌐 Built using **HTML, CSS, JavaScript**, and **Bootstrap**

---

## 📂 Project Structure

```
cpu scheduling simulator/
│
├── index.html                → Main home page
├── about.html                → Project description
├── docs.html                 → Algorithm documentation
├── style.css                 → Global styles
│
├── backend/
│   ├── ganttcharts.html      → Gantt chart output
│   ├── css/                  → Custom and Bootstrap styles
│   └── js/                   → JavaScript logic for scheduling and UI
│
└── README.md                 → You are here!
```

---

## 🚀 How to Use

1. **Open `index.html`** in a web browser.
2. Choose a scheduling algorithm.
3. Enter process data (burst time, arrival time, etc.)
4. Click **Submit** to generate the Gantt chart.
5. View results including:
   - Gantt Chart
   - Average Waiting Time
   - Average Turnaround Time

---

## 📘 Educational Use

This project is perfect for:
- Computer Science students learning Operating Systems
- Teachers conducting CPU scheduling demonstrations
- Anyone who wants to understand scheduling algorithms visually

---

## 🛠️ Tech Stack

- HTML5
- CSS3 (Bootstrap based)
- JavaScript (vanilla)

---

## 📩 Contributing

Have a suggestion or found a bug? Feel free to fork the repo and submit a pull request!

---

## 📜 License

This project is released under the MIT License (if applicable). Feel free to use and modify for educational or personal use.
