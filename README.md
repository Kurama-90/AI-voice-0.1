graph LR
    A[User Voice Input] --> B[Browser]
    B --> C[Cloudflare Worker]
    C --> D[Gemini AI]
    D --> C
    C --> B
    B --> E[Voice Response]
