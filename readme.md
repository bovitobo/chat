Channels allows you to use WebSockets and other non-HTTP protocols in your Django site.
For example you might want to use WebSockets to allow a page on your site to immediately
receive updates from your Django server without using HTTP long-polling or other expensive techniques.

In this Demo I built a simple chat server, where you can join an online room,
post messages to the room, and have others in the same room see those messages immediately.

Open a browser tab to the room page at http://127.0.0.1:8000/chat/lobby/.
Open a second browser tab to the same room page.

In the second browser tab, type the message “hello” and press enter.
You should now see “hello” echoed in the chat log in both the second browser tab and in the first browser tab.

This demo is taken from Tutorial on Channels: https://channels.readthedocs.io/en/latest/tutorial/index.html