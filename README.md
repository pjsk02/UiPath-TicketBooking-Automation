# 🎤 Voice-Based Ticket Booking Automation with UiPath 🤖  
_A smart RPA system to book tickets using voice recognition, Python, and UiPath_

---

## 📌 Project Overview

This project demonstrates an **automated ticket booking system** using **voice commands** as input and built using **UiPath**, **Python**, and **speech recognition APIs**. It extracts ticket data from multiple travel websites and books the cheapest available option for the user with zero manual interaction.

Developed as part of the **Robotic Process Automation (RPA)** course in undergraduate studies.

---

## 🔧 Tech Stack

| Area                | Tools/Technologies                    |
|---------------------|----------------------------------------|
| RPA Platform        | UiPath                                |
| Voice Recognition   | Python (`SpeechRecognition`, `pyttsx3`)|
| Web Automation      | UiPath: `Click`, `Type Into`, `Open Browser`, `Data Scraping` |
| Data Storage        | Excel (via UiPath and Python)         |
| Analysis Module     | Python (`Pandas`, `NumPy`)            |
| Travel Sites Used   | MakeMyTrip, Goibibo, EaseMyTrip       |

---

## 🧠 Modules Implemented

### 🎤 Speech Input Module (Python)
- Takes **voice input** for Source, Destination, Travel Date, and Class
- Converts voice to text and saves it to Excel for UiPath to use

### 🌐 Website Automation (UiPath)
- Opens browser to **MakeMyTrip**, **Goibibo**, etc.
- Enters inputs via `Type Into` & `Click`
- Searches flights and trains and captures results

### 📊 Data Extraction Module
- Extracts:
  - Flights: Name, Departure/Arrival Time, Price
  - Trains: Train Number, Duration, Price
- Saves data into structured Excel format

### 📉 Data Analyser Module
- Reads all extracted prices from Excel
- Compares options and selects the **top 3 cheapest** modes of travel

---

## ✅ Key Features

- 🎙️ Full voice-to-ticket automation  
- 💬 Multi-modal input: speech → Excel → UiPath  
- 🧠 Smart selection of cheapest ticket via data analysis  
- 🌐 Multi-website scraping for better coverage  
- 📨 Email-enabled output (future scope)  

---

## 🚀 How to Run

```bash
1. Run the Python voice module
   - python voice_input.py
   - Output stored in input_data.xlsx

2. Open UiPath Studio
   - Load main workflow
   - It reads input_data.xlsx and starts automation

3. Website automation + data extraction
   - Bot fills in details and scrapes ticket prices

4. Data analysis (Python)
   - python analyze_prices.py
   - Displays cheapest travel options
# 🎤 Voice-Based Ticket Booking Automation with UiPath 🤖  
_A smart RPA system to book tickets using voice recognition, Python, and UiPath_
```
---

## 📌 Project Overview

This project demonstrates an **automated ticket booking system** using **voice commands** as input and built using **UiPath**, **Python**, and **speech recognition APIs**. It extracts ticket data from multiple travel websites and books the cheapest available option for the user with zero manual interaction.

Developed as part of the **Robotic Process Automation (RPA)** course in undergraduate studies.

---

## 🔧 Tech Stack

| Area                | Tools/Technologies                    |
|---------------------|----------------------------------------|
| RPA Platform        | UiPath                                |
| Voice Recognition   | Python (`SpeechRecognition`, `pyttsx3`)|
| Web Automation      | UiPath: `Click`, `Type Into`, `Open Browser`, `Data Scraping` |
| Data Storage        | Excel (via UiPath and Python)         |
| Analysis Module     | Python (`Pandas`, `NumPy`)            |
| Travel Sites Used   | MakeMyTrip, Goibibo, EaseMyTrip       |

---

## 🧠 Modules Implemented

### 🎤 Speech Input Module (Python)
- Takes **voice input** for Source, Destination, Travel Date, and Class
- Converts voice to text and saves it to Excel for UiPath to use

### 🌐 Website Automation (UiPath)
- Opens browser to **MakeMyTrip**, **Goibibo**, etc.
- Enters inputs via `Type Into` & `Click`
- Searches flights and trains and captures results

### 📊 Data Extraction Module
- Extracts:
  - Flights: Name, Departure/Arrival Time, Price
  - Trains: Train Number, Duration, Price
- Saves data into structured Excel format

### 📉 Data Analyser Module
- Reads all extracted prices from Excel
- Compares options and selects the **top 3 cheapest** modes of travel

---

## ✅ Key Features

- 🎙️ Full voice-to-ticket automation  
- 💬 Multi-modal input: speech → Excel → UiPath  
- 🧠 Smart selection of cheapest ticket via data analysis  
- 🌐 Multi-website scraping for better coverage  
- 📨 Email-enabled output (future scope)  

---

## 🚀 How to Run

```bash
1. Run the Python voice module
   - python voice_input.py
   - Output stored in input_data.xlsx

2. Open UiPath Studio
   - Load main workflow
   - It reads input_data.xlsx and starts automation

3. Website automation + data extraction
   - Bot fills in details and scrapes ticket prices

4. Data analysis (Python)
   - python analyze_prices.py
   - Displays cheapest travel options
```

## 💡 What I Learned

- 🤖 Building real-world RPA workflows using UiPath  
- 🧠 Integrating AI (voice) with RPA tools  
- 🌐 Web automation and scraping travel portals  
- 📊 Using dataframes for price comparison  
- 🗣️ Python voice APIs + Excel-based integration  

---

## 🔮 Future Enhancements

- ✈️ Suggest flights with lower cancellation penalties  
- ⭐ Include customer review-based recommendations  
- 📩 Email automation for ticket delivery  
- 💬 Real-time chatbot UI for travel queries  

---

## 📚 References

- [Speech-to-Text in Python](https://www.geeksforgeeks.org/python-convert-speech-to-text-and-text-to-speech/)  
- [MakeMyTrip](https://www.makemytrip.com/flights/)  
- [Goibibo](https://www.goibibo.com/flights/)  
- [EaseMyTrip](https://www.easemytrip.com/flights.html)  

---

📬 Let’s connect on [LinkedIn](https://www.linkedin.com/in/je-pulipati/)
