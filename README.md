# Cats & Dogs - Frontend Test

## 📌 Descrizione

Per questo test ho utilizzato [Vite](https://vitejs.dev/) come bundler e [Bootstrap 5](https://getbootstrap.com/) come framework CSS.

Anche se la pagina è in HTML statico e tutto è contenuto in un unico file index.html, l’ho comunque strutturata pensando in ottica modulare.

Ho suddiviso il markup in section ben definite (esempio: hero, cards, features, call-to-action e faqs) proprio per rendere il codice leggibile e pronto, eventualmente, per una futura integrazione in un CMS come WordPress.

In pratica, ogni blocco è pensato come se fosse un componente riutilizzabile. Questo approccio torna molto utile quando si passa alla gestione dinamica dei contenuti: ogni section HTML può diventare facilmente un "partial" o un layout di blocco.

## 🔧 Requisiti

- **Node.js** version **18 or higher**

## 🚀 Setup ambiente locale

1. **Clona il repository**

   ```bash
   git clone https://github.com/francescodisanto96/frontend-test
   cd cartella-tuo-progetto

   ```

2. **Installa i Node modules**

   ```bash
   npm install

   ```

3. **Avvia il server di sviluppo**

   ```bash
   npm run dev
   ```

Il progetto sarà disponibile su http://localhost:5173 o su altra porta indicata dal terminale.

4. **Compila per la produzione**

```bash
npm run build

```

---

## 🚀 Integrazione in Wordpress

### 🧩 Suddivisione in blocchi/componenti della pagina per contenuti flessibili

In un contesto WordPress, per ottenere flessibilità e mantenere il controllo sul layout e sui contenuti nella costruzione delle pagine, possiamo utilizzare **Advanced Custom Fields (ACF)** con **Flexible Content** incluso nello stesso plugin.

Con ACF Flexible Content possiamo costruire una struttura "a blocchi" - ognuno con i propri sotto-campi - ed ogni blocco può rappresentare una sezione della pagina (esempio: hero, cards, features, call-to-action e faqs) e l’editor può scegliere quali blocchi usare e in quale ordine.

---

### ❓ Gestione delle FAQ

Le FAQ possono essere gestite tramite un **Custom Post Type (CPT)** dedicato in WordPress.  
Ogni FAQ è un singolo post all’interno di questo CPT, permettendo una gestione ordinata e scalabile dei contenuti.

---

### 🧰 Plugin e metodologie consigliate

| Funzionalità                        | Plugin / Metodo consigliato    |
| ----------------------------------- | ------------------------------ |
| 🌐 Multi-lingua e traduzioni        | WPML o Polylang                |
| 📋 Gestione del menu di navigazione | Menu nativo di WordPress       |
| 🔍 Ottimizzazione SEO               | Yoast SEO o Rank Math          |
| 📬 Pagine con form di contatto      | Contact Form 7 o Gravity Forms |
| 🍪 Gestione consensi cookie         | Complianz o Cookiebot          |

---
