# Passwort Generator mit User Interface

## 📦 Python-Projekt mit virtueller Umgebung (.venv)

Dieses Projekt verwendet eine **virtuelle Python-Umgebung** (`.venv`), um Abhängigkeiten lokal und isoliert zu verwalten.

---

## 🔧 Voraussetzungen

- [Python 3.7+](https://www.python.org/downloads/)
- Optional: [Visual Studio Code](https://code.visualstudiocode.com/)

---

## 🚀 Installation

### 1. Repository klonen (falls du Git verwendest)

    git clone <https://github.com/Dravock/pw-generator.git>

### 2. Virtuelle Umgebung anlegen

    python -m venv .venv

### 3. Umgebung aktivieren

#### ▶️ Auf Windows (cmd)

    .venv\Scripts\activate

#### ▶️ Windows (PowerShell)

    .venv\Scripts\Activate.ps1

#### ▶️ macOS / Linux

    source .venv/bin/activate

### 4. Abhängigkeiten installieren

#### Falls ein requirements.txt vorhanden ist

    pip install -r requirements.txt

#### 💡 Hinweis

Wenn du später noch weitere externe Pakete installierst (z. B. ```requests```, ```pandas```, etc.), kannst du sie mit folgendem Befehl automatisch zur Datei hinzufügen:

    pip freeze > requirements.txt

---

## 🧪 Projekt starten

Um das Projekt zu starten Navigiere in das ```Root``` Verzeichniss und führe folgenden Befehl aus

**bash console:**

    python main.py

---

## ❌ Deaktivieren der Umgebung

Um die Virtuelle Umgebung zu deaktivieren Navigiere in ```./.venv``` dort führt man die deactivate datei aus

**bash console:**

    deactivate
