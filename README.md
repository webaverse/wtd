
# WTD

## metaversefile:
```-javascript
    {
  "start_url": "index.js",
  "components": [
    {
      "key": "wassie",
      "value": {
        "token": {
          "id": 593
        },
        "waypoints": [
          {
            "trigger": "use",
            "effect": {
              "move":[10,0.5,-5]
            }
          },
          {
            "trigger": "proximity",
            "effect": {
              "move":[15,0.5,-10]
            }
          },
          {
            "trigger": "proximity",
            "effect": {
              "move":[16,0.5,-5]
            }
          },
          {
            "trigger": "use",
            "effect": {
              "move":[30,0.5,-5]
            }
          }
        ]
      }
    }
  ]
}
```
## Trigger
`use`: will advance on activate (use E)

`proximity`: will advance to waypoint C when reached waypoint B

## Effect
`move`: position to move to

Could possibly also pass actions, or display text at a certain waypoint like:
`speak`: "Hello there traveler!"
