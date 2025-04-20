# decision-api-python



---

## Lokalna instalacja

### 1. Klonowanie repozytorium

git clone https://github.com/tobiaszmichalak/decision-api-python-140919-ADWCR.git  
cd decision-api-python-140919-ADWCR

### 2. Utworzenie środowiska wirtualnego

python3 -m venv .venv  
source .venv/bin/activate

### 3. Ignorowanie środowiska w GIT

echo ".venv/" >> .gitignore

### 4. Instalacja zależności

pip install -r requirements.txt

### 5. Uruchomienie aplikacji

flask run

---

## Uruchomienie notebooka

Jeśli projekt zawiera notebook:

jupyter notebook Lab2.ipynb

---

## Uruchomienie za pomocą Dockera

### 1. Budowanie obrazu

docker build -t decision-api .

### 2. Uruchomienie kontenera

docker run -p 5000:5000 decision-api

Aplikacja będzie dostępna pod adresem: http://localhost:5000

---

## 🔧 Wymagania

- Python 3.7+
- Docker (opcjonalnie)
