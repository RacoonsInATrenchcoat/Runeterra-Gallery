# Runeterra-Gallery

metadata.json
{
	"locales": ["{string}", ...],
	"clientHash": "{string}"
	"gameplayDataHash": "{string}",
	"timestamp": "{YYYYMMDDhhmm}",
	"patchlineRef": "{string}"
}

cards.json
[
    {
        "id": "{cardCode}",
        "idComponents": 
        {
            "set": "setNumber",
            "region": 
            {
                "id": "{shortRegionCode}",
                "name": "{regionName}"
            }
        }
        "name": "{name}",
        "type": "{type}",
        "subType": "{subType}",
        "superType": "{superType}",
        "description": "{description}",
        "keywords": [],
        "associatedCards": [{cardCode}, ...]
        "health": "{health}",
        "attack": "{attack}",
        "cost": "{cost}",
        "assets":
        {
            "gameAbsolutePath": "http://{cdn}/{bundleName}/set1/en_us/img/card/game/{cardCode}.png"
        } 

    },
    {...}
]

Example:

{
    "associatedCards": [],
    "associatedCardRefs": [],
    "assets": [
      {
        "gameAbsolutePath": "http://dd.b.pvp.net/6_6_0/set1/en_us/img/cards/01PZ019.png",
        "fullAbsolutePath": "http://dd.b.pvp.net/6_6_0/set1/en_us/img/cards/01PZ019-full.png"
      }
    ],
    "regions": [
      "Piltover & Zaun"
    ],
    "regionRefs": [
      "PiltoverZaun"
    ],
    "attack": 2,
    "cost": 2,
    "health": 1,
    "description": "When I'm summoned, refill 2 spell mana.",
    "descriptionRaw": "When I'm summoned, refill 2 spell mana.",
    "levelupDescription": "",
    "levelupDescriptionRaw": "",
    "flavorText": "Not everyone is cut out to further progress in Piltover immediately. Some need a little guidance--those who look at invention through the wrong lens, for instance.",
    "artistName": "SIXMOREVODKA",
    "name": "Eager Apprentice",
    "cardCode": "01PZ019",
    "keywords": [],
    "keywordRefs": [],
    "spellSpeed": "",
    "spellSpeedRef": "",
    "rarity": "COMMON",
    "rarityRef": "Common",
    "subtypes": [],
    "supertype": "",
    "type": "Unit",
    "collectible": true,
    "set": "Set1",
    "formats": [
      "Eternal"
    ],
    "formatRefs": [
      "client_Formats_Eternal_name"
    ]
  },

  Breakdown:
  "gameAbsolutePath": "http://{cdn}/{bundleName}/set1/en_us/img/card/game/{cardCode}.png"
    "gameAbsolutePath": "http://dd.b.pvp.net/6_6_0/set1/en_us/img/cards/01PZ019.png"
