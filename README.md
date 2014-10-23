Dead-Hills-SK
=============
Credit:
	Blitter - Author
	
	 ??????	- Edited for SK use


 Modified for Raid Druid usage on other toons - Necrognomie
 	Re-aligned spacing
	Modified the "get instance" for timing and to close quest windows on all toons
	Added wait4res support/triggers
	Added AA Purchase support
	Adjusted to use MQ2Cast_Spell_Routines for better item cast handling
	Added a "group status" check and pause to wait for mana/end as needed.

	
 Required files:
	wait4res.inc
	AApurchase.inc
	MQ2SpellRoutines.inc
	Deadzone.mac
	Hillinto_sk.ini


 Required Plugins:
	MQ2MoveUtils
	MQ2Advpath (optional, adjust return commands if you don't have/want to use)


 Run /mac dead2sk once then /end it to generate an ini. It will be called DH_SK_<toon name>.ini, open and edit!

 

 This macro is untested with mercs, but it should still work with them.

 There is a 100s delay at the start of every heroic for rebuffs defined in your ini.  Asjust as needed.

 If you usecampfire make sure you have 3 people in your FS in the group otherwise you will get spammed trying to create a campfire.

 Set up your other toons to follow the SK. There are appropriate places to /bc the commands.

 This version utilizes a recorded path back from Cogwitz (the end guy you hail) to Gribble. Refer to the portion of this macro set up to hail Cogwitz and change it unless you record your own path. This was done to fix stuck characters on my end.
