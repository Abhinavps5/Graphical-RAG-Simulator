# Graphical-RAG-Simulator
A graphical tool to simulate resource allocation graphs and detect deadlocks
# Graphical Resource Allocation Graph (RAG) Simulator

## 📌 Project Overview
This project is a **Graphical Simulator for Resource Allocation Graphs (RAGs)** that helps visualize process-resource relationships. The tool can:
- Add and remove **processes and resources** dynamically.
- Simulate **resource allocation** and **release operations**.
- Detect **deadlocks** using cycle detection in the graph.
- Provide a **graphical representation** of the Resource Allocation Graph.

## 🛠 Features
✅ **Interactive GUI** to manage processes and resources.  
✅ **Graph Visualization** using `networkx` and `matplotlib`.  
✅ **Deadlock Detection** to identify cyclic dependencies.  
✅ **User-friendly controls** to allocate and release resources.  

## 📂 Project Structure
```
Graphical-RAG-Simulator/
│-- main.py          # Main application script
│-- README.md        # Project documentation
│-- requirements.txt # List of dependencies 
```

## 🚀 Installation & Usage
### 1️⃣ Install Dependencies
Ensure you have Python installed, then install the required libraries:
```bash
pip install networkx matplotlib tkinter
```

### 2️⃣ Run the Simulator
```bash
python main.py
```

### 3️⃣ Usage Instructions
- Enter **Process Name** and **Resource Name** in the input fields.
- Click **Allocate Resource** to create a dependency.
- Click **Release Resource** to remove a dependency.
- Click **Detect Deadlock** to check for cycles in the graph.
- Click **Show Graph** to visualize the current allocation graph.



## 🛠 Technologies Used
- **Python** (Core Language)
- **Tkinter** (GUI for user interaction)
- **NetworkX** (Graph visualization and analysis)
- **Matplotlib** (Rendering graphical output)

## 📌 GitHub Repository Setup
To clone and run the project from GitHub:
```bash
git clone https://github.com/Abhinavps5/Graphical-RAG-Simulator.git
cd Graphical-RAG-Simulator
python main.py
```

## 📜 License
This project is open-source and available under the **MIT License**.

---
💡 **Developed  by [Abhinav PS ,Y.V.Sai Yaswanth Reddy,M.Gnana Sai Reddy]**
