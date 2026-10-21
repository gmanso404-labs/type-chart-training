# Type chart training

Single-file page to study the Pokémon type chart (Gen 6+, with Fairy): interactive graphs of super effective (x2) and not very effective (x0.5) matchups, plus a practice quiz. Available in Spanish and English (switcher in the top right corner; the choice is remembered in the browser).

- Live: https://gmanso404-labs.github.io/type-chart-training/
- Direct links: `#circular`, `#fuerzas`, `#estatico`, `#grupos`, `#practica`

No build step: `index.html` is the whole app (D3 7.9.0 from cdnjs). To run it locally:

```bash
python -m http.server 8000
```

Then open http://localhost:8000/#practica. Practice stats are stored only in the browser's `localStorage`.

Non-profit fan project. Pokémon and the type names are trademarks of Nintendo, Game Freak and The Pokémon Company.
