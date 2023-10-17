# Scissors - a user-focusing API for Minecraft

Until initial release, here a a few things that need to be done:

- Figure out how to upload this to a repository
- API-wise:
  - Message API: Adventure and Components are good and so on, but sometimes a bit too overkill. Nobody needs Components in items. This API is changing this
  - Command API: Bukkit's system is old and outdated as they register a root command node followed by a greedy string argument. This API aims to add a proper command system
- Server-wise:
  - Restart vs. Stop behaviour: As proposed to Paper in https://github.com/PaperMC/Paper/pull/9679, this server change will happen on Scissors


**COMPATIBILITY WITH PAPER/SPIGOT/BUKKIT IS NOT GUARANTEED AT ANY TIME! ANY BREAKING SERVER/API CHANGES MAY AFFECT YOUR PLUGIN! PLEASE FOLLOW THE UPGRADING GUIDE IN ORDER TO NOT LOSE ANY DATA!**
