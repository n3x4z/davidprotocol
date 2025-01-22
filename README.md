# davidProtocol
A fast & universal protocol base, built from the ground up to be open and modular. Written in C. Designed to handle many tasks under a single software, and hence under one port (eg: chat server and an API endpoint, or game server, or whatever fit your addition is).

In simple words - you compile davidProtocol's base, with your needs (modules) hooked up to it, then just boot it up and its as if multiple server software was running under the single davidprotocol one. Example: You compile base + your own basic chat module + your own game server module. You then start it up, open your chat app and connect to the server as you would with anything else. Then, at the same time, you boot up your game client, and connect to the server too. Both chat and game use the same server port, and davidProtocol manages communication between clients and server modules. You save on host ports, potentially resources too, and you centralize multiple things onto single ports.

## Licensing
davidProtocol code written by the owner of the repository and any contributors is fully licensed under the project license (Apache 2.0 as of writing this). Any other code is otherwise licensed under their own licenses - so do keep in mind those parts may not match the overall project license

## Description
davidProtocol began as an experiment to see just how much you can squeeze a single server software to run multiple things using the least resources. Of course, this power shouldn't be abused to centralize everything, as excessive centralization can, for some stuff, cause issues.

