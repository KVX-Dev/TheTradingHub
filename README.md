# QuantHub: Professional Trading Journal

> **Execute like a machine. Analyze like a scientist.**

QuantHub ist eine leistungsstarke, **local-first** Desktop-Anwendung für Trader, die Daten über Emotionen stellen. Speziell entwickelt für quantitative Strategien wie **QSA-12**, bietet es tiefe Einblicke in deinen "Edge" durch R-Multiple-Analysen und psychologisches Tracking.

---

## ⚡ Key Features

* **Zero-Latency Local Storage:** Basierend auf SQLite. Deine Trading-Daten verlassen niemals deinen Rechner.
* **Quantitative Metriken:** Automatisierte Berechnung von **R-Multiples**, Profit-Faktor und Erwartungswert (Expectancy).
* **Visuelle Equity Curve:** Echtzeit-Tracking deines Kontowachstums mit interaktiven Charts (Plotly/Recharts).
* **Strategy Tagging:** Analysiere, welche Setups (z. B. QSA-12, Breakouts, Mean Reversion) tatsächlich profitabel sind.
* **Pro-Level UI:** Ein elegantes, von Bloomberg inspiriertes Dark-Mode-Interface, gebaut mit Tailwind CSS und Shadcn/ui.
* **Psychologie-Log:** Dokumentiere deinen emotionalen Zustand bei jedem Trade, um "Tilt" zu identifizieren, bevor er Kapital kostet.

---

## 🛠 Tech Stack

* **Framework:** [Electron](https://www.electronjs.org/) (Desktop Core)
* **Frontend:** [React](https://reactjs.org/) + [Tailwind CSS](https://tailwindcss.com/)
* **UI Components:** [Shadcn/ui](https://ui.shadcn.com/)
* **Datenbank:** [SQLite](https://www.sqlite.org/)
* **Visualisierung:** [Recharts](https://recharts.org/) / [Plotly](https://plotly.com/javascript/react/)

---

## 🚀 Getting Started

### Für Nutzer
1. Gehe zur [Releases](https://github.com/yourusername/quanthub/releases) Seite.
2. Lade die `.exe` (Windows) oder `.dmg` (macOS) der neuesten Version herunter.
3. Installieren und direkt mit dem Journaling starten.

### Für Entwickler
Klone das Repository und installiere die Abhängigkeiten:

```bash
git clone [https://github.com/yourusername/quanthub.git](https://github.com/yourusername/quanthub.git)
cd quanthub
npm install
npm run dev
📊 Die QSA-12 Logik
QuantHub ist von Haus aus für die Quantitative Structure Alignment (QSA-12) Strategie optimiert:

Bias: H1 EMA 50 Alignment Check.

Execution: M5 Change of Character (ChoCh) + RSI(7) Momentum Trigger.

Risk: Festes 1:2 CRV (wird automatisch in der App berechnet).

🛡 Disclaimer
Trading ist mit erheblichen Risiken verbunden. Diese Software ist ein Werkzeug zur Dokumentation und Analyse. Sie stellt keine Finanzberatung oder automatisierte Ausführung dar. Backteste deine Strategien immer ausgiebig, bevor du echtes Kapital riskierst.

🤝 Contributing
Beiträge machen die Open-Source-Community zu einem fantastischen Ort zum Lernen und Gestalten. Jeder Beitrag ist willkommen.

Projekt forken

Feature Branch erstellen (git checkout -b feature/AmazingFeature)

Änderungen committen (git commit -m 'Add some AmazingFeature')

Branch pushen (git push origin feature/AmazingFeature)

Pull Request eröffnen

GitHub Description (Kurzbeschreibung für die Sidebar)
📊 QuantHub | High-end, local-first Electron App für quantitative Trader. Tracke R-Multiples, Equity Curves und meistere die QSA-12 Strategie mit einem Bloomberg-inspirierten UI. 🚀


---
