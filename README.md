# keycloak-tut
Keycloak tutorial


Run Key Cloak
```bash
# Make work dir
mkdir ~/work/keycloak-tut
# Clone repo
git clone https://github.com/ajarv/keycloak-tut .
# Checkout keycloack sample setup
cd ~/work/keycloak-tut
git checkout 01-keycloak-setup

# Run keycloak 
docker-compose up -d

```

Access Keycloak at http://localhost:8080/auth