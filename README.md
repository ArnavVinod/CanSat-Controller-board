# CanSat-Controller-board
This repository has the design descriptions for the CanSat payload PCB design for INSPACe Model Rocketry 2025.

<img width="1383" height="847" alt="image" src="https://github.com/user-attachments/assets/0fb8e187-cb29-43e8-9282-3b741794cfa2" />

The board connects I2C based MPU6050, BMP180, a DHT11 sensor to an Arduino nano which is also connected to an L293D motor driver for controlling motors (intended for a gyroscope in the CanSat).


On board telemetry module -> LoRa SX1278 (433 MHz) 
Custom KiCad PCB Footprint files available in profile.

<img width="872" height="796" alt="image" src="https://github.com/user-attachments/assets/a3d97f78-effa-4cfe-ad90-7e831ad316ac" />

PCB also houses a Muon detector experiment circuit using the LT1807 OpAmp, Onsemi SIPM.
Experiment inspiration and credit: Dr. Spencer Axani(https://github.com/spenceraxani/CosmicWatch-Desktop-Muon-Detector-v2)

<img width="556" height="683" alt="Screenshot 2025-06-13 004054" src="https://github.com/user-attachments/assets/fbdf5260-704d-4c78-908d-cdf3fd398cd4" />
Fabrication credit: Elecrow PCB
