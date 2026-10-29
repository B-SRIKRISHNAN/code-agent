# code-agent
A coding agent that can work on an input issue using a mix of paid and local models for optimal token cost without quality compromise


This will be designed to run inside a docker container. Ideally must have an api based access to local models on the network for modularity.

The agent will have multiple agents and possibly a rag setup for optimal code index if needed.


Each container must resolve one issue of sufficient complexity... If a issue is very complex or is a very big module, then it must be broken down to features that are issue level, create every one of the issues and then work on that issue....
