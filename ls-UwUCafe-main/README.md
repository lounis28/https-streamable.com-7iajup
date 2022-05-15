# ls-UwUCafe
UwU Cafe job for Gabz UwU Cat Cafe map for QBCore

# Privew
https://streamable.com/7iajup

# Add to qb-core/shared/items.lua
```
	-- mt-UwUCafe
	-- ingredientes
	["pacote-leite"] 		 = {["name"] = "pacote-leite", 					["label"] = "Pacote de leite", 					    ["weight"] = 1500, 		["type"] = "item", 			["image"] = "leite.png", 				["unique"] = false, 	["useable"] = true, 	["shouldClose"] = true,    ["combinable"] = nil,   ["description"] = ""},
	["barra-manteiga"] 		 = {["name"] = "barra-manteiga", 				["label"] = "Barra de manteiga", 					["weight"] = 1500, 		["type"] = "item", 			["image"] = "manteiga.png", 			["unique"] = false, 	["useable"] = true, 	["shouldClose"] = true,    ["combinable"] = nil,   ["description"] = ""},
	["pacote-farinha"] 		 = {["name"] = "pacote-farinha", 				["label"] = "Pacote de farinha", 					["weight"] = 1500, 		["type"] = "item", 			["image"] = "farinha.png", 				["unique"] = false, 	["useable"] = true, 	["shouldClose"] = true,    ["combinable"] = nil,   ["description"] = ""},
	["barra-chocolate"] 	 = {["name"] = "barra-chocolate", 				["label"] = "Barra de chocolate", 					["weight"] = 1500, 		["type"] = "item", 			["image"] = "chocolate.png", 			["unique"] = false, 	["useable"] = true, 	["shouldClose"] = true,    ["combinable"] = nil,   ["description"] = ""},
	["caixa-morangos"] 		 = {["name"] = "caixa-morangos", 				["label"] = "Caixa de morangos", 					["weight"] = 1500, 		["type"] = "item", 			["image"] = "morangos.png", 			["unique"] = false, 	["useable"] = true, 	["shouldClose"] = true,    ["combinable"] = nil,   ["description"] = ""},
	["limao"] 		         = {["name"] = "limao", 					    ["label"] = "Limão", 					            ["weight"] = 1500, 		["type"] = "item", 			["image"] = "limao.png", 				["unique"] = false, 	["useable"] = true, 	["shouldClose"] = true,    ["combinable"] = nil,   ["description"] = ""},
	["pacote-natas"] 		 = {["name"] = "pacote-natas", 					["label"] = "Pacote de natas", 					    ["weight"] = 1500, 		["type"] = "item", 			["image"] = "natas.png", 				["unique"] = false, 	["useable"] = true, 	["shouldClose"] = true,    ["combinable"] = nil,   ["description"] = ""},
	["leite-condensado"] 	 = {["name"] = "leite-condensado", 				["label"] = "Leite condensado", 					["weight"] = 1500, 		["type"] = "item", 			["image"] = "condensado.png", 			["unique"] = false, 	["useable"] = true, 	["shouldClose"] = true,    ["combinable"] = nil,   ["description"] = ""},
	["extrato-baunilha"] 	 = {["name"] = "extrato-baunilha", 				["label"] = "Extrato de baunilha", 					["weight"] = 1500, 		["type"] = "item", 			["image"] = "baunilha.png", 			["unique"] = false, 	["useable"] = true, 	["shouldClose"] = true,    ["combinable"] = nil,   ["description"] = ""},
	["pacote-acucar"] 		 = {["name"] = "pacote-acucar", 				["label"] = "Pacote de açucar", 					["weight"] = 1500, 		["type"] = "item", 			["image"] = "acucar.png", 				["unique"] = false, 	["useable"] = true, 	["shouldClose"] = true,    ["combinable"] = nil,   ["description"] = ""},
	["frasco-nutela"] 		 = {["name"] = "frasco-nutela", 				["label"] = "Frasco de Nutela", 					["weight"] = 1500, 		["type"] = "item", 			["image"] = "nutela.png", 				["unique"] = false, 	["useable"] = true, 	["shouldClose"] = true,    ["combinable"] = nil,   ["description"] = ""},
	["pacote-oreo"] 		 = {["name"] = "pacote-oreo", 					["label"] = "Pacote de Oreo", 					    ["weight"] = 1500, 		["type"] = "item", 			["image"] = "oreo.png", 				["unique"] = false, 	["useable"] = true, 	["shouldClose"] = true,    ["combinable"] = nil,   ["description"] = ""},
	["extrato-menta"] 		 = {["name"] = "extrato-menta", 				["label"] = "Extrato de menta", 					["weight"] = 1500, 		["type"] = "item", 			["image"] = "menta.png", 				["unique"] = false, 	["useable"] = true, 	["shouldClose"] = true,    ["combinable"] = nil,   ["description"] = ""},
	["caixa-amoras"] 		 = {["name"] = "caixa-amoras", 					["label"] = "Caixa de amoras", 					    ["weight"] = 1500, 		["type"] = "item", 			["image"] = "amoras.png", 				["unique"] = false, 	["useable"] = true, 	["shouldClose"] = true,    ["combinable"] = nil,   ["description"] = ""},
	["graos-cafe"] 		     = {["name"] = "graos-cafe", 					["label"] = "Grãos de café", 					    ["weight"] = 1500, 		["type"] = "item", 			["image"] = "graoscafe.png", 			["unique"] = false, 	["useable"] = true, 	["shouldClose"] = true,    ["combinable"] = nil,   ["description"] = ""},
	["frango"] 		         = {["name"] = "frango", 					    ["label"] = "Frango", 					            ["weight"] = 1500, 		["type"] = "item", 			["image"] = "frango.png", 			["unique"] = false, 	["useable"] = true, 	["shouldClose"] = true,    ["combinable"] = nil,   ["description"] = ""},

	-- comidas
	["cupcake-morango"] 	 = {["name"] = "cupcake-morango", 					["label"] = "Cupcake de morango", 					["weight"] = 1000, 		["type"] = "item", 			["image"] = "cupmorango.png", 				["unique"] = false, 	["useable"] = true, 	["shouldClose"] = true,    ["combinable"] = nil,   ["description"] = ""},
	["cupcake-chocolate"] 	 = {["name"] = "cupcake-chocolate", 				["label"] = "Cupcake de chocolate", 				["weight"] = 1000, 		["type"] = "item", 			["image"] = "cupchocolate.png", 			["unique"] = false, 	["useable"] = true, 	["shouldClose"] = true,    ["combinable"] = nil,   ["description"] = ""},
	["cupcake-limao"] 		 = {["name"] = "cupcake-limao", 					["label"] = "Cupcake de limao", 					["weight"] = 1000, 		["type"] = "item", 			["image"] = "cuplimao.png", 				["unique"] = false, 	["useable"] = true, 	["shouldClose"] = true,    ["combinable"] = nil,   ["description"] = ""},
	["gelado-morango"] 		 = {["name"] = "gelado-morango", 					["label"] = "Gelado de morango", 					["weight"] = 1000, 		["type"] = "item", 			["image"] = "gemorango.png", 				["unique"] = false, 	["useable"] = true, 	["shouldClose"] = true,    ["combinable"] = nil,   ["description"] = ""},
	["gelado-chocolate"] 	 = {["name"] = "gelado-chocolate", 					["label"] = "Gelado de chocolate", 					["weight"] = 1000, 		["type"] = "item", 			["image"] = "gechocolate.png", 				["unique"] = false, 	["useable"] = true, 	["shouldClose"] = true,    ["combinable"] = nil,   ["description"] = ""},
	["gelado-baunilha"] 	 = {["name"] = "gelado-baunilha", 					["label"] = "Gelado de baunilha", 					["weight"] = 1000, 		["type"] = "item", 			["image"] = "gemorango.png", 				["unique"] = false, 	["useable"] = true, 	["shouldClose"] = true,    ["combinable"] = nil,   ["description"] = ""},
	["panqueca-nutela"] 	 = {["name"] = "panqueca-nutela", 					["label"] = "Panqueca de Nutela", 					["weight"] = 1000, 		["type"] = "item", 			["image"] = "panutela.png", 				["unique"] = false, 	["useable"] = true, 	["shouldClose"] = true,    ["combinable"] = nil,   ["description"] = ""},
	["panqueca-oreo"] 		 = {["name"] = "panqueca-oreo", 					["label"] = "Panqueca de Oreo", 					["weight"] = 1000, 		["type"] = "item", 			["image"] = "paoreo.png", 				    ["unique"] = false, 	["useable"] = true, 	["shouldClose"] = true,    ["combinable"] = nil,   ["description"] = ""},
	["waffle-nutela"] 		 = {["name"] = "waffle-nutela", 					["label"] = "Waffle de nutela", 					["weight"] = 1000, 		["type"] = "item", 			["image"] = "wnutela.png", 				    ["unique"] = false, 	["useable"] = true, 	["shouldClose"] = true,    ["combinable"] = nil,   ["description"] = ""},
	["pastel-frango"] 		 = {["name"] = "pastel-frango", 					["label"] = "Pastel de frango", 					["weight"] = 1000, 		["type"] = "item", 			["image"] = "pfrango.png", 				    ["unique"] = false, 	["useable"] = true, 	["shouldClose"] = true,    ["combinable"] = nil,   ["description"] = ""},
	["muffin-chocolate"]     = {["name"] = "muffin-chocolate", 				    ["label"] = "Muffin de chocolate", 					["weight"] = 1000, 		["type"] = "item", 			["image"] = "mufchocolate.png", 		    ["unique"] = false, 	["useable"] = true, 	["shouldClose"] = true,    ["combinable"] = nil,   ["description"] = ""},

	-- bebidas
	["cafe-uwu"] 		  = {["name"] = "cafe-uwu", 					["label"] = "Café", 					["weight"] = 1000, 		["type"] = "item", 			["image"] = "cafe.png", 				["unique"] = false, 	["useable"] = true, 	["shouldClose"] = true,    ["combinable"] = nil,   ["description"] = ""},
	["latte-uwu"] 		  = {["name"] = "latte-uwu", 				    ["label"] = "Latte", 					["weight"] = 1000, 		["type"] = "item", 			["image"] = "latte.png", 				["unique"] = false, 	["useable"] = true, 	["shouldClose"] = true,    ["combinable"] = nil,   ["description"] = ""},
	["bubble-amora"]      = {["name"] = "bubble-amora", 				["label"] = "Bubble Tea de amora", 		["weight"] = 1000, 		["type"] = "item", 			["image"] = "btamora.png", 				["unique"] = false, 	["useable"] = true, 	["shouldClose"] = true,    ["combinable"] = nil,   ["description"] = ""},
	["bubble-menta"] 	  = {["name"] = "bubble-menta", 				["label"] = "Bubble Tea de menta", 		["weight"] = 1000, 		["type"] = "item", 			["image"] = "btmenta.png", 				["unique"] = false, 	["useable"] = true, 	["shouldClose"] = true,    ["combinable"] = nil,   ["description"] = ""},
	["bubble-morango"] 	  = {["name"] = "bubble-morango", 			    ["label"] = "Bubble Tea de morango", 	["weight"] = 1000, 		["type"] = "item", 			["image"] = "btmorango.png", 			["unique"] = false, 	["useable"] = true, 	["shouldClose"] = true,    ["combinable"] = nil,   ["description"] = ""},
	["milkshake-morango"] = {["name"] = "milkshake-morango", 	        ["label"] = "Milkshake de morango", 	["weight"] = 1000, 		["type"] = "item", 			["image"] = "msmorango.png", 			["unique"] = false, 	["useable"] = true, 	["shouldClose"] = true,    ["combinable"] = nil,   ["description"] = ""},
	["milkshake-chocolate"] = {["name"] = "milkshake-chocolate", 	    ["label"] = "Milkshake de chocolate", 	["weight"] = 1000, 		["type"] = "item", 			["image"] = "mschocolate.png", 			["unique"] = false, 	["useable"] = true, 	["shouldClose"] = true,    ["combinable"] = nil,   ["description"] = ""},
```

