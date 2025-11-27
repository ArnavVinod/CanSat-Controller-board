# CanSat-Controller-board
This repository has the design descriptions for the CanSat payload PCB design for INSPACe Model Rocketry 2025.
The board connects I2C based MPU6050, BMP180, a DHT11 sensor to an Arduino nano which is also connected to an L293D motor driver for controlling motors (intended for a gyroscope in the CanSat).
On board telemetry module -> LoRa SX1278 (433 MHz) 
Custom KiCad PCB Footprint files available in profile.

PCB also houses a Muon detector experiment circuit using the LT1807 OpAmp, Onsemi SIPM.
Experiment inspiration and credit: Dr. Spencer Axani(https://github.com/spenceraxani/CosmicWatch-Desktop-Muon-Detector-v2)
