# interview-prep-agenticai-chatbot

By leveraging a multi-agent approach and Retrieval-Augmented Generation (RAG), we build an advanced AI-driven interview assistant that retrieves relevant knowledge, processes responses through specialized AI agents, and provides intelligent, personalized feedback.

### Benefits of Using LangGraph and CrewAI Together
LangGraph and CrewAI serve complementary roles in orchestrating AI workflows:

1. LangGraph provides a structured, graph-based execution model ideal for retrieval pipelines.
2. CrewAI enables multiple AI agents to collaborate dynamically, each specializing in different aspects of problem-solving.
3. Together, they create a flexible, intelligent system that can retrieve knowledge, analyze responses, and provide optimized feedback efficiently.
   
Best Approach: Use LangGraph for knowledge retrieval and workflow management, and CrewAI for multi-agent interaction.

### How the System Works
- User asks a question → e.g., “How does Dijkstra’s algorithm work?”
- LangGraph retrieves relevant knowledge from FAISS.
- CrewAI’s agents (DSA AI, LLD AI, HLD AI) evaluate and refine the response.
- LangGraph manages the execution flow and returns a structured answer.

### Tech Stack
- LangGraph → Workflow orchestration
- CrewAI → Multi-agent collaboration
- FAISS → Vector search for efficient knowledge retrieval
- DeepSeekR1→ LLM for intelligent responses
