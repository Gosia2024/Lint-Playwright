

````md
## Wichtige Daten

**Projektname:** Lint Playwright Projekt

**Ziel:**  
Eine einfache Webseite lokal und automatisch testen.

**Tools:**  
- npm
- ESLint
- Vite
- Playwright
- GitHub Actions

**Wichtige Befehle:**

```bash
npm install
npm run lint
npm run test:chromium
npm run dev
````

**Wichtige Dateien:**

```text
index.html
package.json
eslint.config.mjs
playwright.config.js
test/homepage.spec.js
.github/workflows/test.yml
```

**Lokale Tests:**

```bash
npm run lint
npm run test:chromium
```

**GitHub Actions macht automatisch:**

```bash
npm ci
npm run lint
npx playwright install --with-deps chromium
npm run test:chromium
```

**Merksatz:**
Was lokal im Terminal funktioniert, kann GitHub Actions automatisch ausführen.

```
