# RF Design

## RF Frequency

GPS L1

1575.42 MHz


## RF Signal Path

```
GNSS Antenna

↓

U.FL Connector

↓

50 Ω Transmission Line

↓

MAX-M10S RF_IN

↓

Internal LNA

↓

SAW Filter

↓

GNSS Receiver
```

## Design Rules

- Short RF trace
- Continuous ground plane
- No vias on RF path
- 45° routing preferred
- Keep digital traces away from RF

## Lessons Learned

During Project Orion, several RF concepts were studied:

- Transmission lines
- Impedance matching
- Reflection
- SAW filters
- Low Noise Amplifiers
- RF PCB layout
