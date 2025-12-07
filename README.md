🚀 Advanced Disk Scheduling Simulator

A powerful and interactive disk scheduling simulator designed to visualize how operating systems handle disk access requests using popular scheduling algorithms.
This simulator allows users to input custom request queues, observe real-time head movements, and compare algorithm efficiency through detailed performance metrics.

Understand disk behavior, reduce seek time, and learn OS scheduling concepts — all in one intuitive simulator. 🎯📀

🌟 Overview

The Advanced Disk Scheduling Simulator provides a step-by-step, high-visibility view of disk head movements across tracks using algorithms like FCFS, SSTF, SCAN, C-SCAN, LOOK, and C-LOOK.

With real-time visualization, seek-time calculation, and track-by-track simulation, this project helps learners instantly understand how different scheduling approaches affect disk performance.

🔍 Key Features
✅ Interactive Disk Head Visualization

Track-by-track movement display

Animated seek sequence (optional)

Shows direction for SCAN/C-SCAN algorithms

Auto-updates simulation results

📊 Real-Time Algorithm Comparison

Visual charts (using Matplotlib / Chart.js):

📈 Total Seek Time
📈 Average Seek Time
📈 Head Movement Graph (per request)

Features:

Real-time simulation

Dynamic chart updates

Clean visualization of head path

Comparison mode for multiple algorithms

📋 Dynamic Input Controls

Users can customize:

Disk size

Initial head position

Sequence of disk access requests

Selected scheduling algorithm

Supported Algorithms

🔹 FCFS
🔹 SSTF
🔹 SCAN
🔹 C-SCAN
🔹 LOOK
🔹 C-LOOK

Each algorithm displays:

Seek order

Seek distance per move

Total + average seek time

⚙️ Algorithm Engine

Includes a robust scheduler with:

Priority-based selection

Head movement optimizer

Built-in validation checks

Track boundary control

🎛️ Actions & Filters
Simulation Controls

▶️ Start Simulation

🔁 Re-run with new inputs

📦 Compare Algorithms

✏️ Edit Request Queue

Visual Filters

Show / hide movement lines

Highlight nearest request (SSTF)

Reverse head direction (SCAN family)

🕒 Time Window View

Switch algorithm visualizations across:

5 requests

10 requests

Full queue

Custom window

Charts auto-adjust labels & axes based on the chosen view.

📁 Repository Structure
📦 Advanced-Disk-Scheduling-Simulator
 ┣ 📂 src
 ┃ ┣ algorithms/
 ┃ ┣ simulator/
 ┃ ┗ ui/
 ┣ 📂 assets
 ┣ 📄 README.md
 ┣ 📄 requirements.txt
 ┗ 📄 main.py / main.cpp

🧪 Performance Metrics

The simulator automatically computes:

Total head movement

Average seek time

Time complexity of each algorithm

Request servicing order

Direction trace (for SCAN/C-SCAN)

🎯 Use Cases

✔️ Operating Systems lab practice
✔️ Visual learning tool for DSA/OS concepts
✔️ Comparing algorithm efficiencies
✔️ Teaching tool for SCAN-based scheduling

⚒️ Tech Stack

Python / C++ / Java (your choice)

Matplotlib / Chart.js for visualization

Tkinter / Web UI (optional)

GitHub for version control

🚧 Future Enhancements

🔹 Add GUI-based dashboard
🔹 Add real disk I/O log import
🔹 Add more algorithms (e.g., N-Step-SCAN)
🔹 Add CSV export of seek logs
🔹 Add animation mode with speed control
