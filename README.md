## Added weed strains
## Support Discord | https://discord.gg/2DrnWE3CcQ
**Delete your old weed from qb-core/shared/items.lua**

**qb-core/shared/items.lua**
```
-- Joints
	['wwjoint'] 						 = {['name'] = 'wwjoint', 			  	  		['label'] = 'White Widow Joint', 					['weight'] = 0, 		['type'] = 'item', 		['image'] = 'joint.png', 				['unique'] = false, 	['useable'] = true, 	['shouldClose'] = true,    ['combinable'] = nil,   ['description'] = 'Sidney would be very proud at you'},
	['sjoint'] 						 = {['name'] = 'sjoint', 			  	  		['label'] = 'Skunk Joint', 					['weight'] = 0, 		['type'] = 'item', 		['image'] = 'joint.png', 				['unique'] = false, 	['useable'] = true, 	['shouldClose'] = true,    ['combinable'] = nil,   ['description'] = 'Sidney would be very proud at you'},
	['phjoint'] 						 = {['name'] = 'phjoint', 			  	  		['label'] = 'Purple Haze Joint', 					['weight'] = 0, 		['type'] = 'item', 		['image'] = 'joint.png', 				['unique'] = false, 	['useable'] = true, 	['shouldClose'] = true,    ['combinable'] = nil,   ['description'] = 'Sidney would be very proud at you'},
	['ogkjoint'] 						 = {['name'] = 'ogkjoint', 			  	  		['label'] = 'OG Kush Joint', 					['weight'] = 0, 		['type'] = 'item', 		['image'] = 'joint.png', 				['unique'] = false, 	['useable'] = true, 	['shouldClose'] = true,    ['combinable'] = nil,   ['description'] = 'Sidney would be very proud at you'},
	['amjoint'] 						 = {['name'] = 'amjoint', 			  	  		['label'] = 'Amnesia Joint', 					['weight'] = 0, 		['type'] = 'item', 		['image'] = 'joint.png', 				['unique'] = false, 	['useable'] = true, 	['shouldClose'] = true,    ['combinable'] = nil,   ['description'] = 'Sidney would be very proud at you'},
	['akjoint'] 						 = {['name'] = 'akjoint', 			  	  		['label'] = 'AK47 Joint', 					['weight'] = 0, 		['type'] = 'item', 		['image'] = 'joint.png', 				['unique'] = false, 	['useable'] = true, 	['shouldClose'] = true,    ['combinable'] = nil,   ['description'] = 'Sidney would be very proud at you'},
	['zkittlezjoint'] 						 = {['name'] = 'zkittlezjoint', 			  	  		['label'] = 'Zkittlez Joint', 					['weight'] = 0, 		['type'] = 'item', 		['image'] = 'joint.png', 				['unique'] = false, 	['useable'] = true, 	['shouldClose'] = true,    ['combinable'] = nil,   ['description'] = 'Sidney would be very proud at you'},
	['weddingcakejoint'] 						 = {['name'] = 'weddingcakejoint', 			  	  		['label'] = 'Wedding Cake Joint', 					['weight'] = 0, 		['type'] = 'item', 		['image'] = 'joint.png', 				['unique'] = false, 	['useable'] = true, 	['shouldClose'] = true,    ['combinable'] = nil,   ['description'] = 'Sidney would be very proud at you'},
	['dosidosjoint'] 						 = {['name'] = 'dosidosjoint', 			  	  		['label'] = 'Dosidos Joint', 					['weight'] = 0, 		['type'] = 'item', 		['image'] = 'joint.png', 				['unique'] = false, 	['useable'] = true, 	['shouldClose'] = true,    ['combinable'] = nil,   ['description'] = 'Sidney would be very proud at you'},
	['godfatherogjoint'] 						 = {['name'] = 'godfatherogjoint', 			  	  		['label'] = 'Godfather OG Joint', 					['weight'] = 0, 		['type'] = 'item', 		['image'] = 'joint.png', 				['unique'] = false, 	['useable'] = true, 	['shouldClose'] = true,    ['combinable'] = nil,   ['description'] = 'Sidney would be very proud at you'},
	
	-- Weed
	['weed_white-widow'] 			 = {['name'] = 'weed_white-widow', 			 	['label'] = 'White Widow 1g', 			['weight'] = 200, 		['type'] = 'item', 		['image'] = 'weed_baggy.png', 			['unique'] = false, 	['useable'] = true, 	['shouldClose'] = false,   ['combinable'] = {accept = {'rolling_paper'}, reward = 'wwjoint', anim = {['dict'] = 'anim@amb@business@weed@weed_inspecting_high_dry@', ['lib'] = 'weed_inspecting_high_base_inspector', ['text'] = 'Rolling White Widow joint', ['timeOut'] = 5000,}},   ['description'] = 'Weed Baggy.'},
	['weed_skunk'] 				  	 = {['name'] = 'weed_skunk', 			 		['label'] = 'Skunk 1g', 				['weight'] = 200, 		['type'] = 'item', 		['image'] = 'weed_baggy.png', 			['unique'] = false, 	['useable'] = true, 	['shouldClose'] = false,   ['combinable'] = {accept = {'rolling_paper'}, reward = 'sjoint', anim = {['dict'] = 'anim@amb@business@weed@weed_inspecting_high_dry@', ['lib'] = 'weed_inspecting_high_base_inspector', ['text'] = 'Rolling Skunk joint', ['timeOut'] = 5000,}},   ['description'] = 'Weed Baggy.'},
	['weed_purple-haze'] 			 = {['name'] = 'weed_purple-haze', 			 	['label'] = 'Purple Haze 1g', 			['weight'] = 200, 		['type'] = 'item', 		['image'] = 'weed_baggy.png', 			['unique'] = false, 	['useable'] = true, 	['shouldClose'] = false,   ['combinable'] = {accept = {'rolling_paper'}, reward = 'phjoint', anim = {['dict'] = 'anim@amb@business@weed@weed_inspecting_high_dry@', ['lib'] = 'weed_inspecting_high_base_inspector', ['text'] = 'Rolling Purple Haze joint', ['timeOut'] = 5000,}},   ['description'] = 'Weed Baggy.'},
	['weed_og-kush'] 				 = {['name'] = 'weed_og-kush', 			 		['label'] = 'OGKush 1g', 				['weight'] = 200, 		['type'] = 'item', 		['image'] = 'weed_baggy.png', 			['unique'] = false, 	['useable'] = true, 	['shouldClose'] = false,   ['combinable'] = {accept = {'rolling_paper'}, reward = 'ogkjoint', anim = {['dict'] = 'anim@amb@business@weed@weed_inspecting_high_dry@', ['lib'] = 'weed_inspecting_high_base_inspector', ['text'] = 'Rolling OG Kush joint', ['timeOut'] = 5000,}},   ['description'] = 'Weed Baggy.'},
	['weed_amnesia'] 				 = {['name'] = 'weed_amnesia', 			 		['label'] = 'Amnesia 1g', 				['weight'] = 200, 		['type'] = 'item', 		['image'] = 'weed_baggy.png', 			['unique'] = false, 	['useable'] = true, 	['shouldClose'] = false,   ['combinable'] = {accept = {'rolling_paper'}, reward = 'amjoint', anim = {['dict'] = 'anim@amb@business@weed@weed_inspecting_high_dry@', ['lib'] = 'weed_inspecting_high_base_inspector', ['text'] = 'Rolling Amnesia joint', ['timeOut'] = 5000,}},   ['description'] = 'Weed Baggy.'},
	['weed_ak47'] 				     = {['name'] = 'weed_ak47', 			 		['label'] = 'Big Bag of AK47 (10g)', 	['weight'] = 200, 		['type'] = 'item', 		['image'] = 'weed_baggy.png', 			['unique'] = false, 	['useable'] = true, 	['shouldClose'] = false,    ['combinable'] = {accept = {'rolling_paper'}, reward = 'akjoint', anim = {['dict'] = 'anim@amb@business@weed@weed_inspecting_high_dry@', ['lib'] = 'weed_inspecting_high_base_inspector', ['text'] = 'Rolling AK47 joint', ['timeOut'] = 5000,}},   ['description'] = 'Weed Baggy.'},
	['weed_zkittlez'] 				 = {['name'] = 'weed_zkittlez', 				['label'] = 'Zkittlez 1g', 				['weight'] = 200, 		['type'] = 'item', 		['image'] = 'weed_baggy.png', 			['unique'] = false, 	['useable'] = true, 	['shouldClose'] = false,    ['combinable'] = {accept = {'rolling_paper'}, reward = 'zkittlezjoint', anim = {['dict'] = 'anim@amb@business@weed@weed_inspecting_high_dry@', ['lib'] = 'weed_inspecting_high_base_inspector', ['text'] = 'Rolling Zkittlez joint', ['timeOut'] = 5000,}},   ['description'] = 'Weed Baggy.'},
	['weed_weddingcake'] 			 = {['name'] = 'weed_weddingcake', 				['label'] = 'Wedding Cake 1g', 			['weight'] = 200, 		['type'] = 'item', 		['image'] = 'weed_baggy.png', 			['unique'] = false, 	['useable'] = true, 	['shouldClose'] = false,    ['combinable'] = {accept = {'rolling_paper'}, reward = 'weddingcakejoint', anim = {['dict'] = 'anim@amb@business@weed@weed_inspecting_high_dry@', ['lib'] = 'weed_inspecting_high_base_inspector', ['text'] = 'Rolling Wedding Cake joint', ['timeOut'] = 5000,}},   ['description'] = 'Weed Baggy.'},
	['weed_dosidose'] 			 	= {['name'] = 'weed_dosidose', 					['label'] = 'Dosidos 1g', 				['weight'] = 200, 		['type'] = 'item', 		['image'] = 'weed_baggy.png', 			['unique'] = false, 	['useable'] = true, 	['shouldClose'] = false,    ['combinable'] = {accept = {'rolling_paper'}, reward = 'dosidosjoint', anim = {['dict'] = 'anim@amb@business@weed@weed_inspecting_high_dry@', ['lib'] = 'weed_inspecting_high_base_inspector', ['text'] = 'Rolling Dosidos joint', ['timeOut'] = 5000,}},   ['description'] = 'Weed Baggy.'},
	['weed_godfatherog'] 			 	= {['name'] = 'weed_godfatherog', 					['label'] = 'Godfather OG 1g', 				['weight'] = 200, 		['type'] = 'item', 		['image'] = 'weed_baggy.png', 			['unique'] = false, 	['useable'] = true, 	['shouldClose'] = false,    ['combinable'] = {accept = {'rolling_paper'}, reward = 'godfatherogjoint', anim = {['dict'] = 'anim@amb@business@weed@weed_inspecting_high_dry@', ['lib'] = 'weed_inspecting_high_base_inspector', ['text'] = 'Rolling Godfather OG joint', ['timeOut'] = 5000,}},   ['description'] = 'Weed Baggy.'},

	-- Weed Seed
	['weed_white-widow_seed'] 		 = {['name'] = 'weed_white-widow_seed', 		['label'] = 'White Widow Seed', 		['weight'] = 0, 		['type'] = 'item', 		['image'] = 'weed_seed.png', 		    ['unique'] = false, 	['useable'] = true, 	['shouldClose'] = false,   ['combinable'] = nil,   ['description'] = 'A weed seed of White Widow'},
	['weed_skunk_seed'] 			 = {['name'] = 'weed_skunk_seed', 			    ['label'] = 'Skunk Seed', 				['weight'] = 0, 		['type'] = 'item', 		['image'] = 'weed_seed.png', 		    ['unique'] = false, 	['useable'] = true, 	['shouldClose'] = true,	   ['combinable'] = nil,   ['description'] = 'A weed seed of Skunk'},
	['weed_purple-haze_seed'] 		 = {['name'] = 'weed_purple-haze_seed', 		['label'] = 'Purple Haze Seed', 		['weight'] = 0, 		['type'] = 'item', 		['image'] = 'weed_seed.png', 		    ['unique'] = false, 	['useable'] = true, 	['shouldClose'] = true,	   ['combinable'] = nil,   ['description'] = 'A weed seed of Purple Haze'},
	['weed_og-kush_seed'] 			 = {['name'] = 'weed_og-kush_seed', 			['label'] = 'OGKush Seed', 				['weight'] = 0, 		['type'] = 'item', 		['image'] = 'weed_seed.png', 		    ['unique'] = false, 	['useable'] = true, 	['shouldClose'] = true,	   ['combinable'] = nil,   ['description'] = 'A weed seed of OG Kush'},
	['weed_amnesia_seed'] 			 = {['name'] = 'weed_amnesia_seed', 			['label'] = 'Amnesia Seed', 			['weight'] = 0, 		['type'] = 'item', 		['image'] = 'weed_seed.png', 		    ['unique'] = false, 	['useable'] = true, 	['shouldClose'] = true,	   ['combinable'] = nil,   ['description'] = 'A weed seed of Amnesia'},
	['weed_ak47_seed'] 				 = {['name'] = 'weed_ak47_seed', 			    ['label'] = 'AK47 Seed', 				['weight'] = 0, 		['type'] = 'item', 		['image'] = 'weed_seed.png', 		    ['unique'] = false, 	['useable'] = true, 	['shouldClose'] = true,	   ['combinable'] = nil,   ['description'] = 'A weed seed of AK47'},
	['weed_zkittlez_seed'] 				 = {['name'] = 'weed_zkittlez_seed', 			    ['label'] = 'Zkittlez Seed', 				['weight'] = 0, 		['type'] = 'item', 		['image'] = 'weed_seed.png', 		    ['unique'] = false, 	['useable'] = true, 	['shouldClose'] = true,	   ['combinable'] = nil,   ['description'] = 'A weed seed of Zkittlez'},
	['weed_weddingcake_seed'] 				 = {['name'] = 'weed_weddingcake_seed', 			    ['label'] = 'Wedding Cake Seed', 				['weight'] = 0, 		['type'] = 'item', 		['image'] = 'weed_seed.png', 		    ['unique'] = false, 	['useable'] = true, 	['shouldClose'] = true,	   ['combinable'] = nil,   ['description'] = 'A weed seed of Wedding Cake'},
	['weed_dosidos_seed'] 				 = {['name'] = 'weed_dosidos_seed', 			    ['label'] = 'Dosidos Seed', 				['weight'] = 0, 		['type'] = 'item', 		['image'] = 'weed_seed.png', 		    ['unique'] = false, 	['useable'] = true, 	['shouldClose'] = true,	   ['combinable'] = nil,   ['description'] = 'A weed seed of Dosidos'},
	['weed_godfatherog_seed'] 				 = {['name'] = 'weed_godfatherog_seed', 			    ['label'] = 'Godfather OG Seed', 				['weight'] = 0, 		['type'] = 'item', 		['image'] = 'weed_seed.png', 		    ['unique'] = false, 	['useable'] = true, 	['shouldClose'] = true,	   ['combinable'] = nil,   ['description'] = 'A weed seed of Godfather OG'},
	['weed_nutrition'] 				 = {['name'] = 'weed_nutrition', 			    ['label'] = 'Plant Fertilizer', 		['weight'] = 2000, 		['type'] = 'item', 		['image'] = 'weed_nutrition.png', 		['unique'] = false, 	['useable'] = true, 	['shouldClose'] = true,	   ['combinable'] = nil,   ['description'] = 'Plant nutrition'},
    ```

