In this section we break down the differences between:
*  Automation
* Basic LLM Workflow
* Agentic Workflow
Automation refers to the use of code to write functions, establish rules and apply it to a repeatable task.  A basic LLM workflow when we input some prompt with instructions and we expect and output with a useful response. An agentic workflow can choose tools depending on the type of task that is given and can take decisions on what actions to take.

| Workflow type      | Description                                                                          |
| ------------------ | ------------------------------------------------------------------------------------ |
| Basic LLM workflow | A fixed path from input to prompt, model, and output                                 |
| Automation         | A predictable workflow controlled by code, rules, or functions                       |
| Agentic workflow   | A workflow where the system can choose tools, update state, and decide the next step |
LangChain is an open source framework for building LLM-powered applications and agents, however, in this room we will focus on it's ability for tool calling. 

A LangChain agent can decide when to request an approved tool, provide the required input, receive the result, and use that information to produce a final answer.

Choose wether or not to develop an Agentic workflow depending on the the complexity of the job/task.