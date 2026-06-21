# ImagineHack-2026
Track 1: Secure, Scalable, and Sustainable Advisory Platform by AAG x ASG

Project Title: NodeItDown
Description: NodeItDown is an enterprise-grade, AI-driven knowledge graph and automated note-taking platform. It transforms chaotic business conversations into a structured, interconnected neural network of corporate intelligence.

Team Name: 404
Team Members: Anderson Chung, Chang Kai Jie, Yau Cheng Long, Yoshito

Technologies Used: HTML5, CSS, JavaScript, API Intergration, OpenAI X Grafilab AI Model

Challenges & Approaches:
1. Challenges
The "Data Hairball" Problem: The risk of creating a chaotic, non-functional visual graph that confuses users instead of providing clarity.

Trust & Explainability: Wealth management is high-stakes. A "black box" AI that gives advice without evidence is a major compliance risk that would be rejected by fintech sponsors.

Contextual Fragmentation: Meetings, market news, and portfolio data live in different silos, making it nearly impossible for an advisor to manually connect the dots in real-time.

Time-to-Value Bottleneck: Manual synthesis of client meetings and research takes hours, causing a delay between the event (e.g., market change) and the advisory action.

2. The Technical Approach
Graph-Based Reasoning (Node-Link Architecture): Instead of a standard database list, we adopted a node-link model to visualize the relationship between "Problem" (e.g., meeting notes) and "Solution" (e.g., market insight). This transforms raw data into a Decision Map.

Deterministic Logic over Stochastic Guessing: To ensure reliability, we used a curated schema approach. By manually linking critical nodes during the demo, we ensure the "Agentic Loop" (News → Portfolio → Action) is logical, error-free, and audit-ready.

The "Evidence Trail" (Drill-Down Capability): We built an interactive interface where every node is clickable, revealing the source data (original transcripts or articles). This provides the audit trail required for financial compliance.

Automated Synthesis Engine: We leveraged FastAPI on the backend to act as the "coordinator." It intercepts the unstructured text from the "Voice" or "News" inputs and outputs a structured JSON schema, which the frontend then renders as an interactive node graph.

Human-in-the-Loop Workflow: We intentionally designed the platform to stop at the "proposal" stage, ensuring that a human advisor must approve the AI’s suggested action before it is sent to the client.
