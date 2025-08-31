geoffrey hinton and yann lecun

RAG AND MCP
LangGraph basic

Build Basic ChatBot using LangGraph Graph API
Components of LangGraph

1 - Edge  -- Link 2 nodes
2 - Node  -- Implementation of any workflow(EX:ytvideo to transcript generator)
3 - State  -- Here you save the output of one of the workflow and can be used in any workflow as per your graph


- maintained state among the nodes is called stateGraph
- Graph API
- Functional API

        LLM + prompt
            |
START --> ChatBot  --> END               
            |
   External Tools integration  --  reACT Agent