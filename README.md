🚚 Supply Chain Fixer

An Interactive Supply Chain Resilience & Recovery Simulation Platform

Supply Chain Fixer is an interactive web-based demo platform that simulates the flow of goods through a four-stage supply chain. The system demonstrates how disruptions such as delays, shortages, and equipment failures impact operations and how an intelligent Fixer Agent automatically responds to restore performance.

The project is designed for learning, demonstrations, academic presentations, and understanding supply chain resilience through an easy-to-use visual interface.

📌 Project Overview

The application models a simplified supply chain consisting of four major stages:

🏭 Supplier
⚙️ Manufacturer
🚚 Distributor
🛒 Retailer

Users can simulate daily operations, intentionally create disruptions, or allow random disruptions to occur. Whenever problems arise, the Fixer Agent analyzes the situation and applies recovery actions to maintain service levels.

The platform also provides real-time performance metrics, historical records, and an AI-style assistant to explain system behavior.

🎯 Objectives

The primary objectives of this project are:

Demonstrate how disruptions affect supply chain operations.
Visualize inventory movement across all supply chain stages.
Show automated recovery through an intelligent Fixer Agent.
Display service level improvements after corrective actions.
Provide an educational tool for students, faculty, and business demonstrations.
Simplify supply chain resilience concepts using an interactive simulation.
✨ Features
📊 Live Control Room
Real-time supply chain dashboard
Interactive monitoring interface
Visual representation of all supply chain stages
🏭 Four-Stage Supply Chain Simulation

The simulation includes:

Supplier
Manufacturer
Distributor
Retailer

Each stage processes inventory independently while maintaining the overall supply flow.

⚠️ Manual Disruption Triggers

Users can manually introduce disruptions such as:

Supplier delay
Manufacturing breakdown
Distribution delay
Retail stock shortage
🎲 Automatic Random Disruptions

The simulator can automatically generate unexpected events to mimic real-world uncertainty.

Examples include:

Transportation delays
Production failures
Inventory shortages
Demand spikes
🤖 Intelligent Fixer Agent

The Fixer Agent continuously monitors the system and performs corrective actions such as:

Restoring delayed shipments
Recovering inventory flow
Resolving production issues
Improving service level
Reducing stockouts
📝 Event Log

Every activity is recorded in chronological order.

The log includes:

Daily operations
Disruptions
Recovery actions
Service improvements
📈 Performance Chart

The application visualizes:

Service Level over time
Recovery progress
Overall system performance
📊 KPI Dashboard

Key Performance Indicators include:

📅 Current Day
📈 Service Level
🛠️ Fixes Applied
📦 Stockouts

These metrics update dynamically during the simulation.

💾 Save & History

Users can:

Save completed simulation runs
Review previous simulations
Compare historical performance
🔐 Login Screen

A simple login interface is provided for demonstration purposes before accessing the dashboard.

🤖 AI Assistant

An integrated AI-style assistant helps users understand:

Current simulation status
Supply chain events
Recovery actions
Performance metrics
🏗️ System Architecture
                    +----------------------+
                    |      Login Page      |
                    +----------+-----------+
                               |
                               v
                  +--------------------------+
                  |   Supply Chain Dashboard |
                  +-----------+--------------+
                              |
        -------------------------------------------------
        |          |             |              |
        v          v             v              v
   Supplier   Manufacturer   Distributor   Retailer
        |          |             |              |
        -------------------------------
                      |
                      v
              Disruption Engine
                      |
                      v
                Fixer Agent Logic
                      |
          -----------------------------
          |             |             |
          v             v             v
      KPI Cards    Event Log    Performance Chart
                      |
                      v
               History & Save System
                      |
                      v
                 AI Assistant Chat
🛠️ Technology Stack
Technology	Purpose
HTML5	Structure
CSS3	Styling
JavaScript (Vanilla)	Application Logic
Local Storage	Save Simulation History
Chart.js (Optional)	Performance Visualization
📂 Project Structure
Supply-Chain-Fixer/
│
├── index.html
├── style.css
├── script.js
├── README.md
│
├── assets/
│   ├── images/
│   ├── icons/
│   └── screenshots/
│
└── data/
    └── simulation-history.json (optional)
🚀 How to Run
Clone the repository
git clone https://github.com/yourusername/supply-chain-fixer.git
Open the project folder.
Launch index.html in any modern web browser.
Log in using the demo credentials (if enabled).
Start the simulation.
Trigger disruptions manually or wait for random events.
Observe how the Fixer Agent restores supply chain performance.
📊 Workflow
Start Simulation
        │
        ▼
Normal Supply Flow
        │
        ▼
Disruption Occurs
        │
        ▼
Fixer Agent Detects Issue
        │
        ▼
Recovery Action Applied
        │
        ▼
Service Level Improves
        │
        ▼
Performance Updated
        │
        ▼
Simulation History Saved
📈 Performance Metrics

The simulator tracks:

Service Level (%)
Number of Fixes Applied
Stockouts
Simulation Day
Recovery Success
Event History
🎓 Use Cases

This project is suitable for:

College Mini Projects
Final Year Projects
Supply Chain Demonstrations
Operations Management Learning
Logistics Training
Academic Presentations
Industry Concept Demonstrations
🔮 Future Enhancements

Possible future improvements include:

Multi-Agent AI Coordination
Predictive Demand Forecasting
Machine Learning-Based Recovery
Supplier Performance Analytics
Route Optimization
Warehouse Management Module
Real-Time Database Integration
User Authentication System
Cloud Deployment
Mobile Responsive Dashboard
🤝 Contributing

Contributions are welcome!

Fork the repository.
Create a new feature branch.
Commit your changes.
Push the branch.
Open a Pull Request.
📜 License

This project is intended for educational and demonstration purposes. You may modify and extend it for learning or academic use.

👨‍💻 Author

Lalithkumar N

B.Tech – Artificial Intelligence and Data Science

Passionate about AI, Full-Stack Development, and Supply Chain Innovation.
