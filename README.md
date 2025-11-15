# Educational RAG

## Project setup

uv init

uv add setuptools dotenv ipykernel ipywidgets jupyter-dash langchain langchain_community langchain_huggingface langchain-ollama langchain-chroma langchain-openai langchain-text-splitters gradio ollama typer matplotlib numpy plotly scikit-learn nbformat 


# Modelos avaliados

base_model="openai/gpt-oss-120b" - insuficient credits
base_model="openai/gpt-oss-20b:free" - [1]
base_model="google/gemini-2.0-flash-exp:free" [1]
base_model="google/gemma-3n-e2b-it:free" [2] 
base_model="nvidia/nemotron-nano-12b-v2-vl:free" - ok
base_model="nvidia/nemotron-nano-9b-v2:free" - ok
base_model="qwen/qwen3-4b:free" [1]
base_model="qwen/qwen3-coder:free" - ok
base_model="meta-llama/llama-3.3-8b-instruct:free" - ok
base_model="meta-llama/llama-3.3-70b-instruct:free" [3]
base_model="deepseek/deepseek-chat-v3-0324:free" - [1]
base_model="deepseek/deepseek-chat-v3.1:free" - [2]



[1] RateLimitError: Error code: 429 - {'error': {'message': 'Provider returned error', 'code': 429, 'metadata': {'raw': 'openai/gpt-oss-20b:free is temporarily rate-limited upstream. Please retry shortly, or add your own key to accumulate your rate limits: https://openrouter.ai/settings/integrations', 'provider_name': 'Chutes'}}, 'user_id': 'user_35TQ1EigQNriguRE2twwpeQ3KIU'}

[2] NotFoundError: Error code: 404 - {'error': {'message': 'No endpoints found that support tool use. To learn more about provider routing, visit: https://openrouter.ai/docs/provider-routing', 'code': 404}}

[3] BadRequestError: Error code: 400 - {'error': {'message': 'Provider returned error', 'code': 400, 'metadata': {'raw': '{"detail":"Tools are not supported in streaming mode."}', 'provider_name': 'ModelRun'}}, 'user_id': 'user_35TQ1EigQNriguRE2twwpeQ3KIU'}








   