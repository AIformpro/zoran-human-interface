
# interface humaine zoran

Module **UI/UX opérateur** pour l’écosystème Zoran / QuantaGlottal©® — permet à un utilisateur non technique de piloter, configurer et surveiller les agents Zoran.

---

## ✨ Fonctionnalités
- **Interface web** intuitive (React/Vue/Svelte) pour l’exécution des agents
- **Configuration visuelle** des injecteurs 4 Champs
- **Tableaux de bord** temps réel (télémétrie, état des agents, logs)
- **Gestion multi-agents** : contrôle et supervision simultanée
- **Alertes et notifications** configurables
- **Modes prédéfinis** : standard, heavy, mimetic boost
- **Compatibilité mobile** (PWA)

---

## 📦 Installation (développement)
```bash
npm install
npm run dev

ou en Python (backend API) :

pip install -e .


---

⚡ Exemple rapide (backend Flask)

from interface_humaine_zoran import app

if __name__ == "__main__":
    app.run(host="0.0.0.0", port=8080)


---

🧱 Structure suggérée

src/interface_humaine_zoran/
  __init__.py
  api.py                # backend API REST
  ui/                   # code front-end (React/Vue/Svelte)
    App.vue
    components/
  telemetry.py          # liaison avec module zoran-télémétrie
  injecteurs.py         # chargement/apply injecteurs
  config.py             # configuration persistante
tests/
  test_api.py
package.json
pyproject.toml
.gitignore
LICENSE
README.md


---

🧪 Tests

pytest -q          # backend
npm run test       # frontend


---

🔐 Éthique

L’interface respecte le principe vivant > humain :

filtrage des actions non conformes

transparence sur les données collectées

contrôle explicite par l’utilisateur



---

📜 Licence

MIT — voir LICENSE.


---

Auteur : Frédéric Tabary — Institut IA
Contact : 0645605023 — Canada, Montréal, France
INSTITUT🦋 IA INC., 7100-380, rue Saint-Antoine Ouest, Montréal (Québec) H2Y 3X7.



