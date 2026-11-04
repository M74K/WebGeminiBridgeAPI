# WebGeminiBridgeAPI
### Turn Gemini Web into an OpenAI-compatible API.

WebGeminiBridgeAPI is a lightweight local API bridge that allows you to use Google's Gemini Web interface through an OpenAI-compatible API endpoint.
Instead of using the official Gemini API and managing API keys, WebGeminiBridgeAPI communicates with your existing authenticated Gemini Web session and exposes it through a local HTTP server.
This makes it possible to integrate Gemini Web models into applications and tools that support the OpenAI Chat Completions API.

✨ Features

OpenAI-compatible API — use Gemini Web through the familiar /v1/chat/completions endpoint.

Existing Gemini session — authenticate using your Gemini Web session cookies.

Model discovery — automatically detect available models from your Gemini session.

Multiple models — access supported Gemini models through a single local API.

Streaming support — stream generated responses when supported by the client and bridge.

Local HTTP server — run the bridge locally without deploying an external server.

Simple configuration — configure the Gemini session URL, cookies, host and port through the terminal.
