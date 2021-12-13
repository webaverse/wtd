
# WTD

## Code Example:
```-javascript
    {
      "position": [
        24,
        0.5,
        16
      ],
      "quaternion": [
        0,
        1,
        0,
        0
      ],
      "start_url": "https://webaverse.github.io/wtd/",
      "components": [
        {
          "key": "token",
          "value": {
            "id": 8617
          }
        },
        {
          "key": "waypoints",
          "value": [
             [[10,0.5,5], [15,0.5,8]],
             [[25,0.5,0], [18,0.5,5], [12,0.5,-2]]
          ]
        }
      ]
    },
```

## Waypoints Breakdown:

```
[[10,0.5,5], [15,0.5,8]],
[[25,0.5,0], [18,0.5,5]]
```

#### Outer brackets `[[...]]`: 
-- `Waypoint Group`: Can advance to the next `Waypoint Group` with **activate** (Hold E) when the player passed all previous waypoints.

#### Inner brackets `[...]`: 
-- `Waypoint`: Will automatically advance to next waypoint when reached. Can be used for more tactical/fine-tuned movement (Instead of walking in a straight line)

### Important:
- Must have atleast 1 `Waypoint Group [[...]]` containing atleast 1 `Waypoint [...]`
- Auto-destroy on the last **activate** (Hold E)







