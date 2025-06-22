# Cats & Dogs - Frontend Test

## 📌 Descrizione

Questo test utilizza [Vite](https://vitejs.dev/) come bundler e [Bootstrap 5](https://getbootstrap.com/) come framework CSS.

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

# Integrazione in Wordpress 🚀

## Suddivisione in blocchi/componenti della pagina per contenuti flessibili 🧩

Per garantire modularità e flessibilità nella costruzione delle pagine, utilizziamo **Advanced Custom Fields (ACF)** con la **Flexible Content** incluso nello stesso plugin.  
Questo approccio consente di creare layout composti da blocchi e componenti riutilizzabili, facilmente configurabili dal backend.  
Il Flexible Content permette di definire diverse “righe” o “blocchi” personalizzati, ognuno con i propri sotto-campi, offrendo così la massima libertà nella composizione dei contenuti da parte degli editor. 🎨

---

## Gestione delle FAQ ❓

Le FAQ vengono gestite tramite un **Custom Post Type (CPT)** dedicato in WordPress.  
Ogni FAQ è un singolo post all’interno di questo CPT, permettendo una gestione ordinata e scalabile dei contenuti. 📚

---

## Plugin e metodologie consigliate 🧰

| Funzionalità                        | Plugin / Metodo consigliato                                                   |
| ----------------------------------- | ----------------------------------------------------------------------------- |
| 🌐 Multi-lingua e traduzioni        | WPML (robusto e completo), oppure Polylang (più leggero)                      |
| 📋 Gestione del menu di navigazione | Menù nativo di WordPress                                                      |
| 🔍 Ottimizzazione SEO               | Yoast SEO oppure Rank Math                                                    |
| 📬 Pagine con form di contatto      | Contact Form 7 o Gravity Forms (premium)                                      |
| 🍪 Gestione consensi cookie         | Complianz (GDPR/Cookie compliance), oppure Cookiebot per soluzioni enterprise |

---
