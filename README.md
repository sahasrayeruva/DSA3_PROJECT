# Patent Prior Art & Litigation Analytics Engine

## About the Project

The Patent Prior Art & Litigation Analytics Engine is a web-based application developed as part of our DSA-3 course. It helps users search patent records using keywords and explore related patent information.

The project uses Data Structures and Algorithms to support searching, similarity analysis, graph traversal, and ranking of patent records.

## Technologies Used
- Python
- FastAPI
- HTML, CSS, JavaScript
- SQLite
- Uvicorn

## DSA Concepts
- Hash Maps
- Tries
- String Similarity
- Graphs (BFS and DFS)
- Priority Queues
- Set Cover
- Backtracking

## Features
- Keyword-based patent search
- Patent information storage and retrieval
- Basic patent statistics and analytics
- Patent similarity and relationship analysis modules

## How to Run

**1. Install dependencies**
```bash
pip install fastapi uvicorn
```

**2. Start the backend**
```bash
python -m uvicorn main:app --reload
```

**3. Start the frontend** (open another terminal)
```bash
cd frontend
python -m http.server 5500
```

Open the application at `http://localhost:5500`.

## Database

The project uses SQLite and currently contains 10,005 patent records, including 10,000 synthetically generated demonstration records and 5 original sample records.

## Team Members

- Mahathi Chekka – 2520080030
- Sahasra – 2520080062

## Academic Details

- **Course:** Data Structures and Algorithms–3
- **Course Code:** 25CS2103E
- **University:** K L (Deemed to be) University, Hyderabad
- **Academic Year:** 2026–2027

---

*Developed as an academic DSA-3 project*
