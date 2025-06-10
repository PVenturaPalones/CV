# Configuración de DomusCoin

Este directorio contiene archivos de ejemplo para configurar una economía unificada basada en **DomusCoin**.

## PlayerPoints
- Se usa PlayerPoints 3.3.2 como almacenamiento principal.
- Vault 2.11.0 enlaza esta economía con otros plugins.

## MyCommand
- Se crea el comando `/pay` para transferir DomusCoin entre jugadores.
- Mensajes:
  - Al que envía: `&7Le enviaste &6⛃ &5{cantidad} &7a &e{jugador}.`
  - Al que recibe: `&7Recibiste &6⛃ &5{cantidad} &7de &e{jugador}.`

## PicoJobs y NexusAuctionHouse
- Ambos plugins utilizan Vault y reconocen DomusCoin como moneda única.

Los archivos YAML adjuntos deben colocarse en las carpetas de cada plugin dentro del servidor Spigot/Paper.
