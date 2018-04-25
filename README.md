# RealTimeDataDevliveryUsingWebsocketwithSpringBoot

The traditional approach to handing out clients data in real-time (or quasi-real-time) was to make clients poll the server at regular intervals. This could be achieved by a simple polling (say, every 5 seconds), or long-polling (same as the other, but with longer-lasting sockets and late responses), but now there are new kids in town. The new approach to this situation is to let the server push the data using a publish/subscribe mechanism, rather than the client pulling them in, and technologies like Comet, WebSocket, Server-Sent Events were created for this exact purpose.

This article will demonstrate a simple guestbook app that uses the WebSocket method, and will feature Spring Boot and STOMP on the server side, and SockJS and stomp.js on the client side.

# Run This App

gradle bootRun

open below url

http://localhost:8080
