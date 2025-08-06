# All-in-document-solution-mongodb
cat > README.md <<'MD'
# Bike Sharing — MongoDB Test Kit (Graph + Time Series)
Quick start:
  docker compose up -d
  docker compose exec mongo mongosh "mongodb://admin:changeme@localhost:27017/admin" /work/scripts/seed.js
  docker compose exec mongo mongosh "mongodb://admin:changeme@localhost:27017/admin" /work/queries/run_samples.js
MD
