# 1. Clone your repo
git clone https://github.com/YOUR_ORG/nmdr.git
cd nmdr

# 2. Start DHIS2
docker compose up -d

# 3. Watch logs until ready (~2-3 min)
docker logs -f nmdr_dhis2
