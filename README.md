====================================

### EXECUTAR DOCKER DESKTOP

### CHATWOOT (password .env e yaml)
docker compose run --rm rails bundle exec rails db:chatwoot_prepare
docker compose up -d

### API
git clone https://github.com/EvolutionAPI/evolution-api.git
alterar nome do ./src/dev-env.yml para env.yml
npm install
npm start

### NGROK