## Qb-weed/config
    ```
    QBWeed = {}
QBWeed.HarvestTime = 40 * 1000

QBWeed.Plants = {
    ["og-kush"] = {
        ["label"] = "OGKush 2g",
        ["item"] = "weed_og-kush",
        ["stages"] = {
            ["stage-a"] = "bkr_prop_weed_01_small_01c",
            ["stage-b"] = "bkr_prop_weed_01_small_01b",
            ["stage-c"] = "bkr_prop_weed_01_small_01a",
            ["stage-d"] = "bkr_prop_weed_med_01b",
            ["stage-e"] = "bkr_prop_weed_lrg_01a",
            ["stage-f"] = "bkr_prop_weed_lrg_01b",
            ["stage-g"] = "bkr_prop_weed_lrg_01b",
        },
        ["highestStage"] = "stage-g"
    },
    ["amnesia"] = {
        ["label"] = "Amnesia 2g",
        ["item"] = "weed_amnesia",
        ["stages"] = {
            ["stage-a"] = "bkr_prop_weed_01_small_01c",
            ["stage-b"] = "bkr_prop_weed_01_small_01b",
            ["stage-c"] = "bkr_prop_weed_01_small_01a",
            ["stage-d"] = "bkr_prop_weed_med_01b",
            ["stage-e"] = "bkr_prop_weed_lrg_01a",
            ["stage-f"] = "bkr_prop_weed_lrg_01b",
            ["stage-g"] = "bkr_prop_weed_lrg_01b",
        },
        ["highestStage"] = "stage-g"
    },
    ["skunk"] = {
        ["label"] = "Skunk 2g",
        ["item"] = "weed_skunk",
        ["stages"] = {
            ["stage-a"] = "bkr_prop_weed_01_small_01c",
            ["stage-b"] = "bkr_prop_weed_01_small_01b",
            ["stage-c"] = "bkr_prop_weed_01_small_01a",
            ["stage-d"] = "bkr_prop_weed_med_01b",
            ["stage-e"] = "bkr_prop_weed_lrg_01a",
            ["stage-f"] = "bkr_prop_weed_lrg_01b",
            ["stage-g"] = "bkr_prop_weed_lrg_01b",
        },
        ["highestStage"] = "stage-g"
    },
    ["ak47"] = {
        ["label"] = "AK47 2g",
        ["item"] = "weed_ak47",
        ["stages"] = {
            ["stage-a"] = "bkr_prop_weed_01_small_01c",
            ["stage-b"] = "bkr_prop_weed_01_small_01b",
            ["stage-c"] = "bkr_prop_weed_01_small_01a",
            ["stage-d"] = "bkr_prop_weed_med_01b",
            ["stage-e"] = "bkr_prop_weed_lrg_01a",
            ["stage-f"] = "bkr_prop_weed_lrg_01b",
            ["stage-g"] = "bkr_prop_weed_lrg_01b",
        },
        ["highestStage"] = "stage-g"
    },
    ["purple-haze"] = {
        ["label"] = "Purple Haze 2g",
        ["item"] = "weed_purple-haze",
        ["stages"] = {
            ["stage-a"] = "bkr_prop_weed_01_small_01c",
            ["stage-b"] = "bkr_prop_weed_01_small_01b",
            ["stage-c"] = "bkr_prop_weed_01_small_01a",
            ["stage-d"] = "bkr_prop_weed_med_01b",
            ["stage-e"] = "bkr_prop_weed_lrg_01a",
            ["stage-f"] = "bkr_prop_weed_lrg_01b",
            ["stage-g"] = "bkr_prop_weed_lrg_01b",
        },
        ["highestStage"] = "stage-g"
    },
    ["white-widow"] = {
        ["label"] = "White Widow 2g",
        ["item"] = "weed_white-widow",
        ["stages"] = {
            ["stage-a"] = "bkr_prop_weed_01_small_01c",
            ["stage-b"] = "bkr_prop_weed_01_small_01b",
            ["stage-c"] = "bkr_prop_weed_01_small_01a",
            ["stage-d"] = "bkr_prop_weed_med_01b",
            ["stage-e"] = "bkr_prop_weed_lrg_01a",
            ["stage-f"] = "bkr_prop_weed_lrg_01b",
            ["stage-g"] = "bkr_prop_weed_lrg_01b",
        },
        ["highestStage"] = "stage-g"
    },
    ["zkittlez"] = {
        ["label"] = "Zkittlez 2g",
        ["item"] = "weed_zkittlez",
        ["stages"] = {
            ["stage-a"] = "bkr_prop_weed_01_small_01c",
            ["stage-b"] = "bkr_prop_weed_01_small_01b",
            ["stage-c"] = "bkr_prop_weed_01_small_01a",
            ["stage-d"] = "bkr_prop_weed_med_01b",
            ["stage-e"] = "bkr_prop_weed_lrg_01a",
            ["stage-f"] = "bkr_prop_weed_lrg_01b",
            ["stage-g"] = "bkr_prop_weed_lrg_01b",
        },
        ["highestStage"] = "stage-g"
    },
    ["weddingcake"] = {
        ["label"] = "Wedding Cake 2g",
        ["item"] = "weed_weddingcake",
        ["stages"] = {
            ["stage-a"] = "bkr_prop_weed_01_small_01c",
            ["stage-b"] = "bkr_prop_weed_01_small_01b",
            ["stage-c"] = "bkr_prop_weed_01_small_01a",
            ["stage-d"] = "bkr_prop_weed_med_01b",
            ["stage-e"] = "bkr_prop_weed_lrg_01a",
            ["stage-f"] = "bkr_prop_weed_lrg_01b",
            ["stage-g"] = "bkr_prop_weed_lrg_01b",
        },
        ["highestStage"] = "stage-g"
    },
    ["dosidos"] = {
        ["label"] = "Dosidos 2g",
        ["item"] = "weed_dosidose",
        ["stages"] = {
            ["stage-a"] = "bkr_prop_weed_01_small_01c",
            ["stage-b"] = "bkr_prop_weed_01_small_01b",
            ["stage-c"] = "bkr_prop_weed_01_small_01a",
            ["stage-d"] = "bkr_prop_weed_med_01b",
            ["stage-e"] = "bkr_prop_weed_lrg_01a",
            ["stage-f"] = "bkr_prop_weed_lrg_01b",
            ["stage-g"] = "bkr_prop_weed_lrg_01b",
        },
        ["highestStage"] = "stage-g"
    },
}

QBWeed.Props = {
    ["stage-a"] = "bkr_prop_weed_01_small_01c",
    ["stage-b"] = "bkr_prop_weed_01_small_01b",
    ["stage-c"] = "bkr_prop_weed_01_small_01a",
    ["stage-d"] = "bkr_prop_weed_med_01b",
    ["stage-e"] = "bkr_prop_weed_lrg_01a",
    ["stage-f"] = "bkr_prop_weed_lrg_01b",
    ["stage-g"] = "bkr_prop_weed_lrg_01b",
}
```

