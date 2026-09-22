# Square Era Database - Room 1: Sanctuary Hub

Persistent world modifications, player profiles, and session state for Square Era 3D Voxel Sandbox Room 1.

## Room Overview
- Room ID: 1
- Room Name: Sanctuary Hub
- Game Mode: CREATIVE
- Description: Community Creative Sanctuary Hub, AI Sanctuary sector builds and collaborative voxel architecture.
- Server Repository: [yasamarium/square-era-server-room1](https://github.com/yasamarium/square-era-server-room1)

## Schema & Files
- `data/world.json`: JSON map of persistent chunk modifications `[ ["x,y,z", blockId], ... ]`.
- `data/players.json`: Registered player profiles and session records.
- `data/chat.json`: Persistent in-room chat history.
- `data/sessions.json`: 5-hour runner cycle timestamps and synchronization checkpoints.

Zero external databases required. Backed 100% by GitHub Git persistence.
