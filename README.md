# home assistant core docker

## install HACS
https://hacs.xyz/docs/use/download/download/#to-download-hacs

- Open a terminal.
- Go inside the container with docker exec -it <name of the container running homeassistant> bash.
- Run the HACS download script.
  `wget -O - https://get.hacs.xyz | bash -`
- restart HA
- follow: https://hacs.xyz/docs/use/configuration/options/#changing-the-hacs-configuration-options

## HACS
- `kiosk-mode`:  clean dashboard for tablet/family
- `browser_mod 2`: for instance show popup when solar power is to be used!
- `Pyscrips`
- `Mushroom`: nicer cards

## Update Home Assisstant with Docker
- get new updated image:   
`docker compose pull` 
- restart:   
`docker compose up -d`
