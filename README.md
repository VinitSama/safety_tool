
# Drowsiness - SeatBelt Detectition




The Drowsiness and Seat Belt Detection Safety System is an innovative project designed to enhance road safety using camera-based technology. This system employs advanced computer vision techniques to monitor the driver's alertness and seat belt compliance in real-time. By analyzing facial landmarks and eye movements, it can accurately detect signs of driver drowsiness, such as prolonged eye closure or head nodding. Simultaneously, the system uses image processing to verify whether the driver is wearing a seat belt. Integrated with an alert mechanism, the system promptly issues warnings if drowsiness or seat belt violations are detected, ensuring timely corrective actions. This cost-effective and user-friendly tool aims to reduce road accidents and improve adherence to safety regulations, making it a valuable addition to modern vehicular safety measures.


## Deployment
Before running the project, ensure that you have Python installed (preferably version 3.8 or higher). You'll also need to install required dependencies and set up a virtual environment for better package management.

1. Set Up a Virtual Environment (Optional but Recommended) To create a virtual environment, follow these steps:

```bash
# Install virtualenv if you don't have it
pip install virtualenv

# Create a virtual environment named 'venv'
virtualenv venv

# Activate the virtual environment (Windows)
.\venv\Scripts\activate
```

2. Install Required Packages
Once the virtual environment is activated, install the necessary packages listed in requirements.txt:
```bash
pip install -r requirements.txt
```
3. To run the seatbelt detection script, execute the following command:
```bash
python main.py
```