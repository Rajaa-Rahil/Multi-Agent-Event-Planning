# Multi-Agent Event Planning with CrewAI
A comprehensive event planning system using CrewAI's multi-agent framework to automate venue selection, logistics, marketing, and risk management for events.

## Project Overview

This project is a Jupyter Notebook that demonstrates a multi-agent approach to automated event planning using the CrewAI framework. The example focuses on organizing the "Green Energy Startup Expo" in Austin, TX, aiming to efficiently coordinate tasks between agents representing Venue Coordination, Logistics, Marketing and Communications, and Risk and Compliance.

## Features

- **Multi-Agent System**: Four specialized agents covering multiple aspects of event management.  
- **Structured Output**: Pydantic models to ensure data structuring. 
- **Web Integration**: Web search and content scraping tools.  
- **File Export**: Produces JSON and Markdown reports automatically.
- **environment variables**: Use environment variables (.env) to secure API key management. 
- **Sustainable Focus**: Special emphasis on green event planning.

## Technologies

- Python 3.x.
- Jupyter Notebook.
- CrewAI agent framework.
- dotenv for environment variables.
- OpenAI API, Serper API for web search.
- Pydantic for data models.

## Setup

1. Download the repository.
2. Install the required Python packages in the requirements.txt file.
3. Create a `.env` file in the root directory to store your API keys:
   OPENAI_API_KEY=your_openai_api_key
   SERPER_API_KEY=your_serper_api_key
4. Open the Jupyter Notebook and set your model.
5. Customize the event details and then run the cells:

 ```python
event_details = {
    'event_topic': "Your Event Name",
    'event_city': "City, State",
    'tentative_date': "YYYY-MM-DD",
    'expected_participants': 100,
    'budget': 50000,
    'preferences': "your preferences here",
    'audience': "target audience description",
    'venue_type': "Venue Type"
}
```

## Output Files

The project generates three files:

- `venue_details.json` – Structured venue information. 
- `marketing_report.md` – Marketing strategy and outreach plan.  
- `risk_compliance_checklist.md` – Safety, risk assessmment and compliance chechlist.

##  Acknowledgments

- Built with [CrewAI](https://www.crewai.com). 
- Uses [OpenAI](https://openai.com) models.  
- Search powered by [Serper](https://serper.dev).
   
