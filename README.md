# Colton's Minecraft Adventure Server

This project is for a Webelos Cub Scout elective called "Game Design".  We are trying to create a game that will allow players to quest for items then trade those items for clues on how to complete the next step of the game.  It seems like the shopkeepers plugin might help with this.

This server is based on what seems to be the very cool [docker-minecraft-server](https://github.com/itzg/docker-minecraft-server) project by [Itzg](https://github.com/itzg).

This installs a [Bukkit/Spigot server](https://getbukkit.org/) so we can install the following mods:

 * [bukkit-plugins/shopkeepers](https://www.curseforge.com/minecraft/bukkit-plugins/shopkeepers)
 

## Installation

 * clone this project
 * copy the shopkeepers jar file to data/mc/plugins directory

## Usage

to start server:

    docker-compose up

to stop server:

    docker-compose down


## TODO

 * Once we figure out all the plugins and config we need, then we will bake this into our own docker image.