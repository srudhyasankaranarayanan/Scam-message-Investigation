
# Scam Message Investigator

## Project Description

Scam Message Investigator is an AI-powered application that helps users identify suspicious messages. It analyzes SMS messages, emails, and other text messages to find possible scam indicators.

The application uses the Gemma 3:1B language model through Ollama to examine messages and provide a risk assessment.

It helps users understand why a message may be suspicious and suggests safety actions to avoid online scams.

## Features

- Analyze suspicious SMS and email messages.
- Identify possible scam indicators.
- Detect urgent or threatening messages.
- Identify requests for passwords, OTPs, PINs, and bank details.
- Examine suspicious links and payment requests.
- Classify messages based on their risk level.
- Provide safety recommendations.
- Generate an investigation report.

## Technologies Used

- Python
- Streamlit
- Ollama
- Gemma 3:1B
- Requests
- JSON

## How It Works

1. The user enters a suspicious message.
2. The application sends the message to the local Ollama service.
3. The Gemma 3:1B model analyzes the message.
4. The AI identifies possible warning signs.
5. The application displays the risk level and investigation results.
6. The user receives safety recommendations.

## Project Structure

```text
Scam-Message-Investigator/
│
├── app.py
└── README.md
```

## Installation

### 1. Install Python Dependencies

```bash
pip install streamlit requests
```

### 2. Install Ollama

Download and install Ollama from:

https://ollama.com/

### 3. Download the Model

Open the terminal and run:

```bash
ollama pull gemma3:1b
```

### 4. Run the Application

Navigate to the project folder and execute:

```bash
streamlit run app.py
```

The application will open in your web browser.

## Risk Levels

- Low Concern: No clear warning signs are identified.
- Medium Concern: Some suspicious elements are found.
- High Concern: Multiple serious warning signs are detected.

## Advantages

- Easy to use.
- Runs AI locally using Ollama.
- Helps users recognize common online scams.
- Provides quick message analysis.
- Does not require a paid AI API.

## Limitations

- AI results may not always be accurate.
- A message alone cannot confirm whether a sender is genuine.
- The application cannot independently verify links or sender identities.
- Users should verify important messages through official channels.

## Future Enhancements

- Add image-based message analysis.
- Support multiple languages.
- Add suspicious URL checking.
- Maintain investigation history.
- Generate downloadable PDF reports.

## Conclusion

Scam Message Investigator is a simple AI-based application that helps users understand potential online threats. It uses a locally running language model to analyze messages and provide useful safety suggestions. It aims to improve digital awareness and help users stay safe from online scams.

## Author

**Srudhya Sankaranarayanan**
