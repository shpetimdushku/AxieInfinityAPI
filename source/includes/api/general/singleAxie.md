## Single Axie

> Returns JSON structured like this:

```json
{
  "id": 48133,
  "name": "Axie #48133",
  "genes": "31209586552778604935104065586416217693789939714895764496264522953517210607944",
  "owner": "0x3945476e477de76d53b4833a46c806ef3d72b21e",
  "birthDate": 1554629529,
  "sireId": 20426,
  "sireClass": "aquatic",
  "matronId": 35323,
  "matronClass": "aquatic",
  "stage": 4,
  "class": "aquatic",
  "title": null,
  "parts": [
    ...,
    {
      "id": "mouth-silence-whisper",
      "name": "Silence Whisper",
      "class": "plant",
      "type": "mouth",
      "mystic": false,
      "bionic": false,
      "xmas": false,
      "stage": 1,
      "moves": [
        {
          "id": "mouth-forest-spirit",
          "name": "Forest Spirit",
          "type": "support",
          "attack": 0,
          "defense": 13,
          "accuracy": 100,
          "stage": 1,
          "effects": [
            {
              "name": "Heal",
              "type": "active",
              "description": "User heals 1/4 of max HP to front Ally."
            }
          ]
        }
      ]
    },
    ...
  ],
  "image": "https://storage.googleapis.com/assets.axieinfinity.com/axies/48133/axie/axie-full-transparent.png",
  "figure": {
    "images": {
      "axie.png": "https://storage.googleapis.com/assets.axieinfinity.com/axies/48133/axie/axie.png"
    },
    "atlas": "https://storage.googleapis.com/assets.axieinfinity.com/axies/48133/axie/axie.atlas",
    "model": "https://storage.googleapis.com/assets.axieinfinity.com/axies/48133/axie/axie.json"
  },
  "auction": {
    "type": "sale",
    "startingPrice": "1200000000000000000",
    "endingPrice": "1150000000000000000",
    "buyNowPrice": "1150000000000000000",
    "suggestedPrice": "1150115740740740740",
    "startingTime": "1560840680",
    "duration": "259200",
    "timeLeft": "0"
  },
  "stats": {
    "hp": 50,
    "speed": 46,
    "skill": 35,
    "morale": 33
  },
  "exp": 31,
  "activityPoint": 198,
  "pendingExp": 5263,
  "expSubmittedAt": 1562401923967,
  "expSignature": "0x01ae777161c73a1936da5efd8fe6cef84463d4f8da90a4baa6907e126f7776a38373b2382295bbd5d89b477cf41ef0b6a2d7e03031944de9628a627431235a54141c",
  "breedCount": 4,
  "breedable": false,
  "level": 1,
  "unlocked": true
}
```

Allows to retrieve data on specific Axie.

### Endpoint

`GET /axies/<ID>`

### URL Parameters

Parameter | Description
--------- | -----------
ID | The ID of Axie to retrieve

