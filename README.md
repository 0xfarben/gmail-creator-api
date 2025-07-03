# [Free-Gmail-API](https://rapidapi.com/canvabouys/api/free-gmail-api){:target="_blank"}- Empower Your Email Testing! 🌟

Welcome to **FREE-GMAIL-API**, your go-to solution for generating temporary Gmail addresses and retrieving messages effortlessly. This API, built with FastAPI and integrated with Emailnator, is designed for developers seeking privacy, testing, and automation capabilities. Unlock its full potential with this guide!

## 🚀 Getting Started

### What is Free-Gmail-API?
Free-Gmail-API allows you to:
- Generate disposable Gmail addresses for testing or privacy.
- Fetch message lists and detailed content (sender, subject, time, and refined text).
- Ensure robust performance with CSRF token handling.
### Why Use It?
- **Privacy**: Ideal for anonymous sign-ups or testing without personal email exposure.
- **Testing**: Perfect for developers automating workflows or validating email systems.
- **Ease**: Simple JSON-based endpoints with free access to start.

## 📚 API Endpoints

| Endpoint           | Method | Description                              | Request Example                          |
|--------------------|--------|------------------------------------------|------------------------------------------|
| `/generate-email`  | POST   | Generate a temporary Gmail address.      | `{"email": ["Gmail"]}`                |
| `/message-list`    | POST   | Retrieve message list for an email.      | `{"email": "user@gmail.com"}`           |
| `/message-details` | POST   | Get detailed info for a specific message.| `{"email": "user@gmail.com", "message_id": "id"}` |

### Sample Response
- `/generate-email`: `{"email": "temp123@gmail.com"}`
- `/message-list`: `{"messages": [{"messageID": "id", "from": "sender", "subject": "subject", "time": "time"}]}`
- `/message-details`: `{"id": "message_id", "from": "sender", "subject": "subject", "time": "time", "refined_content": "text"}`

### Get API and Key from
[Link to API](https://rapidapi.com/canvabouys/api/free-gmail-api){:target="_blank"}

## 📜 Terms of Service
Use responsibly. No spamming or illegal activities.
