<h1>Google Images Scraping Project</h1>

<p>
Questo progetto si concentra sull'automazione del download di immagini da Google Immagini in base a una query di ricerca. Utilizzando tecniche 
  di web scraping, lo script permette di cercare automaticamente le immagini, raccoglierle e salvarle localmente per ulteriori analisi o utilizzo.
  <br>
  Nota: La cartella 'gattini_images' è solo una demo dell'output, utilizzando la query gattini gia inserita nello script.
</p>
<h4>Disclaimer: questo notebook è da utilizzarsi nel rispetto del GDPR.</h4>

<h3>Lo script incluso nel progetto è:</h3>
<ul>
  <li>
    <strong>scraper_mechanicalsoup.ipynb</strong>: Questo notebook Jupyter utilizza la libreria <strong>MechanicalSoup</strong> per eseguire 
    il web scraping su Google Immagini. Inserendo una query, lo script si collega a Google Immagini, raccoglie i link delle immagini risultanti 
    e le scarica nella directory locale. Lo script può essere modificato per controllare il numero di immagini da scaricare e la qualità delle stesse.
  </li>
</ul>

<h2>Funzionalità dello script</h2>
<ol>
  <li>
    <strong>Query personalizzata</strong>: Inserendo una query di ricerca specifica, lo script invia una richiesta a Google Immagini e raccoglie 
    i link delle immagini corrispondenti.
  </li>
  <li>
    <strong>Download automatico</strong>: Lo script scarica automaticamente le immagini trovate in una cartella locale, con la possibilità di 
    impostare un limite sul numero di immagini.
  </li>
  <li>
    <strong>Gestione degli errori</strong>: Il notebook include meccanismi per gestire eventuali errori che si verificano durante il processo di 
    scraping, come immagini mancanti o non accessibili.
  </li>
  <li>
    <strong>Facilità di personalizzazione</strong>: Lo script può essere facilmente modificato per cambiare parametri come il numero di immagini, 
    il formato del file e altre impostazioni di scraping.
  </li>
</ol>

<h2>Prerequisiti</h2>
<p>Per eseguire questo progetto, sono necessarie le seguenti librerie:</p>
<ul>
  <li><strong>MechanicalSoup</strong>: Una libreria Python per automatizzare l'interazione con siti web.</li>
  <li><strong>Jupyter Notebook</strong>: Per eseguire il notebook interattivo.</li>
  <li><strong>wget</strong>: Utilizzata per il download delle immagini dai link raccolti durante lo scraping.</li>
  <li><strong>os</strong> e <strong>shutil</strong>: Librerie Python native per la gestione del file system durante il salvataggio delle immagini.</li>
</ul>

<h2>Come usare lo script</h2>
<ol>
  <li>Clona il repository e apri il notebook <code>scraper_mechanicalsoup.ipynb</code> in Jupyter Notebook.</li>
  <li>Esegui le celle del notebook, inserendo la query desiderata quando richiesto.</li>
  <li>Le immagini scaricate verranno salvate nella cartella locale specificata all'interno del notebook.</li>
</ol>
