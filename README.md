# Noolite РС11* transmitters

https://www.noo.com.by/adapter-noolite-pc.html

Support only PC11* transmitters.

## Installation

```npm install -g https://github.com/...```

## Configuration

``` 
{
    "bridge": {
        "name": "Homebridge",
        "username": "00:00:00:00:00:00",
        "port": 00000,
        "pin": "000-00-000"
    },
    "accessories": [
        {
            "accessory": "RadioPlayerPlus",
            "name": "Web Radio",
            "stations": [
                {
                    "name": "Deutschlandfunk",
                    "streamUrl": "http://st01.dlf.de/dlf/01/128/mp3/stream.mp3"
                },
                {
                    "name": "Fritz",
                    "streamUrl": "http://rbb-fritz-live.cast.addradio.de/rbb/fritz/live/mp3/128/stream.mp3"
                }
            ],
            "delay": 100,
            "reconnectAfter": 45
        }
    ]
}
```

Doku is work in progress. Feel free to make pull requests.
