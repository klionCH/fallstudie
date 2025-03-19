Reflexion zur GitHub Actions Pipeline

1️⃣ Aufbau der Pipeline

Linting-Job: Prüft Code-Stil mit ESLint.

Testing-Job: Führt Jest-Tests aus.

Deployment-Job: Erfolgt nur nach erfolgreichem Linting & Testing.

2️⃣ Herausforderungen & Erkenntnisse

Die Jest Tests funktionieren nicht. Ich habe versucht jest in den Package.json hinzuzufügen, was aber nicht geholfen hat.

3️⃣ Verbesserungspotenzial

Parallelisierung: Matrix-Tests für verschiedene Node.js-Versionen.

Prettier-Job: Automatische Code-Formatierung.

Langfristig: Automatisches Deployment & Slack/Discord-Integration.

4️⃣ Fazit

Klare Trennung der Jobs verbessert Wartbarkeit & Debugging.

Pipeline kann weiter optimiert werden für Performance & Skalierbarkeit.

