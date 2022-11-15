# mul_api
Building an API for the master unit list
This is the base repoistory for the code for the variables needed to utilise the MUL resource from an API stand point.

This is a basic example URI that points to a specific unit : https://masterunitlist.azurewebsites.net/Unit/QuickList?Name=WHM-7A

A more advanced URI is this: https://masterunitlist.azurewebsites.net/Unit/QuickList?MinTons=40&MaxTons=55&Factions=29&Types=18&AvailableEras=14

This points to an array of units between 40 and 55 tons inclusive. The Type is battlemech and Faction Fed Suns, in the Jihad era.

Interestingly, the differing ID's seem to be a single list.

Factions:
Federated Suns : 29
Clan Wolverine : 26
Clan Wolf : 24
Cland Jade Falcon : 15
Clan Ghost Bear : 11
Clan Fire Mandrill : 10
Clan Blood Spirit : 2
Draconis Combine : 27
Clan Nova Cat : 17
Clan Smoke Jaguar : 20
Clan Mongoose : 16
Clan Cloud Cobra : 6

Eras:
Star League : 10
Early Succession Wars : 11
Late Succession War - LosTech : 255
Late Succession War - Renaissance : 256
Clan Invasion : 13
Civil War : 247
Jihad : 14
Early Republic : 15
Late Republic : 247
Dark Ages : 16
ilClan : 257

Technology: 
This sort of breaks the idea that its all one list, it could be a couple of lists, but they have openings to allow for additions to it at a later time...
IS : 1, 
Clan : 2, 
Mixed : 3, 
Primitive : 57

Types: 
Mech : 18, 
Combat Vee : 19, 
Aerospace : 17, 
Infantry : 21,
Industrial Mech : 20, 
Protomech : 23, 
support vee : 24, 
Adv Aerospace : 81, 
Adv Supp : 79
Building : 97, 
Unknown : 76
