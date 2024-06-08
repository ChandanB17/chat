## Ad hoc E2E Encrypted Group Chat

### What
This project is a fully functional, minimalist, ad hoc, end-to-end encrypted web group chat. It uses websocket for all message delivery which is more reliable than WebRTC.

### Why
At times, there's a need for private, anonymous group chats. Many existing applications with end-to-end encryption are overly complex. Conversely, simpler applications lack both end-to-end encryption and group functionality. Hence, I invested a few days to develop one myself. It primarily serves as a proof of concept.

### How
The backend is implemented using WebSockets written in Golang.

On the client side, I opted for handwritten, plain JavaScript, avoiding the use of complex frameworks.

