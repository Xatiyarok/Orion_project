# PCB Design

## Design Software

EasyEDA

## PCB Stack

Two-layer PCB

Future revision:

- Four-layer PCB

## Placement Strategy

Placement order:

1. U.FL connector
2. MAX-M10S
3. Decoupling capacitors
4. ESP32-S3
5. Test points

## Routing Priority

1. RF
2. Power
3. UART
4. Control signals

## Power

Current revision uses a shared 3.3 V rail.

## Ground Plane

A continuous ground plane is used to minimize RF return impedance.
