# Tor

## torrc

```text
## Tor opens a socks proxy on port 9150
SocksPort 0.0.0.0:9150

# Try for at most NUM seconds when building circuits. If the circuit isn't open in that time, give up on it. (Default: 1 minute.)
CircuitBuildTimeout 5

# Send a padding cell every N seconds to keep firewalls from closing our connections while Tor is not in use.
KeepalivePeriod 60

# Force Tor to consider whether to build a new circuit every NUM seconds.
NewCircuitPeriod 15

# How many entry guards should we keep at a time?
NumEntryGuards 8
```
