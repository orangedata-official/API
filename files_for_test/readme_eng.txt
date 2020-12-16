Addresses:

TEST environment:
https://apip.orangedata.ru:2443

TEST environment availability check URL for browsers:
https://apip.orangedata.ru:2443/api/v2/

TEST URL FOR queries:
https://apip.orangedata.ru:2443/api/v2/documents/

Test environment IP address 94.228.252.55

PRODUCTION environment:
https://api.orangedata.ru:12003

PRODUCTION environment availability check URL for browsers:
https://api.orangedata.ru:12003/api/v2/

PRODUCTION URL FOR queries:
https://api.orangedata.ru:12003/api/v2/documents/

Producrion IP addresses: 62.76.112.48 and 188.170.11.161
-------------------------------------------------



TEST FILES description:

client_ca.crt - The public part of the key for signing all client's certificates 
client.crt, client.key - TEST Client's certificate and secret part, generated with client_ca.crt (password 1234 was used)
cacert.pem - a set of root certificates
private_key.xml - TEST client's private key  for requests signing 

---------------------------------------------------
PRODUCTION FILE DESCRIPTION:

client_ca.crt - The public part of the key for signing all client's certificates
"INN".crt, "INN".key (real client's INN must be instead of "INN") - client's certificate (*.crt) and it's private part (*.key) generated with client_ca.crt (пароль 1234)
cacert.pem - a set of root certificates
Nebula.KeysGenerator 1.0.0.0.zip - Signature key generator application. This applicarion generates private and public part of client's  key. Clients  must generate their own private and public part and upload public part to www.orangedata.ru  production environment.


    