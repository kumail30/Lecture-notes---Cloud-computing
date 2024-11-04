# NotebookLM Evaluation for University Use
# Open Notebook

An open source, privacy-focused alternative to Google's Notebook LM. Why give Google more of our data when we can take control of our own research workflows?

In a world dominated by Artificial Intelligence, having the ability to think 🧠 and acquire new knowledge 💡, is a skill that should not be a privilege for a few, nor restricted to a single company.

Open Notebook empowers you to manage your research, generate AI-assisted notes, and interact with your content—on your terms.

Learn more about our project at [https://www.open-notebook.ai](https://www.open-notebook.ai)

This repository contains a practical demonstration and evaluation of NotebookLM's capabilities. Each folder documents a specific feature, with examples and observations.

- **Summarization Demo**: Demonstrates how NotebookLM generates summaries from educational materials.
  - [View Summarization Demo](./summarization-demo)
- **QnA Demo**: Logs questions and answers generated by NotebookLM based on content.
  - [View QnA Demo](./QnA-demo)
- **Contextual Search Demo**: Showcases how NotebookLM retrieves information contextually.
  - [View Contextual Search Demo](./contextual-search-demo)
- **Study Guide Demo**: A study guide generated from course materials.
  - [View Study Guide Demo](./study-guide-demo)


### 📝 Notebook Page

Three intuitive columns to streamline your work:
1. **Sources**: Manage all research materials.
2. **Notes**: Create or AI-generate notes.
3. **Chat**: Chat with the AI, leveraging your content.

### ⚙️ Context Configuration

Take control of your data. Decide what gets sent to the AI with three context options:
- No context
- Summary only
- Full content

Plus, you can add your project description to help the AI provide more accurate and helpful responses.

### 🔍 Integrated Search for Your Items

Locate anything across your research with ease using full-text and vector-based search.

### 💬 Powerful open prompts

Jinja based prompts that are easy to customize to your own preferences.


## 🌟 Roadmap

- **Enhanced Citations**: Improved layout and finer control for citations.
- **Better Embeddings & Summarization**: Smarter ways to distill information.
- **Multiple Chat Sessions**: Juggle different discussions within the same notebook.
- **Live Front-End Updates**: Real-time UI updates for a smoother experience.
- **Async Processing**: Faster UI through asynchronous content processing.
- **Cross-Notebook Sources and Notes**: Reuse research notes across projects.
- **Bookmark Integration**: Integrate with your favorite bookmarking app.
- **Multi-model support**: Open AI, Anthropic, Vertex AI, Open Router, Ollama, etc. ✅ 0.0.2
- **Insight Generation**: New tools for creating insights - [transformations](docs/TRANSFORMATIONS.md) ✅ 0.0.3
- **Podcast Generator**: Automatically convert your notes into a podcast format.  ✅ 0.0.4


## 💻 Tech Stack

- **Streamlit**: For the front-end (Looking to move out of Streamlit. Contributors welcome!).
- **SurrealDB**: Fast, scalable database solution.
- **Langchain/Langgraph**: The backbone for LLM interactions.
- **Podcastfy**: For generating podcasts from your notes.


## 🙌 Help Wanted

We would love your contributions! Specifically, we're looking for help with:
- **Front-End Development**: Improve the UI/UX by moving beyond Streamlit.
- **Testing & Bug Fixes**: Help make Open Notebook more robust.
- **Feature Development**: Let’s make the coolest note-taking tool together!

See more at [CONTRIBUTING](CONTRIBUTING.md)
## 📄 License

Open Notebook is MIT licensed. See the [LICENSE](LICENSE) file for details.

---

Your contributions, feature requests, and bug reports are always welcome. Let's build a research tool that respects our privacy and makes learning truly open for everyone. ✨
