# neural_networks
# Neural Networks Project

## 📌 Opis projektu

Ten projekt dotyczy **sieci neuronowych (Neural Networks)** i ma na celu zrozumienie, implementację oraz eksperymentowanie z podstawowymi i bardziej zaawansowanymi modelami uczenia maszynowego. Projekt może służyć zarówno do nauki, jak i jako baza pod dalsze eksperymenty badawcze.

Główne zagadnienia poruszane w projekcie:

* perceptron i sieci wielowarstwowe (MLP)
* funkcje aktywacji
* proces uczenia (backpropagation)
* optymalizacja i regularyzacja
* ewaluacja modeli

---

## 🧠 Zakres funkcjonalny

Projekt zawiera m.in.:

* implementację sieci neuronowej od podstaw **lub** z użyciem bibliotek ML
* trenowanie modelu na przykładowych danych
* testowanie i ocenę jakości modelu
* wizualizację wyników (np. accuracy, loss)

---

## 🛠️ Technologie

W projekcie wykorzystano:

* **Python 3.x**
* **NumPy** – obliczenia numeryczne
* **Matplotlib / Seaborn** – wizualizacja danych
* **PyTorch / TensorFlow / Keras** *(opcjonalnie, zależnie od wersji projektu)*

---

## 📂 Struktura projektu

```
.
├── data/           # Zbiory danych
├── src/            # Kod źródłowy
│   ├── model.py    # Definicja sieci neuronowej
│   ├── train.py    # Proces trenowania
│   └── utils.py    # Funkcje pomocnicze
├── results/        # Wyniki i wykresy
├── README.md
└── requirements.txt
```

---

## ▶️ Uruchomienie projektu

1. Sklonuj repozytorium:

```bash
git clone <adres_repozytorium>
cd neural-networks-project
```

2. Zainstaluj zależności:

```bash
pip install -r requirements.txt
```

3. Uruchom trenowanie modelu:

```bash
python src/train.py
```

---

## 📊 Wyniki

Po zakończeniu trenowania:

* wyniki zapisywane są w katalogu `results/`
* generowane są wykresy funkcji straty oraz dokładności

---

## 🎯 Cele edukacyjne

* zrozumienie matematycznych podstaw sieci neuronowych
* praktyczna implementacja algorytmu uczenia
* analiza wpływu hiperparametrów na jakość modelu

---

## 🚀 Możliwe rozszerzenia

* dodanie sieci konwolucyjnych (CNN)
* eksperymenty z różnymi optymalizatorami
* walidacja krzyżowa
* uczenie na rzeczywistych zbiorach danych

---

## 👤 Autor

Projekt wykonany w celach edukacyjnych.

---

## 📄 Licencja

Projekt udostępniony na licencji MIT.
