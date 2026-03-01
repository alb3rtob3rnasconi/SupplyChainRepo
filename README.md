# **Analisi Supply Chain & Ottimizzazione Logistica \- Cimplasta SrL**

Questo progetto contiene il **Report E-Commerce 2026** per l'ottimizzazione logistica di Cimplasta SrL. Consiste in una presentazione web interattiva e responsive progettata per illustrare il passaggio strategico da una gestione logistica interna a un modello in outsourcing (3PL \- Third Party Logistics) denominato "Zero Pensieri".

## **🚀 Visualizzazione Live**

Il progetto è già ospitato online ed è accessibile direttamente da qualsiasi dispositivo, senza necessità di installazione, compilazione o configurazione di server locali.

È possibile esplorare il report interattivo cliccando sul seguente link:

👉 [**Visualizza il Report Online \- Cimplasta SrL**](https://supplychainrepo.onrender.com)

## **📂 Struttura del Progetto**

La repository è composta da due file HTML principali, che fungono da presentazione direzionale:

1. **index.html (Documento Principale):**  
   * Illustra il concetto "Zero Pensieri".  
   * Mostra il flusso operativo aziendale (Cimplasta SrL ➜ Hub Logistico 3PL ➜ Corriere ➜ Cliente Finale).  
   * Contiene una tabella comparativa dei costi logistici (Gestione Interna vs Outsourcing).  
   * Analizza i Vantaggi Strategici (Pro) e i Punti di Attenzione (Contro).  
2. **Report3PL.html (Appendice Dati e Grafici):**  
   * **Benchmarking Prestazionale:** Valutazione di player di mercato (Shopify SFN, BRT, DHL, GLS, UPS) su parametri chiave. Affiancata da un'analisi testuale dettagliata dei Pro e Contro di ogni fornitore.  
   * **Composizione del Costo Logistico:** Spaccato percentuale delle voci che compongono il costo per singola spedizione con relative descrizioni approfondite.  
   * **Analisi Margine:** Confronto diretto del margine netto aziendale sul singolo ordine tra il modello a gestione interna e il modello in outsourcing.

## **📊 Rationale Strutturale e Scelta dei Grafici (Report 3PL)**

La pagina Report3PL.html è stata progettata seguendo un "funnel analitico" ben preciso, per guidare la dirigenza dalla fase di scelta macroscopica del partner fino al dettaglio dell'impatto sul conto economico. Ecco le motivazioni dietro le scelte progettuali:

### **1\. Valutazione Dettagliata Partner 3PL (Radar Chart)**

* **Motivazione Strutturale:** Questa sezione è stata posizionata intenzionalmente in cima. La selezione del partner è la decisione cardine e strategica da cui derivano a cascata tutte le altre dinamiche di costo e di servizio affrontate nel resto del documento.  
* **Scelta del Grafico (Radar Chart):** È lo strumento visivo perfetto per il benchmarking multi-dimensionale. Permette di sovrapporre visivamente i diversi spedizionieri/3PL valutandoli contemporaneamente su 5 KPI differenti (Costo, Velocità, IT, Capillarità, Assistenza). In un colpo d'occhio, la dirigenza può individuare se un partner è estremamente "sbilanciato" (es. eccellente in velocità ma pessimo nei costi, come DHL) oppure "equilibrato" (come Shopify o GLS).

### **2\. Composizione del Costo Logistico (Donut Chart Espanso)**

* **Motivazione Strutturale:** Una volta compreso il panorama dei partner disponibili, è necessario "zoomare" all'interno della singola tariffa applicata dal 3PL per comprenderne le reali leve di costo.  
* **Scelta del Grafico (Donut Chart \- Grafico a Ciambella):** Il grafico a ciambella è lo standard aureo per visualizzare visivamente le "parti di un tutto" (ovvero il *Total Landed Cost* per spedizione). L'approccio di espandere lateralmente il grafico con card testuali dettagliate è stato scelto per mantenere il grafico pulito (evitando tooltips illeggibili e troppo densi), permettendo al contempo di sviscerare analiticamente ogni singolo centro di costo nascosto (Picking, Materiali, Fuel Surcharge).

### **3\. Analisi Margine: Gestione Interna vs Outsourcing (Stacked Bar Chart)**

* **Motivazione Strutturale:** È la naturale e più importante conclusione del report. Dopo aver scelto i potenziali partner e compreso i costi unitari dell'outsourcing, la direzione necessita di vedere il "bottom line": l'impatto finale sui profitti reali rispetto alla situazione aziendale preesistente.  
* **Scelta del Grafico (Stacked Bar Chart \- Istogramma a Barre Impilate):** È la tipologia di grafico più efficace per confrontare due scenari complessivi (Gestione Interna vs Outsourcing) mostrando al contempo i "mattoncini" che li compongono. Fissando sull'asse verticale il Valore dell'Ordine Medio (es. €40) e impilando i costi fissi/variabili (Prodotto, Logistica, Marketing), lo spazio residuo posizionato in cima alla barra (evidenziato con il Blu Scuro istituzionale di Cimplasta) illustra visivamente, quantitativamente e inequivocabilmente il differenziale di Margine Netto tra le due soluzioni.

## **🎨 Scelte di Progettazione e Design**

Il design è stato curato per offrire un'esperienza di lettura pulita, istituzionale e "data-driven". Le principali scelte UI/UX includono:

* **Palette Cromatica Istituzionale:** \* Il colore di sfondo della pagina è stato impostato su una tonalità grigio-verde neutra (\#acb5b0) per ridurre l'affaticamento visivo.  
  * Il colore primario per titoli, accenti e hover state è il **Blu Scuro Cimplasta (\#243455)**, estratto direttamente dal logo aziendale per mantenere una forte coerenza di brand.  
  * La struttura interna (container e sezioni) utilizza un approccio "Light Theme" con sfondi bianchi (\#ffffff) e grigi chiari (slate-50, slate-100) per far risaltare il testo scuro (\#1e293b).  
* **Color Coding Specifico per Brand:**  
  Nei grafici e nelle sezioni di analisi dei competitor, i colori sono stati assegnati per riflettere l'identità visiva reale dei singoli corrieri/partner logistici, facilitando l'associazione mentale dei dati:  
  * **Shopify SFN:** Verde (\#008060)  
  * **BRT:** Rosso (\#cc0000)  
  * **DHL Express:** Giallo/Oro (\#d4a017)  
  * **GLS:** Blu (\#0033a0)  
  * **UPS Standard:** Marrone Scuro (\#351c15)  
* **Tipografia:** Utilizzo del web font **Inter** (importato da Google Fonts) per garantire massima leggibilità, un aspetto moderno e pulito tipico delle dashboard analitiche.

## **⚙️ Tecnologie Utilizzate**

Il progetto è stato sviluppato per essere leggero, veloce e senza dipendenze complesse da build system, risultando in un approccio "plug and play":

* **HTML5:** Struttura semantica delle pagine.  
* **Tailwind CSS (via CDN):** Framework utility-first utilizzato per l'intero styling, la responsività (mobile-first approach) e le animazioni di transizione (hover states). Nessuna configurazione locale necessaria.  
* **Chart.js (via CDN):** Libreria JavaScript utilizzata per il rendering dei grafici interattivi (Radar, Pie/Donut, Stacked Bar). I grafici includono tooltip personalizzati e sono completamente responsivi.

## **📱 Responsività**

Entrambi i file sono stati sviluppati per adattarsi perfettamente a qualsiasi dimensione di schermo.

* Su dispositivi **mobile**, i layout a griglia passano a una singola colonna, le frecce di processo cambiano orientamento (da orizzontale a verticale) e i grafici scalano automaticamente mantenendo la leggibilità.  
* Su **desktop**, il layout si espande fino a una larghezza massima di 1400px, sfruttando lo spazio per affiancare testi e grafici in modo ottimale.