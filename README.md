## Hi, I'm Sumit

Data scientist by profession, student by nature. Based in Pittsburgh.

Most of my work is about metadata: figuring out where a piece of data came
from, what touched it on the way, and what breaks when something upstream
changes. In a large organisation nobody actually knows this. It is spread
across hundreds of scripts, and the documentation stopped being true years ago.

So I build systems that read the code instead of the docs. They pull apart a
codebase, work out which jobs read and write which tables, follow a single
column back through every transformation that produced it, and store the whole
thing as a graph you can query. Then the hard questions get easy: where did
this number come from, what will this rename break, which pipelines move
sensitive data without anyone checking.

Lately that means putting LLM agents to work on the parts static analysis
cannot reach, and being careful about which answers are proven and which are
only the model's best guess. The two should never look the same to whoever is
reading the result.

Before this I spent a lot of time on modelling proper: imbalanced data,
synthetic data, and the gap between a model that scores well and a model you
would trust with a real decision.

### What I usually reach for

Python, LangChain and LangGraph, Neo4j, FastAPI, React, Docker. Most of it ends
up pointed at financial services data.

### Saying hello

If any of this overlaps with what you are working on, or you think I have
modelled something the wrong way, open an issue on one of my repos. I would
rather hear it.
