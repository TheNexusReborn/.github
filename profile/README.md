## Hi there and thank you for your interest in The Nexus Reborn
The main goal of this project is to bring back some of The Nexus MC's game modes, mainly Survival Games and MCSwat. We do have some plans in regards to other gamemodes, but these will mostly be decided upon by the community when the time comes

You are free to fork/clone the repositories here as you see fit, however the code and projects are highly tailored to The Nexus Reborn specifically. However I do plan on splitting some of these things into their own libraries.
At this time, we use Java 8 and Spigot 1.8.8. However there are some plans to change this in the future

Please feel free to contribute to the project as you see fit, please make sure you follow proper Java Naming Conventions

The Project is divided into some things to make it easier. 

NexusAPI contains all the things that are not specific to Minecraft based coding and does not depend on any of the Spigot Jar Files
NexusCore is the main plugin for all of the Minecraft Spigot Servers and all of them run this plugin. 
NexusProxy is the plugin that is on the BungeeCord Proxy Server and does the same things as NexusCore
NexusHub is the plugin for the Hub Servers
NexusSurvivalGames is the plugin for the Survival Games gamemode

All of these use the Maven build tool, so all you have to do is download them and import using Maven
