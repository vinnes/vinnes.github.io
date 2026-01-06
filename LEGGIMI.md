# Istruzioni (fornite dall'AI)

Per editare un blog online basato su Jekyll (un generatore di siti statici scritto in Ruby che trasforma file Markdown in pagine HTML), non serve un singolo programma, ma una combinazione di strumenti. Ecco una panoramica dei principali componenti necessari, assumendo che tu voglia gestire contenuti, personalizzare temi e pubblicare il blog. Nota che Jekyll è open-source e gratuito, ma richiede un po' di setup tecnico.

- 1. Ruby e Jekyll (il cuore del sistema)
Ruby: Il linguaggio di programmazione su cui si basa Jekyll. Devi installarlo sul tuo computer (versione 2.5 o superiore).
Scaricalo da rubyinstaller.org (per Windows) o usa il package manager del tuo OS (es. apt su Linux, Homebrew su macOS).
Jekyll: Una gemma Ruby. Una volta installato Ruby, usa il comando

```bash
gem install jekyll bundler
```

nel terminale per installarlo.
Bundler: Uno strumento per gestire dipendenze Ruby; viene installato insieme a Jekyll.

- 2. Editor di testo o IDE per scrivere contenuti
Un editor per modificare file Markdown (.md), che sono il formato principale per i post del blog.
Raccomandati: Visual Studio Code (gratuito, con estensioni per Markdown e Jekyll), Sublime Text, Atom o Vim/Emacs per utenti avanzati.
Estensioni utili in VS Code: "Markdown Preview Enhanced", "Jekyll Snippets" o "GitHub Markdown Preview".

- 3. Sistema di controllo versione (Git)
Per tracciare modifiche, collaborare e pubblicare.
Git: Installalo da [git-scm.com](https://git-scm.com). È essenziale per pushare il sito su piattaforme come GitHub Pages.
GitHub Desktop (opzionale): Un'interfaccia grafica per Git, utile se non sei a tuo agio con la riga di comando.

- 4. Piattaforma di hosting/pubblicazione per rendere il blog online.
GitHub Pages: Gratuito e integrato con GitHub; basta "pushare" il repository Jekyll e viene generato automaticamente.
Netlify o Vercel: Piattaforme per deployment continuo, con supporto nativo per Jekyll (gratuite per progetti piccoli).
Altri: Heroku, AWS S3, o un server VPS con supporto statico.

- 5. Strumenti aggiuntivi (opzionali ma utili)
Node.js e npm: Se vuoi aggiungere JavaScript o usare temi avanzati (non essenziale per Jekyll base).
Browser: Per visualizzare l'anteprima locale (Jekyll ha un server built-in con jekyll serve).
Temi e plugin: Scaricali da jekyllthemes.org o GitHub; alcuni richiedono configurazione aggiuntiva.

# Come iniziare
Installa Ruby e Jekyll.
Crea un nuovo sito con

```bash
jekyll new myblog
```

e naviga nella cartella.
Modifica i file Markdown in _posts/ per aggiungere contenuti.
Anteprima con jekyll serve (visita http://localhost:4000).
Pusha su GitHub e abilita Pages per pubblicare online.
Se sei nuovo a Jekyll, consulta la documentazione ufficiale su [Jekyll](jekyllrb.com).