**qb-weed/server/main.lua**
```
QBCore.Functions.CreateUseableItem("weed_white-widow_seed", function(source, item)
    TriggerClientEvent('qb-weed:client:placePlant', source, 'white-widow', item)
end)

QBCore.Functions.CreateUseableItem("weed_skunk_seed", function(source, item)
    TriggerClientEvent('qb-weed:client:placePlant', source, 'skunk', item)
end)

QBCore.Functions.CreateUseableItem("weed_purple-haze_seed", function(source, item)
    TriggerClientEvent('qb-weed:client:placePlant', source, 'purple-haze', item)
end)

QBCore.Functions.CreateUseableItem("weed_og-kush_seed", function(source, item)
    TriggerClientEvent('qb-weed:client:placePlant', source, 'og-kush', item)
end)

QBCore.Functions.CreateUseableItem("weed_amnesia_seed", function(source, item)
    TriggerClientEvent('qb-weed:client:placePlant', source, 'amnesia', item)
end)

QBCore.Functions.CreateUseableItem("weed_ak47_seed", function(source, item)
    TriggerClientEvent('qb-weed:client:placePlant', source, 'ak47', item)
end)

QBCore.Functions.CreateUseableItem("weed_zkittlez_seed", function(source, item)
    TriggerClientEvent('qb-weed:client:placePlant', source, 'zkittlez', item)
end)

QBCore.Functions.CreateUseableItem("weed_weddingcake_seed", function(source, item)
    TriggerClientEvent('qb-weed:client:placePlant', source, 'weddingcake', item)
end)

QBCore.Functions.CreateUseableItem("weed_dosidos_seed", function(source, item)
    TriggerClientEvent('qb-weed:client:placePlant', source, 'dosidos', item)
end)

QBCore.Functions.CreateUseableItem("weed_nutrition", function(source, item)
    TriggerClientEvent('qb-weed:client:foodPlant', source, item)
end)
```

