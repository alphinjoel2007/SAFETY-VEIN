SAFETY-VEIN is an AI-powered underground mine safety, monitoring, and rescue system designed to protect workers in hazardous mining environments. The system continuously monitors environmental and physiological parameters and provides real-time alerts to prevent accidents.

## Key Features
- Real-time gas monitoring (CO, Methane)
- Temperature and humidity tracking
- Worker health monitoring (Heart Rate, SpO2)
- Motion detection using accelerometer
- AI-based risk classification (Normal / Caution / Critical)
- Automated alert system

## Technology Stack
- ESP32 (Data Collection)
- Sensors (Gas, Temperature, Pulse, SpO2)
- Edge Impulse (AI Model)
- Python (Data Processing)
- FPGA (VLSI-based control system)

## Working
1. Sensors collect real-time data from the environment
2. Data is processed and sent to Edge Impulse model
3. AI model classifies conditions:
   - Normal
   - Caution
   - Critical
4. Alerts are triggered based on risk level

## Dataset
The dataset includes:
- CO concentration (ppm)
- Methane levels (ppm)
- Temperature (°C)
- Humidity (%)
- Accelerometer (X, Y, Z)
- Heart Rate (BPM)
- SpO2 (%)

## Applications
- Underground mining safety
- Industrial hazard monitoring
- Worker health tracking
- SAFETY-VEIN is an AI-powered underground mine safety, monitoring, and rescue system designed to protect workers in hazardous mining environments. The system continuously monitors environmental and physiological parameters and provides real-time alerts to prevent accidents.

## Key Features
- Real-time gas monitoring (CO, Methane)
- Temperature and humidity tracking
- Worker health monitoring (Heart Rate, SpO2)
- Motion detection using accelerometer
- AI-based risk classification (Normal / Caution / Critical)
- Automated alert system

## Technology Stack
- ESP32 (Data Collection)
- Sensors (Gas, Temperature, Pulse, SpO2)
- Edge Impulse (AI Model)
- Python (Data Processing)
- FPGA (VLSI-based control system)

## Working
1. Sensors collect real-time data from the environment
2. Data is processed and sent to Edge Impulse model
3. AI model classifies conditions:
   - Normal
   - Caution
   - Critical
4. Alerts are triggered based on risk level

## Dataset
The dataset includes:
- CO concentration (ppm)
- Methane levels (ppm)
- Temperature (°C)
- Humidity (%)
- Accelerometer (X, Y, Z)
- Heart Rate (BPM)
- SpO2 (%)

## Applications
- Underground mining safety
- Industrial hazard monitoring
- Worker health tracking

## Future Scope
- Integration with IoT dashboards
- GPS-based worker tracking
- Automated rescue system
- Mobile app alerts

 # System Architecture

Sensors → ESP32 → AI Model → Output → Alert System

- Sensors collect environmental and health data
- ESP32 processes and sends data
- AI model classifies risk level
- System generates alerts based on condition
- 
