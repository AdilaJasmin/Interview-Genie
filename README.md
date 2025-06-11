# INTRODUCTION

In today's competitive job market, effective interview preparation is essential for candidates to stand out. However, many job seekers struggle to access relevant and personalized resources that match their specific career goals. Interview Genie is an AI-driven platform designed to bridge this gap by providing a tailored interview preparation experience.
Leveraging state-of-the-art Natural Language Processing (NLP) and Retrieval-Augmented Generation (RAG) models, Interview Genie dynamically generates interview questions based on user-provided job descriptions and roles. This ensures that candidates practice with highly relevant, role-specific questions, enhancing their ability to respond confidently and effectively during actual interviews
Interview Genie offers not just question generation but also contextual feedback, enabling users to refine their answers and gain insights into what employers are looking for. By streamlining the preparation process, the platform empowers job seekers to approach interviews with greater confidence, positioning them as strong contenders in their chosen fields.
Whether you're a fresh graduate entering the workforce or a seasoned professional seeking a career change, Interview Genie adapts to your needs, transforming how you prepare for and succeed in interviews.

# ABSTRACT

Interview Genie is an AI-driven platform that enhances interview preparation by generating personalized interview questions based on specific job descriptions. Using advanced Natural Language Processing (NLP) and Retrieval-Augmented Generation (RAG) models, the system tailors questions to align with user-defined roles, ensuring effective practice. This functionality equips job seekers with relevant interview insights, allowing them to build confidence and improve their readiness for real interviews. By optimizing the preparation process, Interview Genie positions candidates as strong contenders in the competitive job market through targeted practice and contextual feedback.

# RUN CODE
# *Activate your virtual environment if not already activated*
source myenv/bin/activate

# *Uninstall conflicting packages*
pip uninstall streamlit langchain langchain-core langchain-text-splitters langsmith chromadb langchain-community langchain-groq langchain-huggingface -y

# *Install required packages in a specific order*
pip install numpy==1.26.4 protobuf==5.28.3 altair cachetools gitpython pyarrow pydeck rich tenacity typing-extensions watchdog requests
pip install langchain==0.3.7 langchain-core==0.3.15 langchain-text-splitters==0.3.2 langsmith==0.1.142 chromadb==0.5.18
pip install sentence-transformers streamlit transformers langchain-huggingface langchain-chroma langchain-community langchain-groq

# *Install any additional missing dependencies if necessary*
pip install aiohttp async-timeout pydantic SQLAlchemy bcrypt onnxruntime grpcio fastapi importlib-resources mmh3 opentelemetry-api opentelemetry-sdk opentelemetry-exporter-otlp-proto-grpc

# *Check for missing dependencies*
pip check

# *Run your application again*
streamlit run app.py
