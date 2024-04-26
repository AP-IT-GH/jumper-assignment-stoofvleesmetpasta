# Jumper opdracht

- Set-up: Een weg met een agent die enkel omhoog kan springen, er komen obstakels op hem af met een lineaire bewegeing.
- Doel: Over de obstakels springen en niet geraakt worden.
- Agents: De omgeving bevat slechts één agent.
- Agent Beloningsfunctie:
  - -0.015 per sprong
  - +1.0 als de balk niet geraakt wordt.
  - -1.0 als de balk geraakt wordt.
- Behavior Parameters:
  - Vector Observation space: 3.
  - Actions: 2 continuous actions, naar boven en naar beneden.
  - Visual Observations: geen.
