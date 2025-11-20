<h2>🤖Blog-writer-multi-agent-master  Crew AI</h2>
The Multi-Agent Blog Writing System (Crew AI) is an innovative project that utilizes cutting-edge technologies to automate the process of creating well-researched, human-like blogs. This system is designed to bridge the gap between AI automation and human creativity by incorporating the latest advancements in Agentic AI.

This project features a multi-agent architecture that autonomously plans, writes, and edits blog posts, ensuring they are accurate, engaging, and up-to-date with the latest trends.

<img width="1575" height="642" alt="multi agent blog writer" src="https://github.com/user-attachments/assets/c2fdb563-ec45-48d9-b9ec-36a0059cd7f3" />

<h2>📁Project Structure</h2>
 <img width="956" height="393" alt="scree" src="https://github.com/user-attachments/assets/eb9649d0-108a-41e7-9ef5-f7a4356251b2" />
 
<h2>🪶Features</h2>
1. Planner Agent: Structures and strategizes blog content based on the input query.

2. Writer Agent: Generates the blog content using the Gemini 2.0-Flash-EXP LLM.

3. Editor Agent: Refines the content for clarity, engagement, and accuracy.

4. Integration with Serper Web Search: Fetches the latest information and trends.

5. FastAPI Backend: Handles blog generation requests.

6. Next.js Frontend: Provides a sleek user interface for input and blog display.

7. End-to-End Automation: Delivers a complete, polished blog with references.
   
<h2>🎡Technologies Used</h2>
<h3>Backend</h3>

1. CREW AI: For Creating multi agent system.

2. FastAPI: For serving the AI-powered blog generation API.

3. Python: For scripting and implementation.

4. LangChain: For managing multi-agent workflows.

5. Gemini 2.0-Flash-EXP: As the language model powering the system.

6. Serper Web Search Tool: To gather real-time data and trends.

<h3>Frontend</h3>

1. Next.js: For building the client-side application.

2. React: For creating dynamic UI components.

3. Tailwind CSS: For styling.

4. Shadcn UI: Components.

<h2>⬇️Installation</h2>
<h2>Backend Setup (FastAPI Server)</h2>
1. Install Dependencies: Ensure Python 3.8+ is installed. Install the required Python libraries:

```bash
pip install -r server/requirements.txt
```
2. Run the FastAPI Server: Open the crewai.ipynb notebook and run the cells to start the FastAPI server.
  
- **Server URL:** `http://127.0.0.1:8002`

<h2>Frontend Setup (Next.js)</h2>
1. Navigate to the Frontend Directory:

 ```bash
cd client/bloggpt
```
2. Install Dependencies:
```bash
npm install
```
3.Start the Development Server:
```bash
npm run dev
```
- **Frontend URL:** ` http://localhost:3000`

<h2>🤯How It Works</h2>
1. User Input: The user enters a topic through the Next.js frontend.

2. API Request: The frontend sends a POST request to the FastAPI server running at
   
`http://127.0.0.1:8002/generate-blog/`.

3. <h2>Blog Generation:</h2>
- **The FastAPI server processes the request using** `crewai.ipynb`
- **The AI agents (Planner, Writer, Editor) collaboratively generate a polished blog.**

4. Response: The FastAPI server returns the generated blog in Markdown format.
5. <H2>Frontend Rendering:</h2>
- **The blog is rendered using `ReactMarkdown` with proper Markdown styling.**

<h2> 🎯Use Cases</h2>

- **Content Marketing:** Automate blog creation for businesses and brands.
  
- **Research Documentation:** Generate research summaries or articles with minimal effort.

- **Trend Analysis:** Create content based on the latest trends in various domains.


<h2>🧾Future Enhancements</h2>

- **Multi-modal Capabilities:** Incorporate image and video generation.

- **Advanced Customization:** Enable user-specific writing styles.

- **Workflow Orchestration:** Add support for managing multiple blogs simultaneously.




                                                           
 


























