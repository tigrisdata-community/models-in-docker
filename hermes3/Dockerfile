FROM reg.xeiaso.net/llama.cpp/server-cuda

ADD https://huggingface.co/NousResearch/Hermes-3-Llama-3.1-8B-GGUF/resolve/main/Hermes-3-Llama-3.1-8B.Q4_K_M.gguf?download=true /models/hermes3-8b-q4_k_m.gguf

CMD ["-m", "/models/hermes3-8b-q4_k_m.gguf", "--port", "8000", "--host", "::"]