# The Calling of the Dark King Mod

Mod de Hollow Knight en desarrollo que actualmente añade 4 amuletos nuevos y 3 enemigos nuevos con 2 salas de pruebas para testearlos.

Hollow Knight mod in development that currently adds 4 new charms and 3 new enemies with 2 testing rooms to try them.

- State: Alpha 0.5.1 / In development
- Estado: Alpha 0.5.1 / En desarrollo.

## Requisitos / Requirements

- Lumalfy
- Hollow Knight Modding API
- SFCore
- Satchel

## Instalación / Installation

ES: 

Extrae la carpeta TheCallingOfTheDarkKingMod dentro de: 

	Hollow Knight/hollow_knight_Data/Managed/Mods/ 
	
Si no existe, creala. Luego ejecuta el juego con Lumafly (Ejecutar con mods).

EN: 

Extract the TheCallingOfTheDarkKingMod folder into: 

	Hollow Knight/hollow_knight_Data/Managed/Mods/ 
	
If it doesn't exist, create it. Then launch the game with Lumafly (Launch with mods).

## Contenido actual / Current content

ES:

Añade 4 amuletos nuevos.

- Corazón de Darkyrita. Tiene efecto de escudo salvavidas al estar a un golpe de la muerte.
	- Sinergias:
		- Combina con todos los amuletos que se activan al recibir daño.
		- Sangrecolmena: El escudo dura lo suficiente para recibir la cura pasiva.
		- Coraza de baldur: Al curarse con ambos escudos activos, el de este no recibe daño.
- Remanente infectado. Deja una pequeña sombra detrás del jugador y explota al cabo de un tiempo.
	- Sinergias:
		- Piedra de chamán: El daño y area de la sombra se incrementan.
		- Sombra afilada: La sombra explota y se recarga antes.
		- Blasón del defensor: La sombra al explotar deja un remanente que expulsa ondas de daño.
- Aguijón y Alma. Las Artes del aguijón consumen ALMA y potencian su daño.
	- Sinergias:
		- Piedra de chamán: El daño de las habilidades se incrementa.
		- Tuercehechizos: El coste de las habilidades se reduce.
- Precio del ALMA. Permite gastar Geo para compensar el ALMA faltante al lanzar un hechizo.
	- Sinergias:
		- Codicia irrompible: El precio de los hechizos se reduce.
		- Enjambre recolector: El tiempo de espera del amuleto se reduce.
  		- Agijón y ALMA: Funciona con las Artes del aguijón potenciadas.

Añade 3 enemigos nuevos.

- Gruzzer del Vacío:
	- Tiene dos tipos: Base y estático.
		- Base: Sigue el mismo patrón de movimiento que un Gruzzer del juego base.
		- Estático: Se mueve ligeramente hacia arriba y hacia abajo en la misma posición.
	- Al morir expulsa 4 púas que explotan si tocan al caballero o al entrorno o si el caballero las golpea.
- Gruzzer del Vacío inestable:
	- Tiene dos tipos: Básico y estático.
		- Base: Sigue el mismo patrón de movimiento que un Gruzzer del juego base.
		- Estático: Se mueve ligeramente hacia arriba y hacia abajo en la misma posición.
	- Tiene un área de detección que, si el caballero entra, activará su modo agresivo y no dejará de perseguirlo hasta que uno de los dos muera.
 	- Cada cierto tiempo dispara una púa explosiva en dirección al caballero.
	- Al morir, expulsa 4 púas y una de ellas siempre será en dirección al caballero, que explotan si tocan al caballero o al entorno o si el caballero las golpea.
- Saco de Gruzzers:
	- Tiene un área de detección que, si el caballero entra, empezará a escupir Gruzzers cada cierto tiempo con un 25% de que sea un Gruzzer Inestable.
	- Al escupir 3 Gruzzers sin morir, la próxima vez, en vez de escupir uno, explotará y expulsará dos Gruzzers a la vez.
	- Si el caballero lo mata no lanzará ninguno.
- Las púas de todos los Gruzzers pueden matar a otros Gruzzers activando una reacción en cadena. También puedes recargar el salto si les haces un 'pogo'.

EN:

Adds 4 new charms.

- Heart of Darkyrite. Provides a life-saving shield effect when one hit away from death.
	- Synergies:
		- Combines with all charms that activate upon receiving redamage.
		- Hiveblood: The shield lasts long enough to receive the passive heal.
		- Baldur Shell: When healing with both shields active, this shield takes no damage.
- Infected Remnant. Leaves a small shadow behind the player and explodes after a short time.
	- Synergies:
		- Shaman Stone: The shadow's damage and area are increased.
		- Sharp Shadow: The shadow explodes and recharges faster.
		- Defender's Crest: Upon exploding, the shadow leaves a remnant that releases waves of damage.
- Nail and Soul. Nail Arts consume Soul and boost their damage.
	- Synergies:
		- Shaman Stone: Nail Arts damage is increased.
		- Spell Twister: Nail Arts cost is reduced. 
- Price of SOUL. Allows to spend Geo to cover the missing SOUL of a spell.
	- Synergies:
		- Unbreakable Greed: Spell prices reduced.
		- Gathering Swarm: Charm cooldown reduced.
		- Nail and SOUL: Works with the powered Nail Arts.

Adds 3 new enemies.

- Void Gruzzer:
	- It has two types: Base and Static.
		- Base: Follows the same movement pattern as a base game Gruzzer.
		- Static: Moves slightly up and down in the same position.
	- Upon death, it ejects 4 spikes that explode if they touch the knight or the environment, or if the Knight hits them.
- Unstable Void Gruzzer:
	- It has two types: Base and Static.
		- Base: Follows the same movement pattern as a base game Gruzzer.
		- Static: Moves slightly up and down in the same position.
	- It has a detection area that, if the knight enters it, will activate its aggressive mode and will relentlessly pursue the knight until one of them dies.
	- Every so often, it fires an explosive spike in the direction of the knight.
	- Upon death, it ejects 4 spikes, one of which will always be aimed at the Knight. These spikes explode if they touch the knight or the environment, or if the Knight hits them.
- Gruzzer Sack:
	- It has a detection area that, if the knight enters, will begin to eject Gruzzers periodically, with a 25% chance of them being Unstable Gruzzers.
	- If it launches 3 Gruzzers without dying, the next time instead of launching one, it will explode and eject two Gruzzers at once.
	- If the Knight kills it, he will not launch any more.
- The spikes of all Gruzzers can kill other Gruzzers by triggering a chain reaction. You can also recharge the jump if you 'pogo' them.

## Comandos de desarrollador / Developer comands

ES:

- F9: Para mostrar las hitboxes de todo lo relacionado con el mod.
- F10: Para teletransportarte a la puerta inicial del mod y recargar salas de pruebas y sus enemigos.

EN:

- F9: To show all mod related hitboxes.
- F10: To teleport the player to the main door of the mod and reload the testing rooms and their enemies.

## Bugs conocidos / Known bugs

ES:

- General:
	- El mod necesita optimizaciones.
 
EN:
- General:
	- Mod needs optimizations.
