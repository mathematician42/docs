# WPA

```
ce_group=root
ap_scan=0
network={
  key_mgmt=IEEE8021X
  eap=PEAP
  phase2="autheap=MSCHAPV2"
  identity="<username>"
  password="<password>"
  priority=2
}
```

Run

```
wpa_supplicant -D wired -i enp3s0 -c wpa.conf -dd -t
```
