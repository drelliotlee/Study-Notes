Python interpreters
- NEVER USE `/bin/python3`
- NEVER USE `/usr/bin/python3'
- ALWAYS USE `base (~/miniforge3/bin/python)`

---
# Meta Files

`.vscode/launch.json`  = how to launch debuggers
`.vscode/settings.json` = workspace-specific settings
- warnings and errors to ignore

`.github/copilot-instructions.md` = persistent chat instructions
When I type "EXP" at the beginning or end of a prompt, that means i just want you t-o talk to me in the chat window, not make any changes to code.

`.gitignore` = what not to commit

`environment.yml` = all dependencies, so other devs can use `mamba env create -f environment.yml`
`requirements.txt` derived from above, bc most containers want to use `pip install -r requirements.txt`

`pyproject.toml` = config settings for ruff, pyright, pytest

`.devcontainer/devcontainer.json`
`.devcontainer/Dockerfile`

---

# Misc Resources
(probably wont use)
**Github**
[Awesome LLM Apps (101k stars)](https://github.com/Shubhamsaboo/awesome-llm-apps)
[Learn AI Eng (5k stars)](https://github.com/ashishps1/learn-ai-engineering)
[AI Eng Hub (30k stars)](https://github.com/patchy631/ai-engineering-hub)
[Harvard ML Systems (22k stars)](https://github.com/harvard-edge/cs249r_book)
[Raschka Python ML Books (7k stars)](https://github.com/rasbt/python-machine-learning-book-2nd-edition)
[aws examples](https://github.com/aws-samples/mlops-e2e?utm_source=chatgpt.com)
[End to end projects on medium](https://medium.com/%40nedwinvivek/end-to-end-mlops-project-with-open-source-tools-78115cc59748)

**AWS**
[AWS General Immersion Day](https://catalog.workshops.aws/general-immersionday/en-US)
[AWS Workshops](https://builder.aws.com/build/workshops?trk=265ae1c7-2dfc-44c6-bc73-a4d991b8bd7f&sc_channel=el)
[Local Stack ](https://www.localstack.cloud/)
[learn to cloud bootcamp](https://ca-ltc-api-dev.whiteocean-ee25ad60.centralus.azurecontainerapps.io/)
[Cantrill Learning](https://learn.cantrill.io/)
[9 free cantrill labs](https://github.com/acantril/learn-cantrill-io-labs)
[maarek on udemy](https://www.udemy.com/user/stephane-maarek/)
[john bonso tutorialsdojo practice exams](https://tutorialsdojo.com/)
[neal davis digitalcloud](https://digitalcloud.training/)
[AWS skill builder: ML engineer](https://skillbuilder.aws/category/role/machine-learning-engineer)

- Misc Short Courses
	- AWS General Immersion Day workshop
	- AWS SageMaker Immersion Day workshop
	- Anthropic: Claude with Amazon Bedrock
	- Serverless LLM Apps with Amazon Bedrock (by AWS, via DL.ai)
	- IAM Immersion Day workshop



## Projects
- Project 1: Terraform-Managed GenAI Service in AWS [100]
	- Containerized inference API
	- IAM, logging, alerts
	- Cost & latency awareness
	- LangSmith for LLM observability
	- Guardrails integration
	- FastAPI serving layer
	- CI/CD with GitHub Actions
	- Streamlit or Gradio demo UI
- Project 2: Data Ingestion & Warehousing in AWS [80]
	- Streaming + batch data ingestion
	- Data warehouse + schema evolution
	- Prefect for pipeline orchestration
	- Cost optimization
	- CI/CD with GitHub Actions
	- Redis caching layer
- Project 3: End-to-End ML System in AWS [120]
	- A/B testing with traffic splitting
	- Model performance & drift monitoring
	- Feedback loops + automated retraining triggers
	- MLflow for experiment tracking and model registry
	- W&B for training visualization
	- Prometheus + Grafana dashboards
	- CI/CD with GitHub Actions
	- Streamlit or Gradio demo UI