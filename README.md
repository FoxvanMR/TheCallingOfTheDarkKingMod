# The Calling of the Dark King mod

Mod de Hollow Knight en desarrollo que actualmente añade 4 amuletos, 6 enemigos y 2 salas de pruebas, más un pequeño lobby.

A Hollow Knight mod currently in development that adds 4 charms, 6 enemies, and 2 challenge rooms, plus a small lobby.

- Estado: Alpha 0.6.1 / En desarrollo.
- State: Alpha 0.6.1 / In development

## Requisitos / Requirements

- Lumalfy
- Hollow Knight Modding API
- SFCore
- Satchel

## Instalación / Installation

ES: 

Extrae la carpeta TheCallingOfTheDarkKingMod dentro de: 

	Hollow Knight/hollow_knight_Data/Managed/Mods/ 
	
Si no existe, créala. Luego ejecuta el juego con Lumafly (Ejecutar con mods) con este mod y los otros activados.

EN: 

Extract the TheCallingOfTheDarkKingMod folder into: 

	Hollow Knight/hollow_knight_Data/Managed/Mods/ 
	
If it doesn't exist, create it. Then launch the game using Lumafly (Launch with mods) with this mod and the others enabled.

## Contenido actual / Current content

ES:

Añade 4 amuletos nuevos:

- Corazón de Darkyrita. Tiene efecto de escudo salvavidas al estar a un golpe de la muerte.
	- Sinergias:
		- Canción de larvas y Espinas de agonía: Se activan al recibir daño incluso estando invencible.
  		- Coraza de baldur: Si ambos escudos están activos, el de Darkyrita no recibirá daño y no descontará tiempo por golpe a su duración.
- Remanente infectado. Deja una pequeña sombra detrás del jugador y explota al cabo de un tiempo.
	- Sinergias:
		- Piedra de chamán: El daño y el área de la sombra se incrementan.
		- Sombra afilada: La sombra explota y se recarga antes.
		- Blasón del defensor: La sombra al explotar deja un remanente que expulsa ondas de daño.
- Aguijón y ALMA. Las Artes del aguijón consumen ALMA y potencian su daño.
	- Sinergias:
		- Piedra de chamán: El daño de las habilidades se incrementa.
		- Tuercehechizos: El coste de las habilidades se reduce.
- Precio del ALMA. Permite gastar Geo para lanzar un hechizo cuando no se tiene ALMA suficiente.
	- Sinergias:
		- Codicia irrompible: La conversión Geo - ALMA se reduce.
		- Enjambre recolector: El tiempo de espera del amuleto se reduce.
  		- Aguijón y ALMA: Funciona con las Artes del aguijón potenciadas.

Añade 6 enemigos nuevos:

- Gruzzer del Vacío:
	- Tiene dos clases: Base y estático.
		- Base: Sigue el mismo patrón de movimiento que un Gruzzer del juego base.
		- Estático: Se mueve ligeramente hacia arriba y hacia abajo en la misma posición.
	- Al morir expulsa 4 púas que explotan si: tocan al caballero, otros enemigos, el entorno o si el caballero las golpea.
   		- Ls púas de todos los Gruzzers del Vacío pueden matar a otros Gruzzers del Vacío activando una reacción en cadena. 
     	- También puedes recargar el salto si les haces un 'pogo'.
- Gruzzer del Vacío inestable:
	- Tiene dos clases: Básico y estático.
		- Base: Sigue el mismo patrón de movimiento que un Gruzzer del juego base.
		- Estático: Se mueve ligeramente hacia arriba y hacia abajo en la misma posición.
	- Tiene un área de detección que, si el caballero entra, activará su modo agresivo y no dejará de perseguirlo hasta que el Gruzzer del Vacío inestable muera o el caballero salga de la sala.
 	- Cada cierto tiempo dispara una púa explosiva en dirección al caballero si este se encuentra lo suficientemente cerca.
	- Al morir, expulsa 4 púas y una de ellas siempre será en dirección al caballero, que explotan si: tocan al caballero, otros enemigos, el entorno o si el caballero las golpea.
- Saco de Gruzzers:
	- Tiene un área de detección que, si el caballero entra, escupirá hasta 3 Gruzzers del Vacío cada cierto tiempo con una probabilidad de que sea un Gruzzer del Vacío inestable.
	- Si expulsa los 3 Gruzzers del Vacío sin morir, la siguiente vez, en lugar de expulsar solo uno, explotará y lanzará dos Gruzzers del Vacío a la vez, con la posibilidad de que sean Gruzzers del Vacío inestables.
	- Si el caballero lo mata no lanzará ninguno.
- Trepasombras de Darkyrita:
	- Se mueve un poco más rápido que un Trepasombras del juego base.
 	- Tiene una pequeña área delante de él que si el caballero entra, hará que el Trepasombras de Darkyrita, después de una pequeña pausa, haga un esprint hacia el caballero.
  	- Inflige dos máscaras de daño al chocarse contra él.
