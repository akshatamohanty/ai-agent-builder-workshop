# AI Agent Builder Workshop

This comprehensive workshop covers a detailed code walkthrough of building an AI agent from scratch and deploying it to production. We'll cover key concepts like RAG, and explore the design process for agents, including planning, tool design, handling agent communication, memory, evaluation, testing and observability. Attendees will get hands-on experience with both code and no-code tools to build and deploy AI agents to production using open source frameworks like LangChain, LangGraph and Google Cloud.

## Contents

- [Introduction to AI Agents](https://docs.google.com/presentation/d/e/2PACX-1vTuA0bGX_K8p85S5EC4rp2YzbN0sSVR9LCoJJzfVJ2R50KIQFvUO3L7VVqaiUZ8ebzf5aYjdsX7vD1m/pub?start=false&loop=false&delayms=3000)

- [Introduction to LangChain](https://docs.google.com/presentation/d/e/2PACX-1vRNgHl8wJgPu9Aeb6xYvWmI0aNSJ7CAcuO3NttCPDBWSzkSs_mKizcEVqQZhAkgcc5sxSqziO052nNk/pub?start=false&loop=false&delayms=3000)

- <a style="display: flex; flex-direction: row" target="_blank" href="https://colab.research.google.com/github/akshatamohanty/ai-agent-builder-workshop/blob/main/02_Working_with_LLMs.ipynb">
  <div style="margin-right: 4px">Introduction to LangChain: Code walkthrough </div>
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
</a>

- [Introduction to LangGraph](https://docs.google.com/presentation/d/e/2PACX-1vRlRsjDFRRg2JVjaw9DojzZv9qzRziSvMYdado2oWQ7sVk2cr7r3kH2Yk22BFXrh7Rt5aFb8U4ZGKN3/pub?start=false&loop=false&delayms=3000)

- <a style="display: flex; flex-direction: row" target="_blank" href="https://colab.research.google.com/github/akshatamohanty/ai-agent-builder-workshop/blob/main/05_Build_your_own_agent.ipynb">
    <div style="margin-right: 4px">Introduction to LangGraph: Code walkthrough </div>
    <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
</a>

- <a style="display: flex; flex-direction: row" target="_blank" href="https://colab.research.google.com/github/akshatamohanty/ai-agent-builder-workshop/blob/main/06_Research_assistant.ipynb">
    <div style="margin-right: 4px">Building an AI Research Assistant: Code walkthrough</div>
    <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
</a>

- [LangChain Trace Example](https://smith.langchain.com/public/2524f9e0-6d2e-4fea-a775-ce8c5288c2b2/r)

## Setup


### Running Jupyter Notebooks with Google Collab
These guides use Jupyter notebooks. Jupyter notebooks are convenient for learning how to work with LLM systems because oftentimes things can go wrong (unexpected output, API down, etc) and going through guides in an interactive environment is a great way to better understand them.

This and other tutorials are perhaps most conveniently run in a Jupyter notebook in Google Colab. Click on the links above to open the notebooks in Google Collab (you will need a Google account). 

## Running Jupyter Notebooks locally

See [here](https://jupyter.org/install) for instructions on how to install Jupyter locally.
Use `venv` to create a virtual environment and activate it.

```
python3 -m venv agent-builder
source agent-builder/bin/activate
pip3 install -r requirements.txt
```

## API Keys

We use the following API Keys in the Jupyter notebooks. Head over to the links given below. All the following, with the exception of OpenAI can be used with their free tier.

| API KEY    | Link |
| -------- | ------- |
| Gemini  | [https://aistudio.google.com/app/apikey](https://aistudio.google.com/app/apikey)    |
| LangSmith |  [https://smith.langchain.com/](https://smith.langchain.com/ )    |
| OpenAI    |  [https://platform.openai.com/api-keys](https://platform.openai.com/api-keys)    |
| Tavily    |  [https://app.tavily.com/home](https://app.tavily.com/home)    |


## Resources

- [Langgraph](https://langchain-ai.github.io/langgraph/tutorials/)
- [Langraph Academy](https://academy.langchain.com/courses/intro-to-langgraph)