Nueva Project
=============
The OpenTibia revamp project
-------------

OpenTibia has always been a creative platform for people to easily create ideas and worlds from thier heads.
Its been a birthplace for creativity and for people to enter the world of software development.

The project aims to create a more versatile platform for creating player-crafted MMORPG experiences, to do this the project aims to do this:

* Create a WebClient hosted via the server directly (utilizes the same client code).
* A revamped world system to give free-movement to entities.
* Tools for converting the most common project resources (highly focused on custom sprites and projects)
* A modular lazy-loading script system with client-transfer support (via Lua Sandboxing)
* A Client/Server synced UI/Interaction system.
* A open-world focused view give focus on the beautiful mappings of creators.
* Modular system design to extend with new features.
* A Bytecode compression for scripts to lower the data needed, also to protect the scripts a bit more.

The project will be using:
 - Cmake as a build system.
 - C++ for the client and the server.
    - SDL2 for Android/Windows/Web support via OpenGL ES 2 or 3
 - Lua 5.3 for the scripting, Luajit for server
 - Websockets for more support of custom protocols.
 - (Optional) Reliable UDP/Enet could be used for lower latency but only for native clients.
 - Flatbuffers for a fast transfer protocol and file loading.

Currently the project is in the initial phase.
More public documentation will come when a bit maturity has risen.

