FROM reg.xeiaso.net/llama.cpp/server-cuda

ADD https://huggingface.co/QuantFactory/SmolLM-135M-GGUF/resolve/main/SmolLM-135M.Q4_0.gguf?download=true /models/smollm-135m-q4.gguf

CMD ["-m", "/models/smollm-135m-q4.gguf", "--port", "8000", "--host", "::"]