- Cáscara oxidada alada:
	- Se mueve ligeramente hacia arriba y hacia abajo en la misma posición.
 	- Tiene dos tipos de vida:
  		- Vida acorazada: No puedes ganar ALMA al golpearle.
    	- Vida vulnerable: Puedes ganar ALMA al golpearle.
     	- Al romperle la coraza se quedará un tiempo vulnerable.
      	- Si el caballero no lo mata a tiempo, recuperará la coraza completamente.
	- Tiene un rango hacia abajo; si el caballero entra dejará caer una bomba de Darkyrita.
		- Esta explota al tocar al caballero, otros enemigos, el entorno o si el caballero la golpea.
  		- Inflige dos máscaras de daño.
    	- Al lanzarla entrará en un pequeño tiempo de espera.
- Birrormiga de cueva:
	- Va siguiendo un patrón de movimiento aleatorio hasta llegar a un borde o chocarse con una plataforma.
 	- Inflige dos máscaras de daño al chocarse contra ella.
 	- Al entrar en su área de detección se activarán otras dos áreas adicionales:
  		- Área pequeña: Si el caballero entra en esta, la Birrormiga intentará alejarse.
    	- Área Grande: Si el caballero entra en esta, la Birrormiga intentará acercarse.
     	- Área Central: La Birrormiga se quedará quieta.
      	- Cada cierto tiempo lanza 8 proyectiles directos al caballero, 5 por detrás de ella y 3 por delante.
      	- Si el caballero se aleja por mucho tiempo o se esconde, volverá a su ciclo de movimiento aleatorio.

EN:

Adds 4 new charms:

- Heart of Darkyrite. Provides a life-saving shield effect when one hit away from death.
	- Synergies:
		- Combines with all charms that activate upon receiving redamage.
		- Hiveblood: The shield lasts long enough to receive the passive heal.
		- Baldur Shell: When healing with both shields active, the Baldur shield takes no damage.
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

Adds 6 new enemies:

- Void Gruzzer:
	- It has two types: Base and Static.
		- Base: Follows the same movement pattern as a base game Gruzzer.
		- Static: Moves slightly up and down in the same position.
	- Upon death, it ejects 4 spikes that explode if: they touch the Knight, other entities, the environment, or if the Knight hits them.
 		- The spikes of all Gruzzers can kill other Gruzzers by triggering a chain reaction.
   		- You can also recharge the jump if you 'pogo' them.
- Unstable Void Gruzzer:
	- It has two types: Base and Static.
		- Base: Follows the same movement pattern as a base game Gruzzer.
		- Static: Moves slightly up and down in the same position.
	- It has a detection area that, if the Knight enters it, will activate its aggressive mode and will relentlessly pursue the knight until one of them dies.
	- Every so often, it fires an explosive spike in the direction of the knight.
	- Upon death, it ejects 4 spikes, one of which will always be aimed at the Knight. These spikes explode if: they touch the Knight, other entities, the environment, or if the Knight hits them.
- Gruzzer Sack:
	- It has a detection area that, if the Knight enters, will begin to eject Void Gruzzers periodically, with a 25% chance of them being Unstable Void Gruzzers.
	- If it spits out the 3 Void Gruzzers without dying, the next time, instead of spitting out just one, it will explode and eject two Void Gruzzers at once, with a chance that they will be Unstable Void Gruzzers.
	- If the Knight kills it, he will not launch any more.
- Darkyrite Creeper:
	- It moves a bit faster than a base game Creeper.
 	- It has a small area in front of it; If the Knight enters it, the Darkyrite Creeper will, after a brief pause, sprint toward the Knight.
  	- Deals 2 mask of damage upon direct contact.
- Rusted Wingmould:
	- It moves slightly up and down in the same position.
 	- It has two types of health:
  		- Armored health: You cannot gain SOUL by hitting it.
    	- Vulnerable health: You can gain SOUL by hitting it.
     	- Once its armor is broken, it will remain vulnerable for a time.
      	- If the knight does not kill it in time, it will fully recover its armor.
      	- It has a downward range; if the Knight enters, it will drop a Darkyrite bomb.
      		- It explodes upon touching the Knight, other enemies, the environment, or if the Knight strikes it.
      	 	- Deals two mask of damage.
      	  	- Upon casting it, it will enter a brief cooldown period.
- Cave Antter:
	- It follows a random movement pattern until it reaches an edge or collides with a platform.
 	- Deals 2 mask of damage upon direct contact.
  	- Upon entering its detection area, two additional areas will be activated:
  		- Small area: If the Knight enters this, the Antter will try to move away from him.
  	 	- Large Area: If the Knight enters this area, the Antter will try to approach him.
  	  	- Central Area: The Antter will remain stationary.
  	  	- Every so often, it fires 8 projectiles directly at the Knight: 5 from behind it and 3 from its front.
  	  	- If the Knight moves away for a long time or hides, it will return to its random movement cycle.

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
