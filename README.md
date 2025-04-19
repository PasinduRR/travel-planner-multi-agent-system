# travel-planner-multi-agent-system

A beginner-friendly multi-agent travel planner built using Google’s AI Agent Development Kit (ADK). This project showcases how multiple intelligent agents can collaboratively plan trips, handle constraints, and provide real-time travel suggestions.

## Project Stucture

travel_planner/
└── travel_planner/
    ├── .env                    # Stores environment variables like API keys
    ├── agent.py                # The main coordinator - delegates tasks to sub-agents  
    ├── subagents/              # Folder for different agent modules
    │   ├── flight_agent.py     # Handles flight search & suggestions
    │   └── hotel_agent.py      # Handles hotel search & bookings
    ├── tools/                  # Utility functions and tool schemas
    │   ├── schemas.py          # Pydantic or custom schema to ensure consistent data across agents
    └── __init__.py             # Makes travel_planner a Python package

## Guide on how to get started and build this system from scratch

[From Zero to Genius: How I Built a Powerful AI Agent with Google's ADK](https://medium.com/ai-advances/from-zero-to-genius-how-i-built-a-powerful-ai-agent-with-googles-adk-in-just-100-lines-of-code-79c16ceba7cc)
