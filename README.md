
#  Queue_Manager

A Python-based simulation + Streamlit dashboard that models real-time queue management, crowd flow optimization, and intelligent scheduling using dynamic algorithms.

---

##  Features

###  Intelligent Queue Management
- Multiple service counters simulation
- Dynamic queue balancing
- VIP priority handling
- Emergency request injection

---

###  Scheduler System
- Smart customer assignment
- Global queue serving logic
- Real-time rebalance mechanism
- Load-aware distribution across counters

---

###  Simulation Engine
- Single customer arrival simulation
- Burst traffic simulation
- Initial customer seeding
- Realistic wait time tracking

---

###  Two Modes of Execution

#### 1. Streamlit Dashboard (UI Mode)
- Live visualization of queues
- Interactive control panel
- Real-time system status monitoring

#### 2. Headless CLI Mode
- Console-based simulation
- Step-by-step system execution
- Useful for debugging and learning DSA logic

---

##  Tech Stack

- Python
- Object-Oriented Programming (OOP)
- Queue Data Structures
- Scheduling Algorithms
- Streamlit (for UI)
- Subprocess (for app execution)

---

##  Project Structure

main.py          → Entry point (UI + CLI launcher)
queue_manager.py → Handles queue logic and counters
scheduler.py     → Smart scheduling and allocation system
simulation.py    → Customer arrival simulations
ui.py            → Streamlit dashboard (frontend)


##  System Workflow

1. System initializes multiple service counters  
2. Customers are seeded into queues  
3. Scheduler assigns customers intelligently  
4. System serves customers dynamically  
5. Queues are rebalanced automatically  
6. Burst & emergency cases handled in real-time  
7. Final system analytics are displayed  

---

##  Key Outputs

- Queue lengths per counter  
- Average wait times  
- Event logs (last 10 actions)  
- System mode (normal / peak)  
- Total active customers  

---

## Future Improvements

- AI-based prediction of peak hours  
- ML model for wait time optimization  
- Database integration (MongoDB / PostgreSQL)  
- Real-time API integration  
- Web deployment (Cloud hosting)  
- Advanced analytics dashboard  

---

##  Author

Rutuja Pardeshi  
Computer Engineering Student  

---

##  Project Goal

This project demonstrates:

- Real-world queue optimization systems  
- Dynamic scheduling algorithms  
- Simulation-based system design  
- Scalable architecture thinking  

---