**qb-smallresources/server/consumables.lua**
```
QBCore.Functions.CreateUseableItem("joint", function(source, item)
    local Player = QBCore.Functions.GetPlayer(source)
	if not Player.Functions.RemoveItem(item.name, 1, item.slot) then return end
    TriggerClientEvent("consumables:client:UseJoint", source)
end)

QBCore.Functions.CreateUseableItem("wwjoint", function(source, item)
    local Player = QBCore.Functions.GetPlayer(source)
	if not Player.Functions.RemoveItem(item.name, 1, item.slot) then return end
    TriggerClientEvent("consumables:client:UseJointww", source)
end)

QBCore.Functions.CreateUseableItem("sjoint", function(source, item)
    local Player = QBCore.Functions.GetPlayer(source)
	if not Player.Functions.RemoveItem(item.name, 1, item.slot) then return end
    TriggerClientEvent("consumables:client:UseJoints", source)
end)

QBCore.Functions.CreateUseableItem("phjoint", function(source, item)
    local Player = QBCore.Functions.GetPlayer(source)
	if not Player.Functions.RemoveItem(item.name, 1, item.slot) then return end
    TriggerClientEvent("consumables:client:UseJointph", source)
end)

QBCore.Functions.CreateUseableItem("ogkjoint", function(source, item)
    local Player = QBCore.Functions.GetPlayer(source)
	if not Player.Functions.RemoveItem(item.name, 1, item.slot) then return end
    TriggerClientEvent("consumables:client:UseJointogk", source)
end)

QBCore.Functions.CreateUseableItem("amjoint", function(source, item)
    local Player = QBCore.Functions.GetPlayer(source)
	if not Player.Functions.RemoveItem(item.name, 1, item.slot) then return end
    TriggerClientEvent("consumables:client:UseJointam", source)
end)

QBCore.Functions.CreateUseableItem("akjoint", function(source, item)
    local Player = QBCore.Functions.GetPlayer(source)
	if not Player.Functions.RemoveItem(item.name, 1, item.slot) then return end
    TriggerClientEvent("consumables:client:UseJointak", source)
end)

QBCore.Functions.CreateUseableItem("zkittlezjoint", function(source, item)
    local Player = QBCore.Functions.GetPlayer(source)
	if not Player.Functions.RemoveItem(item.name, 1, item.slot) then return end
    TriggerClientEvent("consumables:client:UseJointzkittlez", source)
end)

QBCore.Functions.CreateUseableItem("weddingcakejoint", function(source, item)
    local Player = QBCore.Functions.GetPlayer(source)
	if not Player.Functions.RemoveItem(item.name, 1, item.slot) then return end
    TriggerClientEvent("consumables:client:UseJointweddingcake", source)
end)

QBCore.Functions.CreateUseableItem("dosidosjoint", function(source, item)
    local Player = QBCore.Functions.GetPlayer(source)
	if not Player.Functions.RemoveItem(item.name, 1, item.slot) then return end
    TriggerClientEvent("consumables:client:UseJointdosidos", source)
end)

QBCore.Functions.CreateUseableItem("godfatherogjoint", function(source, item)
    local Player = QBCore.Functions.GetPlayer(source)
	if not Player.Functions.RemoveItem(item.name, 1, item.slot) then return end
    TriggerClientEvent("consumables:client:UseJointgodfatherog", source)
end)
```

