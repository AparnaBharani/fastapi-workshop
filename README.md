#  FastAPI Workshop

#  What You'll Learn

- Create a FastAPI application
- Understand API Endpoints
- Create Path Parameters
- Create Query Parameters
- Handle HTTP Exceptions
- Use Pydantic Models
- Perform CRUD Operations

---

#  Project Structure

```text
fastapi-workshop/
│
├── README.md
├── pyproject.toml
├── uv.lock
├── .gitignore
├── main.py
└── patients.json
```

---

#  Prerequisites

- Python 3.10 or later
- uv
- VS Code
- Git

---

#  Install uv

### Windows (PowerShell)

```powershell
powershell -ExecutionPolicy ByPass -c "irm https://astral.sh/uv/install.ps1 | iex"
```

### Linux / macOS

```bash
curl -LsSf https://astral.sh/uv/install.sh | sh
```

Verify the installation:

```bash
uv --version
```

---

#  Clone the Repository

```bash
git clone https://github.com/<your-username>/fastapi-workshop.git

cd fastapi-workshop
```

---

#  Create a Virtual Environment

### Windows

```bash
uv venv
.venv\Scripts\activate
```

### Linux / macOS

```bash
uv venv
source .venv/bin/activate
```

---

#  Install Dependencies

```bash
uv sync
```

This installs all the required packages listed in the project.

---

#  Run the Application

```bash
uv run fastapi dev main.py
```

Once the server starts, you should see something similar to:

```text
Uvicorn running on http://127.0.0.1:8000
```

---

#  Open in Your Browser

### Home

```
http://127.0.0.1:8000/
```

### Swagger UI

```
http://127.0.0.1:8000/docs
```

### ReDoc

```
http://127.0.0.1:8000/redoc
```

---

#  Workshop Flow

- Hello World Endpoint
- About API Endpoints
- Reading JSON Data
- Path Parameters
- HTTP Exceptions
- Query Parameters
- Pydantic Models
- CRUD Operations

---

#  Tech Stack

- Python
- FastAPI
- Pydantic
- uv

---

Happy Coding! 🚀
