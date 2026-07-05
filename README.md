# Proxy

A simple web proxy server built with Node.js and Express. It fetches content from a given URL and pipes it back to the client.

## Usage

Navigate to the app and use the `/get` endpoint with a `url` query parameter:

```
/get?url=https://example.com
```

## Running locally

```bash
npm install
node index.js
```

The server listens on port 5000 by default.

## Tech stack

- [Express](https://expressjs.com/) — web framework
- [Helmet](https://helmetjs.github.io/) — security headers
- [request](https://github.com/request/request) — HTTP proxying
