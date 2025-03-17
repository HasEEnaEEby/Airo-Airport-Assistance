# ✈️ Flight Assistant Chatbot (RasaProject)

## 📖 Overview
The **Flight Assistant Chatbot** is an AI-powered assistant built with **Rasa** that helps users with flight-related queries, including:
- Checking flight status  
- Finding airline details  
- Providing gate & lounge information  
- Navigating inside the airport  
- Scanning QR codes for boarding passes  

The chatbot supports **voice interaction** and integrates **computer vision** for QR code scanning and navigation.

## 🛠️ Setup & Installation

### Clone the Repository**
```sh
git clone https://github.com/your-username/RasaProject.git
cd RasaProject

```sh

## Create & Activate the Virtual Environment
conda create --name rasa_env python=3.9
conda activate rasa_env

## Install Dependencies
pip install -r requirements.txt

## Train the Rasa Model
rasa train

## Start the Rasa Bot
rasa run

## Chat with the Bot
rasa shell

Features
🔹 Flight Information Retrieval
Check flight status and estimated arrival time.
Get airline-specific details.
🔹 Airport Navigation
Find gates, terminals, and lounges.
Get directions inside the airport.
🔹 QR Code Scanning
Scan boarding passes to retrieve flight details.
🔹 Voice Interaction
Enable real-time voice commands.

## Project Structure
<img width="695" alt="Screenshot 2025-03-17 at 20 00 34" src="https://github.com/user-attachments/assets/4dededf6-04ee-41f3-acf5-04a417a122fb" />
