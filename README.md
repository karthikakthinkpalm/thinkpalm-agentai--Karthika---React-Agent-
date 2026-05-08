# thinkpalm-agentai--Karthika---React-Agent-
# AI Powered Maritime Monitoring System

A real-time terminal-based maritime monitoring dashboard built using Python and the Rich library.

The system simulates vessel tracking, AI-based anomaly detection, live analytics, and operational monitoring for maritime intelligence applications.

---

# Features

- Real-time terminal dashboard
- Interactive vessel selection
- AI ReAct Agent simulation
- Fuel monitoring analytics
- Speed tracking
- Engine temperature monitoring
- Weather monitoring
- Critical alert system
- Multiple vessel support
- Fast optimized execution

---

# Technologies Used

- Python
- Rich Library
- Terminal UI Components
- AI ReAct Agent Logic

---

# Project Structure

```bash
.
├── src
│   ├── maritime_dashboard.py
│   └── screenshots
├── README.md
└── requirements.txt
```

---

# Installation

## Clone Repository

```bash
git clone <repository-url>
cd <repository-name>
```

---

# Install Dependencies

```bash
pip install -r requirements.txt
```

---

# Requirements

Add the following inside `requirements.txt`

```txt
rich
```

---

# Run the Application

```bash
python src/maritime_dashboard.py
```

---

# Available Vessels

- Oceanic-X
- Sea Serpent
- Titan Dawn

---

# How the System Works

1. User selects a vessel
2. Dashboard loads selected vessel data
3. Live metrics are updated dynamically
4. AI agent simulates reasoning steps
5. Alerts are generated for anomalies
6. User can select another vessel after completion

---

# Dashboard Components

## Vessel Radar
Displays:
- GPS connection
- Monitoring status
- Vessel tracking

## Live Vessel Status
Shows:
- Vessel name
- Location
- Speed
- Weather
- Engine status
- AI anomaly detection

## Analytics Panels
Visual monitoring for:
- Fuel consumption
- Speed analytics
- Engine temperature

## AI ReAct Logs
Simulates:
- Thought
- Action
- Observation
- Final Answer

## Alert Banner
Displays:
- Critical alerts
- Operational warnings
- System normal status

---

# Performance Optimization

The dashboard execution was optimized by reducing animation delay and iterations.

## Previous Configuration

```python
iterations=15
delay=1
```

Execution time:
- Approximately 15 seconds per vessel

---

## Optimized Configuration

```python
iterations=3
delay=0.2
```

Benefits:
- Faster dashboard execution
- Better user experience
- Reduced waiting time
- Near real-time interaction

---

# Example Usage

```text
Enter vessel name: Oceanic-X
→ Dashboard starts

Enter vessel name: Sea Serpent
→ Dashboard switches vessel

Enter vessel name: exit
→ Application closes
```

---

# Observations

- Rich library provides powerful terminal visualization capabilities.
- Lower animation delay significantly improves responsiveness.
- Modular dashboard functions improve maintainability.
- ReAct-style AI logs simulate intelligent monitoring workflows.
- Dynamic vessel monitoring enhances realism.

---

# Future Improvements

- Real-time API integration
- GPS tracking support
- Machine learning anomaly prediction
- Database connectivity
- Web dashboard version
- Multi-vessel simultaneous monitoring
- Authentication system

---

# Screenshots

Store screenshots inside:

```bash
src/screenshots
```

Suggested screenshots:
- Dashboard interface
- Vessel analytics
- AI alert system
- ReAct agent logs

---

# Author

Karthika
