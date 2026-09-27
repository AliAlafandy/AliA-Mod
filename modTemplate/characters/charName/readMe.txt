There you can put your character.

-----------------------------------------------------------------------------------

How animations work on character folder:

✓ Learning by Ali Alafandy ✓

charName.json:
	# you can change charName.png into anyThing.png but you should change charName.xml like png one and edit on charName.json in "image": "anyThing".
	# assets animations inside "name"
		• idle
		• waiting
		• walking
		• running
		• stop
		• fall
		• jumping
		• up
		• down
		• power
		• victory
		• gameOver

@ option: If character has an extra animations:
	@ option1 • put it on charName.png
	@ option2 • put it on charName_anim.png # _anim can be your animation name
	# if you make charName_anim.png:
	• edit on charName.json
		{
			"anim": {
				[
					"name": "your_animation",
					"image": "charName_anim"
				]
			}
		}
