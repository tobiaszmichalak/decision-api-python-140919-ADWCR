# Decision API Python

## Klonowanie i konfiguracja

Sklonuj repozytorium:
\`\`\`bash
git clone https://github.com/tobiaszmichalak/decision-api-python-140919-ADWCR.git
cd decision-api-python-140919-ADWCR
\`\`\`

## Przygotowanie środowiska Python

Wymagania: Python 3.7 lub nowszy.

Utwórz wirtualne środowisko:
\`\`\`bash
python3 -m venv .venv
source .venv/bin/activate
\`\`\`

Zainstaluj biblioteki:
\`\`\`bash
pip install -r requirements.txt
\`\`\`

Uruchom aplikację Flask:
\`\`\`bash
python app.py
\`\`\`

Opcjonalnie uruchom notebook Jupyter:
\`\`\`bash
jupyter notebook Lab2.ipynb
\`\`\`

## Docker

Budowanie obrazu:
\`\`\`bash
docker build -t modelML .
\`\`\`

Uruchamianie kontenera:
\`\`\`bash
docker run -p 5000:5000 modelML
\`\`\`
EOF
