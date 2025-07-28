
## Architecture
```mermaid
graph TD
    A[User Voice] --> B[Browser]
    B --> C[Cloudflare Worker]
    C --> D[Gemini AI]
    D --> C --> B --> E[Voice Response]
