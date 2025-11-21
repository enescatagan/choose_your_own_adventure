### Backend Setup

1. İnitialization
```bash
uv init .
```

2. Add Dependencies
```bash
uv add fastapi[all] langchain langchain-openai python-dotenv sqlalchemy uvicorn psycopg2-binary
```