# CodeSpeed
Some code function speed tests for Unity3D


### Arithmetics

| Operation | Time (ms) |
|-----------|-----------|
| +-        | 1         |
| div mul   | 2         |
| %         | 2         |

### Mathf

| Operation           | Time (ms) |
|---------------------|-----------|
| Abs                 | 6         |
| Sign                | 3         |
| Sin                 | 18        |
| Clamp               | 6         |
| Pow                 | 21        |
| Lerp                | 11        |
| Floor               | 10        |
| MoveTowards         | 20        |
| ClosestPowerOf2     | 34        |
| Perlin Noise        | 40        |
| Perlin Noise 1D     | 35        |
| Range               | 37        |
| Random HSV          | 304       |

### Vector3

| Operation        | Time (ms) |
|------------------|-----------|
| Dot              | 6         |
| Lerp             | 28        |
| Slerp            | 63        |
| Scale            | 15        |
| RotateTowards    | 65        |
| Normalize        | 65        |
| Distance         | 15        |
| Magnitude        | 40        |
| Sqrt Magnitude   | 23        |

### Camera

| Operation            | Time (ms) |
|----------------------|-----------|
| Camera.main          | 72        |
| WorldToScreenPoint   | 240       |
| ViewportToScreen     | 95        |

### Physics

| Operation              | Time (ms) |
|------------------------|-----------|
| Raycast 0 collider     | 296       |
| Raycast 1000 collider  | 1400      |
| Raycast2D              | 2400      |
| Boxcast                | 5500      |

### MonoBehaviour

| Operation                                 | Time (ms)       |
|-------------------------------------------|-----------------|
| .gameObject                               | 80              |
| GetComponent null                         | 1530            |
| GetComponent Unity Components             | 140             |
| GetComponent User script                  | 210             |
| Send Message (object with 20 components)  | 200             |
| UnityEvent                                | 35 per listener |
| Event                                     | 3 per listener  |
