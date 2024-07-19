# Encoded-Cardboard-Pistol
Encoded Cardboard Pistol


Custom Addon Cardboard Pistol (fully animated)

damage can be adjusted in metadata if needed.

copy and paste into ox_inventory/data/weapons.lua

		['WEAPON_CARDBOARDPISTOL'] = {
			label = 'CardBoard Pistol',
			weight = 1180,
			durability = 0.03,
			ammoname = 'ammo-card',
			description = '',
		},

this must be under ammo in weapons.lua

		['ammo-card'] = {
			label = 'Cardboard Pallets',
			weight = 1,
		},
