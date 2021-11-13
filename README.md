# Minecraft-Mod-Pack-Tutorial
How to write, test and syncronize separate client and server packs. 

# Synopsis
Use a launcher where you can create different profiles, and create different profiles for testing client-side mods, server-side mods (no client mods), client-server-side mods, integration (client-side and client-server-side mods), and distribution (client-side, client-server side mods, client configuration).

Likewise create five different servers for testing: client-side only (no mods on server), server-side only, client-server-side mods, integration (server-side and client-server-side mods), and distribution (server-side, client-server-side mods, server configuration).

I also strongly suggest to create a git repository and set branches and ...(milestones, but different word...)

Follow up with rigorous cross testing of the different profiles against the different servers in order to check compatibility, and to make sure that client side only mods works on client side only and server side only mods doesn't require anythhing on the client.

Read the [wiki](https://github.com/pkej/Minecraft-Mod-Pack-Tutorial/wiki) for details.
