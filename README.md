# Realtime Chat (Node.js + Express + Socket.IO)

A minimal real-time chat example using Node.js, Express and Socket.IO.

## Quick start (Windows PowerShell)

1. Install dependencies:

```powershell
cd "c:\Users\vella\OneDrive\Desktop\Rm\realtime-chat"
npm install
```

2. Start the server:

```powershell
npm start
```

3. Open http://localhost:3000 in your browser. Open multiple tabs to test realtime messaging.

## Files

- `server.js` - Express server + Socket.IO handlers
- `public/index.html` - client UI
- `public/client.js` - client-side Socket.IO logic
- `public/styles.css` - simple styling

## Notes

This is a small demo and stores messages in memory. For production use, add persistence, authentication, rate-limiting and secure headers.