# Drag and drop images from mt-UwUCafe/images to qb-inventory/html/images.

# Add to qb-core/shared/jobs.lua
```
    ['uwu'] = {
		label = 'UwU Cat Cafe',
		defaultDuty = true,
		offDutyPay = false,
		grades = {
            ['0'] = {
                name = 'Novice',
                payment = 50
            },
			['1'] = {
                name = 'Employee',
                payment = 75
            },
			['2'] = {
                name = 'Experienced',
                payment = 100
            },
			['3'] = {
                name = 'Advanced',
                payment = 125
            },
			['4'] = {
                name = 'Boss',
				isboss = true,
                payment = 150
            },
        },
	},
  ```
  
  # Add to dpemotes/client/AnimationList.lua

```
["bubbletea"] = {"amb@world_human_drinking@coffee@male@idle_a", "idle_c", "", AnimationOptions = { Prop = 'apa_prop_cs_plastic_cup_01', PropBone = 28422, PropPlacement = {0.0, 0.0, 0.0, 0.0, 0.0, 0.0}, EmoteLoop = true, EmoteMoving = true, }}, ["misosoup"] = {"amb@world_human_drinking@coffee@male@idle_a", "idle_c", "", AnimationOptions = { Prop = 'v_ret_247_noodle1', PropBone = 28422, PropPlacement = {0.0, 0.0, 0.0, 0.0, 0.0, 0.0}, EmoteLoop = true, EmoteMoving = true, }}, ["uwusandy"] = {"mp_player_inteat@burger", "mp_player_int_eat_burger", "", AnimationOptions = { Prop = 'ng_proc_food_ornge1a', PropBone = 18905, PropPlacement = {0.13, 0.05, 0.02, -50.0, 16.0, 60.0}, EmoteMoving = true, }}, ["budhabowl"] = {"anim@scripted@island@special_peds@pavel@hs4_pavel_ig5_caviar_p1", "base_idle", "", AnimationOptions = { Prop = "prop_cs_bowl_01b", PropBone = 60309, PropPlacement = {0.0, 0.0300, 0.0100, 0.0, 0.0, 0.0}, SecondProp = 'h4_prop_h4_caviar_spoon_01a', SecondPropBone = 28422, SecondPropPlacement = {0.0,0.0,0.0,0.0,0.0,0.0}, EmoteLoop = true, EmoteMoving = true, } },
```
  
  # Dependicies
  - qb-target - https://github.com/qbcore-framework/qb-target
  - qb-menu - https://github.com/qbcore-framework/qb-menu
  - qb-input - https://github.com/qbcore-framework/qb-input
  - dpemotes - https://github.com/qbcore-framework/dpemotes (For eat animations)
  - qb-phone - https://github.com/qbcore-framework/qb-phone (for billing recive) 
  
  # Link to buy the map 
  https://fivem.gabzv.com/package/4724734

  
