# FLEXCOM Protocol Specification

## Protocol Name
### FLEXCOM (Flexible Exchange Communication Over Messages)

## Description
### FLEXCOM is an internet protocol designed for multiplayer games to send arbitrary data to clients in an easily parsable format. It facilitates structured message-based interactions, ensuring robust data exchange and efficient handling of connections using threaded communication.

## Message Structure
#### Prefix: Identifier for the type of the message (e.g., "MAP" for map data, "LOCATION" for x, y coordinates)
#### MessageName: Name that specifies the subtype of the message (e.g., "COLLIDERS" for map collision data, "X" for the x coordinate)
#### IP: IP address of the client that sent this message to the server
#### Data: Payload of the message

## Example
#### LOCATION_X 124.254.706 15
