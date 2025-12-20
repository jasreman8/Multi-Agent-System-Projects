# Multi-Agent-System-Projects
This repository contains various multi-agent projects created using tools such as ReAct, CrewAI, and LangGraph.

Project 1: Implemented a full agentic workflow using create_react_agent with HR, IT, and Welcome agents coordinating end-to-end onboarding tasks. 
- HR Agent: creates employee records and initiates background checks
- IT Agent: provisions IT accounts, assigns hardware, and manages access setup
- Welcome Agent: generates personalized welcome emails and schedules onboarding sessions
- Modular multi-agent architecture enabling scalable, domain-specific automation

Project 2: Implemented a Multi-Agent RAG system using LangGraph with dynamic query routing:
- Built an LLM-based router to direct queries between internal document RAG and web search agents
- Integrated a hallucination detection and retry mechanism using structured LLM grading
- Enabled grounded answer regeneration based on retrieved evidence

Project 3: Implemented a full agentic onboarding workflow using CrewAI (Agent, Task, Crew, Process):
- Designed specialized HR, IT, and Welcome agents coordinating end-to-end onboarding tasks
- Structured modular tasks enabling scalable, domain-specific agent collaboration
