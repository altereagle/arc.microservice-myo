[![Build Status](https://travis-ci.com/altereagle/arc.microservice-myo.svg?branch=master)](https://travis-ci.com/altereagle/arc.microservice-myo)
[![Maintainability](https://api.codeclimate.com/v1/badges/084bfa31d9332927de83/maintainability)](https://codeclimate.com/github/altereagle/arc.microservice-myo/maintainability)
[![Test Coverage](https://api.codeclimate.com/v1/badges/084bfa31d9332927de83/test_coverage)](https://codeclimate.com/github/altereagle/arc.microservice-myo/test_coverage)
# Arc | *microservice*
## Myo
A microservice that listens to and reports Myo events.
![myo](https://cdn.geekwire.com/wp-content/uploads/2016/09/Myo_-_Real_Life_Applications_of_the_Myo_Armband_-_YouTube.png)

### Install
```
npm install arc.microservice-myo
```

### Incoming Events
| path | accepts | returns | description |
| --- | --- | --- | --- |
| start(**TODO**) | **null** | *Object* | Connects to available Myo's and returns an object with status information. |

### Outgoing Events
| path | accepts | returns | description |
| --- | --- | --- | --- |
| EMG(**TODO**) | **null** | *Object* | Returns EMG data for connected Myos. |

### The Code

| JavaScript |
| --- |
| /[index.js](https://altereagle.github.io/arc.microservice-myo/) |