#WebTox

> Bringing Tox to the Browser. 

WebTox wants to bring Tox to the browser. The project wants to make building web applications using Tox as simple as requiring Tox.js .

##RoadMap

![WebTox](images/webtox.png)

Since Browsers don't support UDP due to security reasons WebTox would be implemented with the help of WebRTC. Initially there would be only WebTox clients. They communicate with each other with the help of WebRTC. Since the normal Tox clients don't have WebRTC support there is no way of WebTox clients to communicate with the normal Tox clients. 

This can be fixed by making Hybrid clients. Hybrid clients which runs on server(like Node.js) supports both WebRTC and UDP. They can communicate with both WebTox clients and normal Tox clients. They can pass the messages from Tox clients to WebTox clients and vice versa. 

The hybrid clients can be eliminated once the Tox applications add support WebTox. 


 