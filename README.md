# Agentic Stock Analysis System with AutoGen  

🚀 **Exploring the Future of Autonomous AI with AutoGen!**  

This project showcases an **Agentic Stock Analysis System**, built using Microsoft's **AutoGen** framework. The system leverages a team of autonomous AI agents to collaboratively analyze stock performance, generate financial reports, and visualize data—all with minimal human intervention.  

The project demonstrates the **transformative potential of autonomous AI** in revolutionizing workflows in industries like finance, research, and beyond.  

**Demo Video**: [Watch Here](https://drive.google.com/file/d/1BbWgFj-efVn7IRode7LsAM_5y31jwVNr/view?usp=sharing)  

---

## 🧠 Highlights of AutoGen's Agent Collaboration  

What makes this project truly unique is the seamless collaboration between multiple autonomous agents, each with a specialized role:  

- **Financial Assistant**: Analyzes stock performance, crunches numbers, and prepares visualizations.  
- **Research Assistant**: Gathers market news and identifies relevant context for stock movements.  
- **Writer Agent**: Synthesizes insights into a professional financial report, complete with markdown formatting.  
- **Critic Agent**: Reviews the writer’s work and provides constructive feedback to improve quality.  
- **Reviewers (Legal, Consistency, Completion)**:  
  - **Legal Reviewer**: Ensures compliance with legal standards.  
  - **Consistency Reviewer**: Validates data consistency across the report.  
  - **Completion Reviewer**: Verifies that all required elements (e.g., news, metrics, and visualizations) are included.  
- **Meta Reviewer**: Aggregates feedback from all reviewers and provides actionable suggestions for improvement.  

---

## 🎯 Key Features  

1. **Autonomous Workflow**: Agents communicate, review, and improve outputs collaboratively, mimicking a real-world team dynamic.  
2. **Stock Analysis**:  
   - Analyzes stock prices over the last six months.  
   - Visualizes normalized stock prices.  
   - Extracts and compares key metrics (e.g., P/E ratio, ROE).  
3. **Market News Insights**: Summarizes and contextualizes relevant headlines for each stock, without sentiment analysis.  
4. **Professional Financial Reports**:  
   - Includes detailed analysis of metrics and correlations.  
   - Provides future scenario predictions.  
   - Integrates visualizations and tables for clarity.  
5. **Code Execution Autonomy**: Agents independently generate and execute code without relying on external libraries, a unique strength of AutoGen.  

---

## 💡 Why AutoGen?  

While frameworks like LangChain excel in task execution, **AutoGen** truly stands out for its ability to foster **agent collaboration and autonomy**. This project highlights:  

- **Teamwork Among Agents**: Agents don’t just execute tasks; they communicate, review, and refine each other’s work.  
- **Self-Sufficiency**: Agents autonomously generate, execute, and validate code, minimizing external dependencies.  
- **Scalability**: The system can be easily extended with additional agents or workflows.  

---

## 📈 The Task  

This project tackled a real-world stock analysis scenario, completing the following steps:  

- **Analyze stock performance**: Examined stock prices and trends over six months.  
- **Visualize normalized prices**: Created a comparative chart of normalized stock prices.  
- **Generate a financial report**:  
  - Included fundamental metrics, correlations, and comparative analysis.  
  - Summarized recent news headlines for context.  
  - Provided future scenarios and predictions.  

---

## 🛠️ Tech Stack  

- **Language**: Python  
- **Core Libraries**:  
  - [AutoGen](https://github.com/microsoft/autogen): Autonomous agent framework.  
  - [Streamlit](https://streamlit.io/): For the interactive user interface.    
- **Visualization**: Matplotlib (for generating figures).
  
---

### Prerequisites  

- Python 3.8+  
- [OpenAI API Key](https://platform.openai.com/signup/) (or another supported LLM API key).  
- A `.env` file containing your API key:  

## 🎥 Demo  

Check out the video demonstration of the project in action:  
[Watch the Demo](https://drive.google.com/file/d/1BbWgFj-efVn7IRode7LsAM_5y31jwVNr/view?usp=sharing)  

---

## 🌟 Acknowledgments  

Special thanks to **Mohsen Hassan** and **Ilyass Tabia** for their excellent course on **AutoGen**, which provided the tools and inspiration for this project.  

---

## 🚀 Future Directions  

1. Add support for live stock data using APIs like Yahoo Finance or Alpha Vantage.  
2. Enhance agent collaboration to optimize the review and report generation process.  
3. Expand analysis capabilities to include ETFs, commodities, and cryptocurrencies.  
4. Integrate sentiment analysis for deeper market insights.  
