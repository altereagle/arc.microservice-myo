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