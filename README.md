# plaidpiper.github.io

Hosts the public key for the Tesla Fleet API partner registration used by
Home Assistant (hestia), at
`/.well-known/appspecific/com.tesla.3p.public-key.pem`.

The matching private key lives on hestia (`/config/tesla_fleet.key`) and in
Vault (`secret/homelab/tesla`). Rotating it means re-registering the domain
and re-pairing the virtual key on the car.
