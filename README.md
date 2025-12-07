🚀 Advanced Disk Scheduling Simulator

A modern, interactive, browser-based simulator that visualizes the working of disk scheduling algorithms used in Operating Systems.
This tool helps users input their own disk access requests, simulate multiple algorithms in real time, and compare performance with detailed charts and metrics.

Understand how head movement works, see seek-time differences, and explore algorithm behavior — all in one elegant dashboard. 🎯📀

🌟 Overview

The Advanced Disk Scheduling Simulator provides a clean, high-clarity interface to experiment with algorithms like FCFS, SSTF, SCAN, and C-SCAN.

Users can enter any request queue, set an initial head position, choose a direction (for SCAN/C-SCAN), and watch the algorithm compute head movement dynamically with graphical visualization using Chart.js.

The simulator also calculates and displays important performance metrics, helping learners understand efficiency and tradeoffs.

🔍 Key Features
✅ Interactive Input Configuration

Easily customize disk environment:

Enter disk requests (comma-separated)

Set initial head position

Define maximum cylinder value

Choose direction → Left / Right

Pick algorithms via checkboxes
✔ FCFS
✔ SSTF
✔ SCAN
✔ C-SCAN

Built-in validation ensures safe and clean inputs.

📈 Real-Time Head Movement Visualization

Using Chart.js, the simulator generates a live graph showing:

Disk head movement step-by-step

Color-coded paths for each algorithm

Real-time chart updates

Smooth line transitions

Scalable axes

The graph helps in comparing algorithm behavior visually.

📋 Performance Metrics Dashboard

A dynamic table calculates and displays:

Metric	Description
Total Seek Time	Total movement of disk head
Average Seek Time	Efficiency indicator
Throughput	Requests serviced per movement
Order of Execution	Request sequence followed

Each algorithm produces its own row with full details.

🎛 Algorithm Engine

The JavaScript backend includes fully implemented algorithms:

🔹 FCFS

Processes requests in the order they arrive.

🔹 SSTF

Always picks the request closest to the head — minimizes movement.

🔹 SCAN

Moves in a direction, servicing requests, hits the end, then reverses.

🔹 C-SCAN

Moves in one direction, jumps to the start, and continues in same direction.

The simulator handles:

Path generation

Order calculation

Seek time math

Direction logic

Left/right track sorting

🌙 Dark Mode Support

A single toggle button switches the entire simulator between Light Mode and Dark Mode, with:

Smooth color transitions

Theme-aware charts and tables

Auto-updating UI elements

The dark theme uses polished, OS-grade styles.

⚙️ Core Technologies Used

HTML5 — Structure

CSS3 — Modern UI, dark mode, responsive layout

JavaScript (ES6) — Algorithm logic + dynamic updates

Chart.js — Disk head movement graph

Flex/Grid Layout — Clean and responsive design

📁 Project Structure
📦 Advanced Disk Scheduling Simulator
 ┣ 📄 index.html        → Main UI + JS logic
 ┣ 📄 styles            → Inline CSS (dark mode + UI)
 ┣ 📄 chart.js CDN      → Graph library
 ┗ 📄 README.md         → Documentation

🧪 How the Simulator Works
1️⃣ User inputs:

Cylinder requests

Initial head position

Max cylinder

Algorithm(s)

2️⃣ Simulator processes inputs

Algorithms compute:

Head path

Seek sequence

Total movement

3️⃣ Chart.js renders movement graph

Each algorithm is displayed in a different color.

4️⃣ Metrics table updates

Shows:

Seek time

Average seek

Throughput

Request order

🚧 Future Enhancements

🔹 Add LOOK & C-LOOK algorithms
🔹 Add animations for head movement
🔹 Export graph as PNG
🔹 Add CSV import/export
🔹 Add detailed timeline logs
🔹 Add comparison mode with multiple charts
