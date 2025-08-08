## AI Travel Agent

This Streamlit app is an AI-powered travel Agent that generates personalized travel itineraries using OpenAI GPT-4o. It automates the process of researching, planning, and organizing your dream vacation, allowing you to explore excitingdestinations with ease.

### Features
+ Research and discover exciting travel destinations, activities, and accommodations
+ Customize your itinerary based on the number of days you want to travel
+ Utilize the power of GPT-4o to generate intelligent and personalized travel plans
+ Download your itinerary as a calendar (.ics) file to import into Google Calendar, Apple Calendar, or other calendar apps

### How to get Started?
1. Install the required dependencies:

`pip install -r requirements.txt`

2. Get your OpenAI API Key

`Sign up for an [OpenAI account](https://auth.openai.com/log-in) (or the LLM provider of your choice) and obtain your API key.`

3. Get your SerpAPI Key

`Sign up for an [SerpAPI account](https://serper.dev/) and obtain your API key.`

4. Run the Streamlit App

`streamlit run travel_agent.py`

### How it Works?
The AI Travel Agent has two main components:

+ __Researcher__: Responsible for generating search terms based on the user's destination and travel duration, and searching the web for relevant activities and accommodations using SerpAPI.
+ __Planner__: Takes the research results and user preferences to generate a personalized draft itinerary that includes suggested activities, dining options, and accommodations.

### Using the Calendar Download Feature
After generating your travel itinerary:

1. Click the "Download Itinerary as Calendar (.ics)" button that appears next to the "Generate Itinerary" button
2. Save the .ics file to your computer
3. Import the file into your preferred calendar application (Google Calendar, Apple Calendar, Outlook, etc.)
4. Each day of your itinerary will appear as an all-day event in your calendar
5. The complete details for each day's activities are included in the event description

