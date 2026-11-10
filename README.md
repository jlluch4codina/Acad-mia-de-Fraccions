# 🧮 Acadèmia de Fraccions (Tema 2 - Nombres Enters i Fraccions)

Una aplicació web interactiva i educativa dissenyada per a l'aprenentatge, pràctica i repàs de les fraccions de nombres enters. Aquest projecte està basat directament en el temari de matemàtiques de secundària (concepte de fracció, representació gràfica, fraccions equivalents, amplificació, simplificació, reducció a comú denominador mitjançant m.c.m., i totes les operacions bàsiques).

---

## 🚀 Característiques Principals

- **🎨 Visualitzador Gràfic Interactiu:** Representació dinàmica de fraccions pròpies i impròpies mitjançant blocs de colors (com ara $\frac{3}{4}$ o $\frac{7}{4}$).
- **📖 Mòdul Didàctic de Teoria (4 Nivells):**
  - **Nivell 1:** Conceptes fonamentals ($a, b \in \mathbb{Z}$), representació visual i càlcul de la fracció d'una quantitat.
  - **Nivell 2:** Fraccions equivalents (comprovació per producte en creu $a \cdot d = b \cdot c$), amplificació i simplificació.
  - **Nivell 3:** Reducció a comú denominador mitjançant la descomposició en factors primers i càlcul del m.c.m.
  - **Nivell 4:** Suma, resta, multiplicació en línia recta i divisió en creu amb exercicis de simplificació successiva.
- **📝 Fitxa d'Exercicis (30 Problemes Resolts):**
  - **Mode Un a Un (Interactiu):** Navegació pas a pas exercici per exercici amb feedback immediat i botó "Següent Exercici".
  - **Full per Imprimir:** Generació d'una fitxa de treball en format paper o PDF amb opció d'activar o ocultar les solucions explicades.
- **🧮 Calculadora pas a pas:** Permet introduir qualsevol parell de fraccions i obtenir la resolució detallada exactament com s'explica a classe.
- **🏆 Quiz Express:** Qüestionari interactiu amb sistema de punts, ratxa de respostes i explicacions pas a pas.

---

## 🛠️ Tecnologies Utilitzades

- **HTML5 / JSX:** Estructura semàntica i accessible.
- **Tailwind CSS:** Disseny de la interfície fluid, modern i completament adaptable a mòbils, tauletes i escriptori.
- **Lucide Icons:** Iconografia clara i intuitiva.
- **JavaScript (Vanilla / React):** Lògica matemàtica auto-continguda sense dependències externes pesades.

---

## 📦 Instal·lació i Ús

Pots executar el projecte de dues maneres diferents:

### Opció A: Versió HTML Directa (Sense instal·lació)
1. Descarrega o clona aquest repositori.
2. Obre el fitxer `index.html` directament a qualsevol navegador web (Chrome, Firefox, Safari, Edge).

### Opció B: Versió React
1. Assegura't de tenir instal·lat [Node.js](https://nodejs.org/).
2. Clona aquest repositori:
   ```bash
   git clone https://github.com/el-teu-usuari/academia-fraccions.git
   cd academia-fraccions
   ```
3. Instal·la les dependències i inicia el servidor de desenvolupament:
   ```bash
   npm install
   npm run dev
   ```

---

## 📂 Estructura del Projecte

```text
.
├── index.html          # Aplicació web auto-continguda en un sol fitxer HTML
├── App.jsx             # Component principal en React
├── README.md           # Documentació del projecte
```

---

## 📄 Llicència

Aquest projecte té llicència [MIT](LICENSE). Pots utilitzar-lo, modificar-lo i redistribuir-lo lliurement per a fins educatius.