# AI_Learning_MCP  

## lab 1  

Context  
Two Mcp tools are used. One tool is to use playwright and node to extract content from browsers. Another tools is to use a file system and node to write responses from a LLM model gpt-4.1-mini.  

The screenshots below show results. 
<img width="2533" height="568" alt="image" src="https://github.com/user-attachments/assets/2b1596cc-3c27-4038-ae77-e39b9c7897c6" />  
They could be found in the file https://github.com/ruihukuang/AI_Learning_MCP/blob/main/sandbox/banoffee.md. 

The trace below shows the process in this workflow.  
<img width="1796" height="1472" alt="image" src="https://github.com/user-attachments/assets/32786d20-b7db-4d4e-94f4-0432f41f9d58" />  

## lab 2  

Context  
Use account.py to create a mcp server. This server is used to integrate with a LLM model gpt-4.1-mini to manage an account for a client, and answer questions about the account.  

The screenshot below shows some outputs for a request.  
<img width="1514" height="663" alt="image" src="https://github.com/user-attachments/assets/e9cb6a43-ad11-474e-834b-52cab0ddb441" />  

## lab 3  

Context  
3 Mcp servers are used. They work with LLM models to generate outputs.  

The first one is a knowledge-graph based memory MCP server related to *libsql*. This mcp server persistently stores entities, observations about them, and relationships between them.  

This mcp server helps to keep memory of entity info and enables to continue conversations based on previous interactions. 

The screenshot below show outputs for the first mcp server usages.  
<img width="1571" height="798" alt="image" src="https://github.com/user-attachments/assets/dd8b60a7-c5ef-49f0-85c5-b207c57f69c2" />  

The second one is a web search MCP server related to *Brave Search*. This Mcp server is used to search info in web similar to google web searches.  

The screenshot below show outputs for the second mcp server usages.  
<img width="1463" height="1225" alt="image" src="https://github.com/user-attachments/assets/abfee1c3-d96a-42ac-98c3-160f27bb7d26" />  

The third one is a financial data MCP server related to *Polygon*. A market.py file is used to interact Polygon API calls to get different share prices. A MCP server is created based on this file.  

The screenshot below show outputs for the third mcp server usages.  
<img width="1481" height="425" alt="image" src="https://github.com/user-attachments/assets/a767035a-e4e2-45a2-ac22-7f8239632ced" />  








