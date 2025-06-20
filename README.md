# Transfers-api
 REST API for booking transfers, with full OpenAPI 3.0 documentation, logging and HTTP Basic Auth.
# Transfers API

Production-ready REST API for managing transfer bookings — designed for integration with external travel services.

## 🚀 Features

- ✅ Transfer search, booking, status, and cancellation endpoints
- 🔐 HTTP Basic Authentication
- 📄 OpenAPI 3.0 schema for documentation and testing
- 🧾 JSON format for all requests and responses
- 🪵 Detailed logging for audit and debugging

## 🔧 Tech Stack

- Python 3.11
- FastAPI
- Uvicorn
- Pydantic
- Logging

## 📂 Project Structure
transfers-api/
├── app/
│   ├── main.py            # Entry point with FastAPI app and routes
│   ├── auth.py            # HTTP Basic Auth implementation
│   ├── schemas.py         # Pydantic models for request/response
│   └── utils.py           # Helper functions (e.g., vehicle mapping)
├── tests/                 # Test cases (optional)
├── requirements.txt       # Python dependencies
├── README.md              # Project documentation
Run server
uvicorn app.main:app --reload
Access interactive docs at:
📚 http://localhost:8000/docs

📌 Use Cases
 • Integrate with third-party booking systems
 • Serve as backend for transfer-ordering apps or bots
 • Test API responses with Swagger/OpenAPI interface

📜 License

MIT License
