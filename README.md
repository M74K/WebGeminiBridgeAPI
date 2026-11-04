# GeminiWebBridgeAPI

**Use Google Gemini Web as an OpenAI-compatible API.**

GeminiWebBridgeAPI is a lightweight Python application that allows you to use Gemini Web models through a local OpenAI-compatible API.

Instead of using the official Gemini API, it connects to your existing authenticated Gemini Web session.

## ✨ Features

OpenAI-compatible API

Gemini Web session authentication

Automatic model discovery

Multiple Gemini models

Streaming responses

Local HTTP server

Easy terminal configuration

## 🖥️ Platform Support

- ✅ Windows — currently supported.
- 🔜 Linux — planned.
- 🔜 macOS — planned.

Currently, GeminiWebBridge is available only for Windows. Support for Linux and macOS is planned for future releases.

## 🚀 Installation

Step 1. Clone the repository:

```bash
git clone https://github.com/YOUR_USERNAME/GeminiWebBridge.git
```

Step 2. Open the project folder:

```bash
cd GeminiWebBridge
```

Step 3. Run the application:

```bat
start.bat
```

Step 4. Follow the instructions in the terminal to configure your Gemini session.

## 📡 API Example

```json
{
  "model": "gemini-3.8-flash",
  "messages": [
    {
      "role": "user",
      "content": "Hello, Gemini!"
    }
  ],
  "stream": true
}
```

## ⚠️ Disclaimer

GeminiWebBridge is an unofficial project and is not affiliated with Google.

It uses internal Gemini Web communication mechanisms that may change without notice.

Keep your Gemini session cookies private and never share them publicly.
