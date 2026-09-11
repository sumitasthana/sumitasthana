## Hi, I'm Sumit

Data scientist by profession, student by nature. Based in Pittsburgh.

Most of my work is about metadata: figuring out where data came from, what
touched it on the way, and what breaks when something changes. Lately that
means building LLM agents that read a codebase directly instead of trusting
whatever the documentation claims.

### Things I'm building

**[metamodel](https://github.com/sumitasthana/metamodel)** : scans a Python
codebase and builds a Neo4j graph of the jobs, datasets, columns and
transformations inside it. You can then ask it plain questions: where does this
column come from, what breaks if I rename this field, which jobs move PII
without an audit trail. Python, FastAPI, Neo4j, React.

**[cardinal](https://github.com/sumitasthana/cardinal)** and
**[kratos-agents](https://github.com/sumitasthana/kratos-agents)** : the schema
layer and the agents behind Kratos.

**[efors](https://github.com/sumitasthana/efors)** : finding machine learning
papers, made less painful.

**[gan-dat](https://github.com/sumitasthana/gan-dat)** : uses GANs to synthesize
extra training rows when a dataset is too small or too imbalanced to model
honestly.

### What I usually reach for

Python, LangChain and LangGraph, Neo4j, FastAPI, React, Docker. Most of it ends up
pointed at financial services data.

### Saying hello

If something here is useful to you, or you disagree with how I modelled a
graph, open an issue on the repo. I would rather hear it.
