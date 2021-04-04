# netcup-wildcard-domain

## How to

1. Generate your API key and password for netcup using https://www.customercontrolpanel.de/run/daten_aendern.php?sprung=api
2. Insert NC_Apikey, NC_Apipw and your Netcup Customer Id (NC_CID) into the docker-compose file
3. Edit the wildcard domain listed in command (e.g. *.example.com )
4. Run `docker-compose up` and enjoy the automatic generation process (can take some minutes) 