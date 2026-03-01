# 🌤️ Weather Agentic AI Workshop 🤖

This repository demonstrates an **Agentic AI** workflow for weather forecasting using Amazon Bedrock (Claude 4.5 Sonnet) and the National Weather Service (NWS) API. It provides both a command-line interface (CLI) and a web interface (Streamlit) to showcase how an AI agent can reason, plan, act, and process real-world data.

**Powered by Claude 4.5 Sonnet on Amazon Bedrock**


## 🎯 Features
- **🧠AI Planning:** Uses Claude 4.5 Sonnet to interpret user locations and generate appropriate NWS API calls.
- **🔗 Action:** Automatically fetches weather data from the NWS API.
- **📊 Processing:** Converts complex weather data into clear, human-readable summaries using AI.
- **💬 Interfaces:**
  - `weather_agent_cli.py`: Interactive CLI agent.
  - `weather_agent_web.py`: Interactive web app (Streamlit).

## 🧠How It Works
1. **User Input:** Enter a location (city, ZIP, state, or description).
2. **AI Planning:** Claude generates the correct NWS API endpoint.
3. **API Calls:** The agent fetches weather data from the NWS.
4. **AI Processing:** Claude summarizes the weather data.
5. **Results:** The forecast is displayed in a user-friendly format.

## 🏗️ Architecture Overview

User Input (Natural Language)  
        ↓  
Intent Parsing & Location Extraction  
        ↓  
Reasoning + Planning  
        ↓  
Weather API Invocation  
        ↓  
Data Processing & Response Synthesis  
        ↓  
Structured Forecast Output  

## 🧠 Key Capabilities

- Parses natural language weather queries
- Extracts location context from user input
- Autonomously decides when to call external Weather API
- Processes raw JSON payloads
- Returns clean, human-readable weather summaries
- Demonstrates reasoning → planning → action → response cycle

## 🛠️ Tech Stack

- Amazon Bedrock
- Claude Sonnet model
- Python
- REST API integration
- JSON parsing & data transformation

## 🔧 Setup
### Prerequisites
- Python 3.8+
- AWS credentials with access to Amazon Bedrock (for Claude)

### Installation
1. Clone the repository:
   ```sh
   git clone https://github.com/gauravbisht411/weather-ai-agent.git
   cd weather-ai-agent
   ```
2. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```

## Usage
### Command-Line Agent
Run the CLI agent:
```sh
python weather_agent_cli.py
```

### Web Agent (Streamlit)
Run the web app:
```sh
streamlit run weather_agent_web.py
```

## 💡 Example Queries
- Seattle
- 90210
- New York City
- Miami, FL
- National park near Homestead in Florida

## 🔬 Notes
- This demo uses official NWS data for educational purposes.
- Claude 4.5 Sonnet access via Amazon Bedrock is required.
<hr></hr>

# 🔬 About This Demo

### 🌤️ Weather Forecast
## **Weather Forecast for Everglades National Park Area, Homestead, Florida**
**Forecast Updated:** March 1, 2026 at 7:46 AM EST
<hr></hr>

## Today's Forecast (Sunday, March 1)
**High: 81°F (cooling to around 76°F in the afternoon)
Conditions: Mostly sunny with patchy fog early morning

⚠️ Weather Alert: Chance of showers and thunderstorms developing, particularly between 11 AM and evening. Some storms could produce heavy rain.

- **Precipitation Chance:** 40%
- **Expected Rainfall:** 0.5 to 0.75 inches possible
- **Wind:** Light northeast winds 2-8 mph
- **Morning:** Patchy fog before 9 AM

**Tonight:** Mostly cloudy with continued chance of showers and thunderstorms (30% chance). Low around 65°F. Additional 0.5-0.75 inches of rain possible.
<hr></hr
      
## Extended Outlook

### Monday, March 2
High: 79°F | Low: 66°F
Conditions: Mostly sunny to partly cloudy
Precipitation: Slight chance of rain showers (20-30%)
Wind: Northeast 6-14 mph with gusts up to 20 mph
Much improved conditions compared to Sunday

### Tuesday, March 3
High: 80°F | Low: 67°F
Conditions: Mostly sunny
Precipitation: Slight chance of showers (20-23%)
Wind: East 9-15 mph with gusts up to 21 mph
Pleasant weather overall

### Wednesday, March 4
High: 81°F | Low: 68°F
Conditions: Sunny to mostly clear
Precipitation: Slight chance of showers (20-24%)
Wind: East 8-15 mph with gusts up to 20 mph
<hr></hr
      
## Notable Weather Patterns
🌧️ **Active Weather Today**: The most significant weather is expected today with thunderstorms capable of producing heavy rainfall. Plan outdoor activities accordingly.

🌤️ **Improving Trend**: Conditions improve significantly starting Monday, with lower rain chances and more sunshine throughout the week.

🌡️ **Consistent Temperatures**: Expect pleasant, typical early March weather with highs in the upper 70s to low 80s and comfortable overnight lows in the mid-to-upper 60s.

💨 **Steady Breezes**: Moderate easterly winds throughout the week (8-15 mph) with occasional gusts up to 20 mph.
<hr></hr

## Planning Recommendations

**Today:** Be prepared for afternoon thunderstorms; bring rain gear and have indoor backup plans
**Monday-Wednesday:** Excellent conditions for outdoor activities with only slight rain chances
**Throughout the week:** Light layers recommended for comfortable mornings and warm afternoons


