# bravefrontier_summongates

Holds summon gate information, their summon rates, and their summon pools. To be used for Hamzabot's h/summon command.

# Rate Parameters

* "featured% (x)": The rate of summoning a featured unit. Multiple "featured%" parameters are used in case a summon gate has multiple featured units. "x" represents the xth unit of the featured pool.
* "global exclusive%": The rate of summoning a Global Exclusive unit.
* "shion to roglizer%": The rate of summoning a unit from Shion batch onward.
* "kulyuk to regil%": The rate of summoning a unit from Regil batch and before.

# Array Parameters

All array parameters list units in their Data ID forms.

* "featured (x)": An array consisting of the xth unit of the featured pool. This parameter will always contain only one element.
* "global exclusive": An array consisting of all Global Exclusive units summonable in the summon gate.
* "shion to roglizer": An array consisting of all units from Shion batch onward.
* "kulyuk to regil": An array consisting of all units from Regil batch and before.

# Other Parameters

* "gate name": The name of the summon gate.
* "active": A boolean that determines whether or not the gate is active in the game.
