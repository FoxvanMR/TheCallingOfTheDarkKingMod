# The Calling of the Dark King mod

- Estado: Alpha 0.6.3 / En desarrollo.
- State: Alpha 0.6.3 / In development

Mod de Hollow Knight que actualmente añade 4 amuletos, 7 enemigos y 2 salas de pruebas, más un pequeño lobby.
A Hollow Knight mod that currently adds 4 charms, 7 enemies, and 2 challenge rooms, plus a small lobby.

La información detallada de todas las características del mod se encuentra en \TheCallingOfTheDarkKingMod\Mod_Info\.
Detailed information on all the mod's features can be found in \TheCallingOfTheDarkKingMod\Mod_Info\.

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
- Remanente infectado. Deja una pequeña sombra detrás del jugador y explota al cabo de un tiempo.
- Aguijón y ALMA. Las Artes del aguijón consumen ALMA y potencian su daño.
- Precio del ALMA. Permite gastar Geo para lanzar un hechizo cuando no se tiene ALMA suficiente.

Añade 7 enemigos nuevos:

- Gruzzer del Vacío. Al morir, explota y expulsa púas explosivas en 4 direcciones.
- Gruzzer del Vacío inestable. Lanza púas explosivas en dirección al caballero, y al morir, explota y expulsa púas explosivas en 4 direcciones y una siempre hacia el caballero.
- Saco de Gruzzers. Con el tiempo y a cierto rango, va expulsando "Gruzzers del Vacío" hasta morir por su cuenta o por el caballero.
- Trepasombras de Darkyrita. Versión más rápida y agresiva de un "Trepasombras". Al estar a cierto rango, carga contra el caballero.
- Cáscara oxidada alada. Suelta bombas de Darkyrita el estar debajo de ella.
	- Se necesita quitarle la coraza antes de dañarla permanentemente, si no se consigue matarla, recuperará su coraza.
- Birrormiga de cueva. Se mantiene siempre a una distancia prudencial del caballero y escupe proyectiles en su dirección.
- Cáscara minera oxidada. Enemigo lento pero resistente.
	- Golpea con fuerza si se encuentra cerca, expulsar proyectiles pegajosos si se encuentra lejos y cubrirse de ataques que vengan por arriba.
 	- Se necesita quitarle la armadura antes de dañarla permanentemente, si no se consigue matarla, recuperará su armadura.

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
  		- Small area: If the Knight enters this area, the Antter will try to move away from him.
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
