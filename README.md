# PydanticAI Cookbook
This is repo for creating small POC's of a Research Agent using the new library Pydantic AI. The agents are powered by gpt-4o and Tavily Search API.

To run the notebooks first install the requirements :
- `pip install -r requirements.txt`
- Create a file `keys.env` to store your API Keys.
- You can get your free Tavily Search API from [here](https://app.tavily.com/home)

The notebook `WebsearchAgent.ipynb` demonstartes how to create a simple research report with a title and summary points.

The notebook `ResearchAnalystAgent.ipynb` aims to produce dataframes out of the results of a query. The results are validated, as PydanticAI provides a way to add validation functions via the *agent.result_validator* decorator.
- This notebook can be further improved by maintaining conversation hisory.
- Can also improve info accuracy my using API's to data proprietors.


