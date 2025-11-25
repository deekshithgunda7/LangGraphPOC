geoffrey hinton and yann lecun ,Andrew Ng  deep learning

Andrej karpathy for neural network and deep learning stareted today
bryc deep leaning   stared
steve brunton for staticis and data sciecnce and cd
   
RAG AND MCP   
LangGraph basic   
Google Mixture of Recursions  paper explained      
LLM Vs Diffusion modals

Today I started math of deep learning
 

to acticate virtual env using .venv\Scripts\activate
to add library uv add -r requirements.txt


Build Basic ChatBot using LangGraph  Graph  API 
Components of LangGraph 

1 - Edge  -- Link 2 nodes 
2 - Node  -- Implementation of any workflow(EX:ytvideo to transcript generator)
3 - State  -- Here you save the output of  one of the  workflow and can be used in any workflo w as per your graph


- maintained state among the nodes is called  stateGraph
- Graph API
- Functional API

        LLM + prompt
            |
START --> ChatBot  --> END               
            |
   External Tools integration  --  reACT Agent

   We have stateGraph and memory..both are different

Lets implement above   

In code

add_messages is called reducer

In a session,when have a conversation every out put is saved in state graph on a variable which holds a list of items.So with the help of reducers we can append any type of data onto list rather than overidding it



lets build it from scratch

ReACT Agent Usage plays important role -- > Act , Observe and Reason  ---> LLM to toolnode for(AI news) and again LLm to ToolNode(for 5 * 5) and to end this is reACT agent Architecture\  



MCP (Model Context Protocol) is an open-source standard for connecting AI applications to external systems.
Using MCP, AI applications like Claude or ChatGPT can connect to data sources (e.g. local files, databases), tools (e.g. search engines, calculators) and workflows (e.g. specialized prompt s)—enabling them to access key information and perform tasks.
 

Distributed computing for multiple system for availabulity