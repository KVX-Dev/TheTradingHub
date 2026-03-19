QuantHub: Professional Trading Journal
Execute like a machine. Analyze like a scientist.

QuantHub is a high-performance, local-first desktop application built for traders who prioritize data over emotions. Designed specifically for quantitative strategies like QSA-12, it provides deep insights into your "Edge" through R-multiple analysis and psychological tracking.

⚡ Key Features
Zero-Latency Local Storage: Powered by SQLite. Your trade data never leaves your machine.

Quantitative Metrics: Automated calculation of R-Multiples, Profit Factor, and Expectancy.

Visual Equity Curve: Real-time tracking of your account growth using interactive Plotly charts.

Strategy Tagging: Analyze which setups (e.g., QSA-12, Breakouts, Mean Reversion) are actually printing money.

The "Pro" UI: A sleek, Bloomberg-inspired Dark Mode interface built with Tailwind CSS and Shadcn/ui.

Psychology Log: Track your emotional state during entries to identify "Tilt" before it costs you capital.

🛠 Tech Stack
Framework: Electron (Desktop Core)

Frontend: React + Tailwind CSS

Components: Shadcn/ui

Database: SQLite

Charts: Recharts / Plotly

🚀 Getting Started
For Users
Go to the Releases page.

Download the .exe (Windows) or .dmg (macOS) for the latest version.

Install and start journaling.

For Developers
Clone the repo and install dependencies:

Bash
git clone https://github.com/yourusername/quanthub.git
cd quanthub
npm install
npm run dev
📊 The QSA-12 Logic
QuantHub is optimized for the Quantitative Structure Alignment (QSA-12) strategy:

Bias: H1 EMA 50 alignment.

Execution: M5 Change of Character (ChoCh) + RSI(7) Momentum Trigger.

Risk: Fixed 1:2 RR (automatically calculated in-app).

🛡 Disclaimer
Trading involves significant risk. This software is a tool for documentation and analysis. It does not provide financial advice or automated execution. Always backtest your strategies before risking real capital.

🤝 Contributing
Contributions are what make the open-source community such an amazing place to learn, inspire, and create. Any contributions you make are greatly appreciated.

Fork the Project

Create your Feature Branch (git checkout -b feature/AmazingFeature)

Commit your Changes (git commit -m 'Add some AmazingFeature')

Push to the Branch (git push origin feature/AmazingFeature)

Open a Pull Request