**qb-smallresources/client/consumables.lua**
```
RegisterNetEvent('consumables:client:UseJoint', function()
    QBCore.Functions.Progressbar("smoke_joint", "Lighting joint..", 4000, false, true, {
        disableMovement = false,
        disableCarMovement = false,
		disableMouse = false,
		disableCombat = true,
    }, {}, {}, {}, function() -- Done
        TriggerEvent("inventory:client:ItemBox", QBCore.Shared.Items["joint"], "remove")
        if IsPedInAnyVehicle(PlayerPedId(), false) then
            TriggerEvent('animations:client:EmoteCommandStart', {"smoke3"})
        else
            TriggerEvent('animations:client:EmoteCommandStart', {"smokeweed"})
        end
        TriggerEvent("evidence:client:SetStatus", "weedsmell", 300)
        exports['ps-buffs']:AddArmorBuff(35000, 10)
        TriggerServerEvent('hud:server:RelieveStress', math.random(2, 4))
        TriggerEvent('animations:client:SmokeWeed')
    end)
end)

RegisterNetEvent('consumables:client:UseJointww', function()
    QBCore.Functions.Progressbar("smoke_joint", "Lighting White Widow joint..", 4000, false, true, {
        disableMovement = false,
        disableCarMovement = false,
		disableMouse = false,
		disableCombat = true,
    }, {}, {}, {}, function() -- Done
        TriggerEvent("inventory:client:ItemBox", QBCore.Shared.Items["wwjoint"], "remove")
        if IsPedInAnyVehicle(PlayerPedId(), false) then
            TriggerEvent('animations:client:EmoteCommandStart', {"smoke3"})
        else
            TriggerEvent('animations:client:EmoteCommandStart', {"smokeweed"})
        end
        TriggerEvent("evidence:client:SetStatus", "weedsmell", 300)
        exports['ps-buffs']:AddArmorBuff(35000, 10)
        TriggerServerEvent('hud:server:RelieveStress', math.random(2, 4))
        TriggerEvent('animations:client:SmokeWeed')
    end)
end)

RegisterNetEvent('consumables:client:UseJoints', function()
    QBCore.Functions.Progressbar("smoke_joint", "Lighting Skunk joint..", 4000, false, true, {
        disableMovement = false,
        disableCarMovement = false,
		disableMouse = false,
		disableCombat = true,
    }, {}, {}, {}, function() -- Done
        TriggerEvent("inventory:client:ItemBox", QBCore.Shared.Items["sjoint"], "remove")
        if IsPedInAnyVehicle(PlayerPedId(), false) then
            TriggerEvent('animations:client:EmoteCommandStart', {"smoke3"})
        else
            TriggerEvent('animations:client:EmoteCommandStart', {"smokeweed"})
        end
        TriggerEvent("evidence:client:SetStatus", "weedsmell", 300)
        exports['ps-buffs']:AddArmorBuff(35000, 10)
        TriggerServerEvent('hud:server:RelieveStress', math.random(2, 4))
        TriggerEvent('animations:client:SmokeWeed')
    end)
end)

RegisterNetEvent('consumables:client:UseJointph', function()
    QBCore.Functions.Progressbar("smoke_joint", "Lighting Purple Haze joint..", 4000, false, true, {
        disableMovement = false,
        disableCarMovement = false,
		disableMouse = false,
		disableCombat = true,
    }, {}, {}, {}, function() -- Done
        TriggerEvent("inventory:client:ItemBox", QBCore.Shared.Items["phjoint"], "remove")
        if IsPedInAnyVehicle(PlayerPedId(), false) then
            TriggerEvent('animations:client:EmoteCommandStart', {"smoke3"})
        else
            TriggerEvent('animations:client:EmoteCommandStart', {"smokeweed"})
        end
        TriggerEvent("evidence:client:SetStatus", "weedsmell", 300)
        exports['ps-buffs']:AddArmorBuff(35000, 10)
        TriggerServerEvent('hud:server:RelieveStress', math.random(2, 4))
        TriggerEvent('animations:client:SmokeWeed')
    end)
end)

RegisterNetEvent('consumables:client:UseJointogk', function()
    QBCore.Functions.Progressbar("smoke_joint", "Lighting Purple Haze joint..", 4000, false, true, {
        disableMovement = false,
        disableCarMovement = false,
		disableMouse = false,
		disableCombat = true,
    }, {}, {}, {}, function() -- Done
        TriggerEvent("inventory:client:ItemBox", QBCore.Shared.Items["ogkjoint"], "remove")
        if IsPedInAnyVehicle(PlayerPedId(), false) then
            TriggerEvent('animations:client:EmoteCommandStart', {"smoke3"})
        else
            TriggerEvent('animations:client:EmoteCommandStart', {"smokeweed"})
        end
        TriggerEvent("evidence:client:SetStatus", "weedsmell", 300)
        exports['ps-buffs']:AddArmorBuff(35000, 10)
        TriggerServerEvent('hud:server:RelieveStress', math.random(2, 4))
        TriggerEvent('animations:client:SmokeWeed')
    end)
end)

RegisterNetEvent('consumables:client:UseJointam', function()
    QBCore.Functions.Progressbar("smoke_joint", "Lighting Purple Haze joint..", 4000, false, true, {
        disableMovement = false,
        disableCarMovement = false,
		disableMouse = false,
		disableCombat = true,
    }, {}, {}, {}, function() -- Done
        TriggerEvent("inventory:client:ItemBox", QBCore.Shared.Items["amjoint"], "remove")
        if IsPedInAnyVehicle(PlayerPedId(), false) then
            TriggerEvent('animations:client:EmoteCommandStart', {"smoke3"})
        else
            TriggerEvent('animations:client:EmoteCommandStart', {"smokeweed"})
        end
        TriggerEvent("evidence:client:SetStatus", "weedsmell", 300)
        exports['ps-buffs']:AddArmorBuff(35000, 10)
        TriggerServerEvent('hud:server:RelieveStress', math.random(2, 4))
        TriggerEvent('animations:client:SmokeWeed')
    end)
end)

RegisterNetEvent('consumables:client:UseJointak', function()
    QBCore.Functions.Progressbar("smoke_joint", "Lighting Purple Haze joint..", 4000, false, true, {
        disableMovement = false,
        disableCarMovement = false,
		disableMouse = false,
		disableCombat = true,
    }, {}, {}, {}, function() -- Done
        TriggerEvent("inventory:client:ItemBox", QBCore.Shared.Items["akjoint"], "remove")
        if IsPedInAnyVehicle(PlayerPedId(), false) then
            TriggerEvent('animations:client:EmoteCommandStart', {"smoke3"})
        else
            TriggerEvent('animations:client:EmoteCommandStart', {"smokeweed"})
        end
        TriggerEvent("evidence:client:SetStatus", "weedsmell", 300)
        exports['ps-buffs']:AddArmorBuff(35000, 10)
        TriggerServerEvent('hud:server:RelieveStress', math.random(2, 4))
        TriggerEvent('animations:client:SmokeWeed')
    end)
end)

RegisterNetEvent('consumables:client:UseJointzkittlez', function()
    QBCore.Functions.Progressbar("smoke_joint", "Lighting Zkittlez joint..", 4000, false, true, {
        disableMovement = false,
        disableCarMovement = false,
		disableMouse = false,
		disableCombat = true,
    }, {}, {}, {}, function() -- Done
        TriggerEvent("inventory:client:ItemBox", QBCore.Shared.Items["zkittlezjoint"], "remove")
        if IsPedInAnyVehicle(PlayerPedId(), false) then
            TriggerEvent('animations:client:EmoteCommandStart', {"smoke3"})
        else
            TriggerEvent('animations:client:EmoteCommandStart', {"smokeweed"})
        end
        TriggerEvent("evidence:client:SetStatus", "weedsmell", 300)
        exports['ps-buffs']:AddArmorBuff(35000, 10)
        TriggerServerEvent('hud:server:RelieveStress', math.random(2, 4))
        TriggerEvent('animations:client:SmokeWeed')
    end)
end)

RegisterNetEvent('consumables:client:UseJointweddingcake', function()
    QBCore.Functions.Progressbar("smoke_joint", "Lighting Wedding Cake joint..", 4000, false, true, {
        disableMovement = false,
        disableCarMovement = false,
		disableMouse = false,
		disableCombat = true,
    }, {}, {}, {}, function() -- Done
        TriggerEvent("inventory:client:ItemBox", QBCore.Shared.Items["weddingcakejoint"], "remove")
        if IsPedInAnyVehicle(PlayerPedId(), false) then
            TriggerEvent('animations:client:EmoteCommandStart', {"smoke3"})
        else
            TriggerEvent('animations:client:EmoteCommandStart', {"smokeweed"})
        end
        TriggerEvent("evidence:client:SetStatus", "weedsmell", 300)
        exports['ps-buffs']:AddArmorBuff(35000, 10)
        TriggerServerEvent('hud:server:RelieveStress', math.random(2, 4))
        TriggerEvent('animations:client:SmokeWeed')
    end)
end)

RegisterNetEvent('consumables:client:UseJointdosidos', function()
    QBCore.Functions.Progressbar("smoke_joint", "Lighting Dosidos joint..", 4000, false, true, {
        disableMovement = false,
        disableCarMovement = false,
		disableMouse = false,
		disableCombat = true,
    }, {}, {}, {}, function() -- Done
        TriggerEvent("inventory:client:ItemBox", QBCore.Shared.Items["dosidosjoint"], "remove")
        if IsPedInAnyVehicle(PlayerPedId(), false) then
            TriggerEvent('animations:client:EmoteCommandStart', {"smoke3"})
        else
            TriggerEvent('animations:client:EmoteCommandStart', {"smokeweed"})
        end
        TriggerEvent("evidence:client:SetStatus", "weedsmell", 300)
        exports['ps-buffs']:AddArmorBuff(35000, 10)
        TriggerServerEvent('hud:server:RelieveStress', math.random(2, 4))
        TriggerEvent('animations:client:SmokeWeed')
    end)
end)

RegisterNetEvent('consumables:client:UseJointgodfatherog', function()
    QBCore.Functions.Progressbar("smoke_joint", "Lighting Godfather OG joint..", 4000, false, true, {
        disableMovement = false,
        disableCarMovement = false,
		disableMouse = false,
		disableCombat = true,
    }, {}, {}, {}, function() -- Done
        TriggerEvent("inventory:client:ItemBox", QBCore.Shared.Items["godfatherogjoint"], "remove")
        if IsPedInAnyVehicle(PlayerPedId(), false) then
            TriggerEvent('animations:client:EmoteCommandStart', {"smoke3"})
        else
            TriggerEvent('animations:client:EmoteCommandStart', {"smokeweed"})
        end
        TriggerEvent("evidence:client:SetStatus", "weedsmell", 300)
        exports['ps-buffs']:AddArmorBuff(35000, 10)
        TriggerServerEvent('hud:server:RelieveStress', math.random(2, 4))
        TriggerEvent('animations:client:SmokeWeed')
    end)
end)
```
