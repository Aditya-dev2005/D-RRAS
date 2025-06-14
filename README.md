🚨 D-RRAS: Disaster Relief & Resource Allocation System

A C++-based simulation platform for managing real-time disaster relief operations using advanced data structures and algorithms. This project models backend logic for dynamic rescue routing, roadblock-aware navigation, resource optimization, multilingual alerting, and volunteer coordination — built entirely around core DSA principles.

📌 Full Feature Set

⚙️ Algorithmic Core

✅ Priority Queue (Heap) for managing rescue requests by severity and timestamp.

📍 Dijkstra's Algorithm for calculating shortest, safest evacuation routes.

🎯 Dynamic Programming (0/1 Knapsack) for resource allocation under capacity constraints.

⚡ Greedy Allocation for volunteer-task matching based on skill and proximity.

⛔ Road Block Handling with real-time graph edge updates and re-routing.

🧠 Simulated AI Priority Scoring for determining request urgency dynamically.

🛠️ Functional Modules

🚨 Rescue Dispatch System – Prioritizes and dispatches aid requests intelligently.

🧑‍🚒 Volunteer Management System – Register, view, and match volunteers with location & skills. Data is persistently saved.

🌍 Multilingual Support – Interface available in 🇬🇧 English, 🇫🇷 French, and 🇪🇸 Spanish.

🧭 Predictive Evacuation Routing – Calculates safest exit routes while avoiding blocked roads.

🚧 Dynamic Road Blocking System – Allows user to block/unblock roads, automatically updating routing.

🔔 Real-Time Disaster Alerts – Displays alerts in disaster-prone regions based on request/load intensity.

🌡️ Resource Demand Heatmap (Simulated) – Displays cities with high demand using request clustering.

📞 Helpline Directory – Lists emergency contact numbers for user assistance.

🧰 Precautionary & Medical Tips – Displays first aid and safety instructions.

💾 File Persistence Layer – Stores all requests, volunteer data, and logs in structured text files.

🧠 Tech Stack & Concepts

Language: C++ (OOP, File Handling, STL)

Data Structures: Graphs, Heaps, Queues, Hash Maps, Sets

Algorithms: Dijkstra’s, Priority Queue, Greedy Matching, Dynamic Programming

Design Principles: Modularized Classes, Encapsulation, System Simulation

Interface: Terminal/CLI (Cross-platform)

🖼️ Screenshots

A full folder of screenshots (/screenshots) is included to visually represent:

Multilingual menus

Volunteer management

Routing with roadblocks

Disaster alerts

Resource heatmaps

🔍 Why This Project Stands Out

D-RRAS was built to simulate backend intelligence systems found in logistics hubs, rescue centers, and emergency dispatch systems. Focused entirely on algorithmic efficiency, it showcases problem-solving, DSA fluency, and real-world modeling — critical to SDE and AMTS roles.

With zero reliance on front-end tools, it instead highlights core coding logic, data structure expertise, and system-level design thinking.

🧾 How to Compile & Run

g++ -o drras drras_more_enhanced.cpp
./drras

👨‍💻 Author

Aditya Chaturvedi
Jaypee Institute of Information Technology
GitHub: @Aditya-dev2005

