# bt-target or qb-eye
 This is a simple tutorial for the bt-target 

For using the script u will need a few requirements 

https://github.com/Mojito-Fivem/bt-target

https://github.com/mkafrin/PolyZone

Adding the addtional boxes and interactions is into the script u want to interact with not into the bt-target.

In my tutorial i am going to use qb-policejob

First of all i need to add :

	'@PolyZone/client.lua',
	'@PolyZone/BoxZone.lua',
	'@PolyZone/EntityZone.lua',
	'@PolyZone/CircleZone.lua',
	'@PolyZone/ComboZone.lua',

into ur client scripts 
Here is mine :

	'@PolyZone/client.lua',
	'@PolyZone/BoxZone.lua',
	'@PolyZone/EntityZone.lua',
	'@PolyZone/CircleZone.lua',
	'@PolyZone/ComboZone.lua',
	'config.lua',
	'client/main.lua',
	'client/camera.lua',
	'client/interactions.lua',
	'client/job.lua',
	'client/gui.lua',
	'client/heli.lua',
	--'client/anpr.lua',
	'client/evidence.lua',
	'client/objects.lua',
	'client/tracker.lua',


After all for the duty interaction go to :

client/main.lua and add everything from the simpleinteraction.lua


After all of this u have a compleate bt-target for QB core.



