# System Architecture

## High-Level Overview

Project Orion consists of two major subsystems:

1. GNSS Receiver
2. Embedded Processing

```
GNSS Antenna
      │
      ▼
 U.FL Connector
      │
      ▼
 MAX-M10S
      │ UART
      ▼
 ESP32-S3
      │
      ▼
 Future Applications
```

## GNSS Receiver

The MAX-M10S performs:

- RF amplification
- SAW filtering
- Acquisition
- Tracking
- Navigation solution
- Satellite decoding

The receiver outputs NMEA messages over UART.

## Embedded Processor

The ESP32-S3 receives GNSS data through UART.

Future revisions will include:

- WiFi
- Bluetooth
- Cloud connectivity
- AI integration
