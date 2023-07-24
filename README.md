# Real-Time-Chat-Application
A real-time chat application implementation using Socket.io, Node, and React.

INSTRUCTION:
To sign in differently in the app, you can use two different browser tabs to open the same application and chat in real time. There is no session maintained so on every page visit it will ask for signing-in. ( For example you can select Alexa in one tab to sign in and TARS in second tab and then you can send message to TARS from Alexa's tab and you should see an unread message on TARS tab ).

Messages are stored in browser memory so on subsequent refreshes messages will be lost. we could've stored messages on the server's DB, but DB is not in the scenario.
