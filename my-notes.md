todo: link to instructions to generate PAT token


# which notebooks run?

## yes

# 01-intro-to-ai-agents

01-intro-to-ai-agents/code_samples/01-semantic-kernel.ipynb

# 02-explore-agentic-frameworks
02-explore-agentic-frameworks/code_samples/02-autogen.ipynb
02-explore-agentic-frameworks/code_samples/02-semantic-kernel.ipynb

#03-agentic-design-patterns
03-agentic-design-patterns/code_samples/03-semantic-kernel.ipynb

# 04-tool-use

# 05-agentic-rag
[good]05-agentic-rag/code_samples/05-semantic-kernel-azure-ai-agent.ipynb
[maybe]05-agentic-rag/code_samples/05-autogen-chromadb.ipynb


# 06-building-trustworthy-agents
[explain system message]06-building-trustworthy-agents/code_samples/06-system-message-framework.ipynb


# 08-multi-agent
[good to explain group chat]08-multi-agent/code_samples/08-semantic-kernel.ipynb
08-multi-agent/code_samples/08-autogen.ipynb

# 09-metacognition
09-metacognition/code_samples/09-semantic-kernel.ipynb

## not running/has issues

02-explore-agentic-frameworks/code_samples/02-azureaiagent.ipynb
- Run finished with status: RunStatus.FAILED Run failed: {'code': 'rate_limit_exceeded', 'message': 'Rate limit is exceeded. Try again in 60 seconds.'}

04-tool-use/code_samples/04-autogen.ipynb
- stays in loop, waiting for input?

04-tool-use/code_samples/04-semantic-kernel-python-aiagent-bookinghotel.ipynb
- AgentInvokeException: Run failed with status: `RunStatus.FAILED` for agent `BookingAgent` and thread `thread_GllROguxkv7tAOmVfUDeksBI` with error: No connection matching model: david_agent_01

05-agentic-rag/code_samples/05-semantic-kernel-azuresearch.ipynb
- trouble with ai search both me & dwight 
# tried with both dwitghts and my ai servce

05-agentic-rag/code_samples/05-semantic-kernel-chromadb.ipynb
- issues with pysqlite3