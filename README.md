# AI-ML-PROJECT
# 👨‍💻 About Me

Hello! My name is **Shashwat Mishra**, and I am a **B.Tech student at VIT Bhopal University**, currently in my **2nd semester** pursuing a degree in **Computer Science / CORE Branch**.

I have a strong interest in **Artificial Intelligence and Machine Learning**, and I enjoy building projects that apply theoretical concepts to real-world problems. This project is part of my **Bring Your Own Project (BYOP)** for the *Fundamentals of AI/ML* course.

Through this project, I have explored how search algorithms like **A\*** can be used to solve pathfinding and optimization problems efficiently.

---

# A* Pathfinding Algorithm (Graph-Based)

## 📌 Project Overview
This project implements the **A\* (A-star) search algorithm**, a fundamental concept in Artificial Intelligence used for finding the shortest path between nodes in a graph.

The algorithm combines actual path cost and heuristic estimates to efficiently determine the optimal path.

---

## 🎯 Objective
The objective of this project is to:
- Find the shortest path in a weighted graph
- Demonstrate heuristic-based search
- Apply AI search algorithms learned in the course

---

## 🧠 Key Concepts Used
- A* Search Algorithm  
- Heuristic Function  
- Graph Representation  
- Priority Queue (Min Heap)  
- Cost Functions:
  - g(n): Cost from start to current node  
  - h(n): Estimated cost to goal  
  - f(n) = g(n) + h(n)  

---

## 🛠️ Technologies Used
- Python 3  
- heapq module (for priority queue)

---

## 📂 Project Structure
project-folder/
│── main.py
│── README.md

## ▶️ How to Run the Project

1. Install Python 3  
2. Save the code in a file named main.py  
3. Run the program: python main.py


## 📊 Sample Input

### Graph

A → B (1), C (3)
B → D (1), E (5)
C → F (2)
D → G (1)
E → G (2)
F → G (1)


### Heuristic Values

A: 7
B: 6
C: 4
D: 3
E: 2
F: 1
G: 0


- Start Node: A  
- Goal Node: G  

---

## ✅ Sample Output

Shortest Path: ['A', 'B', 'D', 'G']


---

## ⚙️ How It Works
1. Start from the initial node  
2. Evaluate nodes using f(n) = g(n) + h(n)  
3. Use a priority queue to select the best node  
4. Track the path using a parent map  
5. Stop when the goal node is reached  

---

## 🌍 Applications of A*
- Navigation systems (Google Maps)  
- Game development (pathfinding)  
- Robotics  
- Network routing


## ⚠️ Limitations
- Requires a good heuristic function  
- Performance depends on heuristic accuracy  

---

## 🚀 Future Enhancements
- Add graphical visualization  
- Convert to grid-based pathfinding  
- Take dynamic user input  
- Compare with BFS and DFS  

---

## 📚 Learning Outcomes
- Learned A* search algorithm  
- Understood heuristic-based optimization  
- Implemented priority queues  
- Applied AI concepts to real-world problems  

---

## 👨‍💻 Author
*Shashwat Mishra*  
B.Tech Student, VIT Bhopal University
