# NeuroBalance 🧠⚖️


> **A gamified Parkinson's disease assessment platform that transforms clinical eye coordination testing into an engaging, interactive experience.**

NeuroBalance leverages real-time eye-tracking technology to monitor patient reflexes and coordination through a Pong-style game, providing healthcare professionals with quantified insights into neurodegeneration progression.

## 🎯 Problem Statement

Parkinson's disease causes inevitable loss of eye coordination due to impaired cerebrospinal fluid (CSF) circulation and neurodegeneration. Traditional assessment methods are often:
- Clinical and non-engaging for patients
- Difficult to track progression over time
- Lacking in quantifiable, real-time metrics

**NeuroBalance** transforms this assessment into an interactive balance training game that both evaluates and helps improve motor control.

## ✨ Features

- **👁️ Real-Time Eye Tracking**: WebGazer library integration for precise gaze detection
- **🎮 Interactive Gameplay**: Classic Pong game controlled entirely by eye movements
- **📊 Clinical Severity Scoring**: Automated assessment based on three key metrics:
  - **Latency**: Response time between eye movement and paddle movement
  - **Drift**: Stability of gaze fixation
  - **Accuracy**: Precision of eye-controlled paddle movements
- **🚦 Three-Tier Assessment System**:
  - 🟢 **Green**: Low severity - Vision functioning normally
  - 🟡 **Yellow**: Medium severity - Notable coordination decline
  - 🔴 **Red**: High severity - Significant impairment detected
- **📈 Progression Tracking**: Historical data for monitoring changes over time

## 🛠️ Tech Stack

### Frontend
- **React** - UI framework
- **TypeScript** - Type-safe development
- **WebGazer.js** - Eye-tracking library

### Backend
- **Flask** - Python web framework
- **Python** - Data processing and API logic

## 🚀 Getting Started

### Prerequisites
- Node.js (v18+)
- Python (v3.9+)
- Webcam (for eye tracking)

### Installation

1. **Clone the repository**
```bash
git clone https://github.com/yourusername/neurobalance.git
cd neurobalance
```

2. **Install frontend dependencies**
```bash
cd frontend
npm install
```

3. **Install backend dependencies**
```bash
cd ../backend
pip install -r requirements.txt
```

### Running the Application

1. **Start the Flask backend**
```bash
cd backend
python app.py
```
The API will run on `http://localhost:5000`

2. **Start the React frontend**
```bash
cd frontend
npm start
```
The app will open at `http://localhost:3000`

3. **Allow webcam access** when prompted and follow the calibration instructions

## 🎮 How to Use

1. **Calibration**: Follow the on-screen prompts to calibrate eye tracking
2. **Play**: Control the paddle using only your eye movements
3. **Assessment**: Complete the game session (typically 2-3 minutes)
4. **Results**: View your severity score and detailed metrics breakdown

## 📊 Metrics Explanation

| Metric | Description | Impact |
|--------|-------------|--------|
| **Latency** | Time delay between gaze shift and paddle response | Higher latency indicates slower neural processing |
| **Drift** | Involuntary eye movement and fixation instability | Increased drift suggests declining motor control |
| **Accuracy** | Precision of eye-controlled movements | Lower accuracy correlates with coordination loss |

## 🏆 Awards

**3rd Place - HackAMind 2025**  
Recognized for innovative approach to neurological health assessment and patient engagement.

## 🎥 Demo

[Watch Demo Video](https://youtu.be/ZqUpHCXDKHU?si=L52hCmnFFWahEJM9)

## 📝 Future Enhancements

- [ ] Multi-patient dashboard for healthcare providers
- [ ] Historical trend analysis and visualization
- [ ] Integration with electronic health records (EHR)
- [ ] Mobile app version for at-home assessments
- [ ] Additional games for varied assessment scenarios
- [ ] Machine learning model for predictive progression analysis

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👥 Team

**Suhaan Temkar** - Lead Developer  
[GitHub](https://github.com/yourusername) | [LinkedIn](https://linkedin.com/in/yourprofile)

## 🙏 Acknowledgments

- WebGazer.js team for the eye-tracking library
- HackAMind 2025 organizers
- Medical professionals who provided consultation on Parkinson's assessment

---

**Made with ❤️ at HackAMind 2025**
