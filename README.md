# Data-Visualization-Project
Data visualization object carried out by my group. Successful infographics thanks to a tableau, check it out!
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="utf-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <!-- The above 3 meta tags *must* come first in the head; any other head content must come *after* these tags -->
    <meta name="description" content="">
    <meta name="author" content="">
    <link href="https://fonts.googleapis.com/css?family=Montserrat:400,700|PT+Serif:400,400i,700,700i|Source+Code+Pro|Source+Sans+Pro:200,200i,300,300i,400,400i,600,600i,700,700i,900,900i" rel="stylesheet">
    <link rel="icon" href="../../favicon.ico">
    <title>Le ombre di Los Angeles</title>
    <!-- Bootstrap core CSS -->
    <link href="css/bootstrap.min.css" rel="stylesheet">
    <!-- IE10 viewport hack for Surface/desktop Windows 8 bug -->
    <link href="css/ie10-viewport-bug-workaround.css" rel="stylesheet">
    <!-- Custom styles for this template -->
    <link href="css/style.css" rel="stylesheet">
    <!-- Just for debugging purposes. Don't actually copy these 2 lines! -->
    <!--[if lt IE 9]><script src="../../assets/js/ie8-responsive-file-warning.js"></script><![endif]-->
    <script src="../../assets/js/ie-emulation-modes-warning.js"></script>
    <!-- HTML5 shim and Respond.js for IE8 support of HTML5 elements and media queries -->
    <!--[if lt IE 9]>
    <script src="https://oss.maxcdn.com/html5shiv/3.7.3/html5shiv.min.js"></script>
    <script src="https://oss.maxcdn.com/respond/1.4.2/respond.min.js"></script>
    <![endif]-->
</head>
<body>
    <!-- Intro con titolo e immagine. Inserire immagine in /media/ con il nome cover.png
         Al posto dei segna posto aggiungere il vostro nome negli <span> -->
    <div class="intro">
        <div class="container">
            <div class="row">
                <div class="col-md-8 col-md-offset-2 text">
                    <h5 class="text-center">Data Visualization Lab UNIMIB - 2017/2018</h5>
                    <h1 class="text-center">Le ombre di <br /> Los Angeles</h1>
                    <h4 class="text-center">
                        Un progetto di <br />
                        <span class="name">Stefano Luca Balu (DS)</span>,
                        <span class="name">Daniele Lacapra (DS)</span>,
                        <span class="name">Roberta Pollastro (DS)</span>,<br />
                        <span class="name">Alessandra Siano (TTC)</span> e
                        <span class="name">Valeria Strano (TTC)</span>
                    </h4>
                </div>
            </div>
        </div>
    </div>

    <!-- Primo blocco di testo -->
    <div class="container">
        <div class="row">
            <div class="col-md-8 col-md-offset-2">

                <h2>
                    Introduzione e obiettivo
                </h2>

                <p>
                    <strong>Los Angeles</strong> attira ogni anno milioni di turisti da tutto il mondo curiosi di visitare le sfaccettature che offre la metropoli californiana. La città non è solo famosa per essere la capitale mondiale dell'intrattenimento, ma  anche per l'offerta di una grande vivacità culturale e artistica che contribuisce a renderla meta ambita.
                </p>
                <p>
                    Chi non ha mai sognato di visitare e vedere con i propri occhi le famose colline di Hollywood, o visitare Beverly Hills centro esclusivo di moda e di bellezza di rilevanza mondiale?
                </p>
                <p>
                    Ma L.A. non è solo sfarzo e ricchezza: analizzando a fondo ogni distretto si possono cogliere profonde differenze.
                    <br />
                    Questa diversità, oltre ad essere evidente da un punto di vista culturale e artistico, si presenta anche da un punto di vista criminale.
                </p>
                <p>
                    Grazie al dataset rilasciato dal dipartimento californiano, opera di una parsimoniosa trascrizione manuale dei rapporti ufficiali della polizia, si sono potuti analizzare i distretti da un <strong>punto di vista criminale, sociale e culturale</strong>, quest'ultimi grazie ad un'integrazione successiva di dati socio-economici.
                </p>
                <p>
                    Tramite visualizzazioni mirate a spiegare il contesto, le differenze tra i distretti e le vittime colpite per ogni reato è possibile utilizzare un <strong>approccio Data-Driven</strong> che da un parte si prefigge il complesso obiettivo di incoraggiare maggiori controlli da parte della polizia nelle zone "ad alto rischio", dall'altra può diventare spunto di riflessione per tutti coloro che vogliono andare a visitare i vari quartieri di Los Angeles.
                </p>
            </div>
        </div>


        <div class="row">
            <div class="col-md-8 col-md-offset-2">
                <h2>
                    Le infografiche
                </h2>
                <h3>
                    La mappa di Los Angeles: una panoramica sulla criminalità
                </h3>

                <p>
                    Una visione complessiva e generale della città di Los Angeles e della sua criminalità è stata rappresentata grazie all'uso di una mappa interattiva. Nell'infografica è possibile osservare, oltre alle zone in cui la criminalità è maggiormente presente, anche un indicatore della diversità etnica della popolazione di ciascun distretto.
                </p>
                <p>
                    Appare evidente come LA sia caratterizzata da una forte diversità etnica, elemento che nel passato della città ha avuto un ruolo primario nella formazione di bande criminali rivali che per anni hanno portato avanti una continua guerriglia in tutta la città.
                </p>

                <p>
                    Altro elemento interessante è l'alto tasso di criminalità nel distretto di Downtown: i crimini più frequenti sono furto e rapine, assalto aggravato e atti di vandalismo; tali reati trovano un terreno fertile in quello che è, a tutti gli effetti, il centro amministrativo della città.
                </p>
                <p>
                    Infine, guardando l'andamento della criminalità da un punto di vista generale, si nota che questo ha subito una certa riduzione tra il 2010 e il 2014, tornando poi a crescere negli anni successivi.
                </p>

            </div>
        </div>
    </div>

    <!-- Prima Visualizzazione -->
    <div class="container viz">
        <div class="row">
            <div class="col-sm-12">
                <!-- Incollare qui l'embed della visualizzazione o inserire l'immagine tramite <img src="media/nomefile.jpg">
                Largezza consigliata per le immagini o per gli embed 1140px per 700px-->
                <div class='tableauPlaceholder' id='viz1536856696409' style='position: relative'><noscript><a href='#'><img alt='Mappa ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Vi&#47;Viz-v_def&#47;Mappa&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz' style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='Viz-v_def&#47;Mappa' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Vi&#47;Viz-v_def&#47;Mappa&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /></object></div>
                <script type='text/javascript'>var divElement = document.getElementById('viz1536856696409'); var vizElement = divElement.getElementsByTagName('object')[0]; vizElement.style.width = '1180px'; vizElement.style.height = '777px'; var scriptElement = document.createElement('script'); scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js'; vizElement.parentNode.insertBefore(scriptElement, vizElement);</script>
            </div>
        </div>
    </div>


    <!-- Secondo blocco di testo -->
    <div class="container">
        <div class="row">
            <div class="col-md-8 col-md-offset-2">
                <h3>La criminalità nei distretti</h3>
                <p>
                    Analizzando gli aspetti economico-culturali di ciascun distretto emerge una correlazione tra il grado di scolarizzazione (diploma di scuola superiore) e il reddito mediano: infatti, i distretti il cui tasso di  scolarizzazione è alto, presentano un reddito mediano più elevato.
                </p>
                <p>
                    Un altro elemento di interesse è la popolazione per miglio quadrato di ciascun distretto che risulta avere una positiva correlazione con le fasce di reddito: i distretti meno popolati sono quelli più ricchi, al contrario quelli con una densità di popolazione maggiore risultano essere più poveri.
                </p>
                <p>
                    Complessivamente risulta evidente che i distretti con bassa densità di popolazione a Los Angeles sono più ricchi e più sicuri rispetto a distretti altamente popolati, i quali risultano nelle fasce più basse di reddito e presentano un numero considerevole di crimini.
                </p>
            </div>
        </div>
    </div>

    <!-- Seconda Visualizzazione -->
    <div class="container viz">
        <div class="row">
            <div class="col-sm-12">
                <!-- Incollare qui l'embed della visualizzazione o inserire l'immagine tramite <img src="media/nomefile.jpg">
                Largezza consigliata per le immagini o per gli embed 1140px per 700px-->
                <div class='tableauPlaceholder' id='viz1528794323520' style='position: relative'><noscript><a href='#'><img alt='reddito ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Vi&#47;Viz-v_def&#47;reddito&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz' style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='Viz-v_def&#47;reddito' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Vi&#47;Viz-v_def&#47;reddito&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='filter' value='publish=yes' /></object></div>
                <script type='text/javascript'>var divElement = document.getElementById('viz1528794323520'); var vizElement = divElement.getElementsByTagName('object')[0]; vizElement.style.width = '100%'; vizElement.style.height = (divElement.offsetWidth * 0.75) + 'px'; var scriptElement = document.createElement('script'); scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js'; vizElement.parentNode.insertBefore(scriptElement, vizElement);</script>
            </div>
        </div>
    </div>

    <!-- Terzo blocco di testo -->
    <div class="container">
        <div class="row">
            <div class="col-md-8 col-md-offset-2">
                <h3>Il crimine in base al genere e all'etnia</h3>
                <p>
                    La diversità tra i crimini non dipende solo dal distretto in cui avvengono, ma anche dalle vittime che li subiscono. In base alla tipologia di crimine sono evidenziate, infatti, delle differenze di genere e di discendenza etnica.
                </p>
                <p>
                    La differenza di genere è soprattutto marcata per i reati di aggressione privata di natura sessuale e per crimini legati alla prostituzione: il numero di vittime di sesso femminile supera di molto il numero di vittime maschili. Altri reati, come ad esempio  il furto di identità, non presentano, invece,  grosse differenze.
                </p>
                <p>
                    La natura del crimine, come precedentemente evidenziato, è posta in relazione alla provenienza etnica della vittima; ad esempio, i reati legati alla prostituzione vedono come vittime principalmente donne di origine afroamericana, mentre l'abuso e la detenzione di droga presentano una prevalenza di donne di etnia ispanica.
                </p>

            </div>
        </div>
    </div>

    <!-- Terza Visualizzazione -->
    <div class="container viz">
        <div class="row">
            <div class="col-sm-12">
                <!-- Incollare qui l'embed della visualizzazione o inserire l'immagine tramite <img src="media/nomefile.jpg">
                Largezza consigliata per le immagini o per gli embed 1140px per 700px-->

                <div class='tableauPlaceholder' id='viz1528800273732' style='position: relative'><noscript><a href='#'><img alt='gender ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Vi&#47;Viz-v_def&#47;gender&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz' style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='Viz-v_def&#47;gender' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Vi&#47;Viz-v_def&#47;gender&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='filter' value='publish=yes' /></object></div>
                <script type='text/javascript'>var divElement = document.getElementById('viz1528800273732'); var vizElement = divElement.getElementsByTagName('object')[0]; vizElement.style.width = '1180px'; vizElement.style.height = '777px'; var scriptElement = document.createElement('script'); scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js'; vizElement.parentNode.insertBefore(scriptElement, vizElement);</script>
            </div>
        </div>
    </div>


    <!-- Quarto blocco di testo con le conlusioni-->
    <div class="container">
        <div class="row">
            <div class="col-md-8 col-md-offset-2">
                <h2>Conclusioni</h2>
                <p>
                    Le infografiche presentate cercano di cogliere le differenze tra i distretti e le vittime che sono maggiormente colpite da certe tipologie di crimini; queste differenze evidenziate possono essere utilizzate per mettere in atto azioni pubbliche al fine di migliorare la vita e il benessere sociale in ogni singolo distretto.
                </p>
                <p>
                    Nei distretti con un reddito mediano più basso si potrebbero infatti applicare opere pubbliche per innalzare il grado di scolarizzazione.
                </p>
                <p>Mentre per quanto riguarda le differenze di genere si dovrebbero applicare misure di protezione per le vittime maggiormente fragili, come le donne nei reati di aggressione privata di natura sessuale. </p>

            </div>
        </div>
    </div>

    <!-- In questa parte descrivere il processo di raccolta, pulizia e visualizzazione dei dati. Che tipo di dati avevo? Che tipo di operazioni sono state effettuate per poter visualizzare i dati. Come si leggono le visualizzazioni?-->
    <div class="howTo">
        <div class="container">
            <div class="row">
                <div class="col-md-6 col-md-offset-2">
                    <h2>Note Metodologiche</h2>

                    <!--dataset-->
                    <h3>Dataset</h3>
                    <p>
                        Il dataset originale è stato scaricato da
                        <a href="https://www.kaggle.com/cityofLA/crime-in-los-angeles" target="_blank">Kaggle</a>
                        ed in seguito è stato integrato con dati
                        <a href="http://maps.latimes.com/neighborhoods/" target="_blank">
                            socio-economici
                        </a>
                        dei distretti.
                    </p>

                    <p>
                        Il dataset presentava tipologie di crimini molto specifiche e dettagliate pertanto sono stati aggregati i crimini in macrocategorie (21), usando come riferimento gli elenchi forniti dall'FBI.
                    </p>

                    <p>
                        Un lavoro analogo è stato effettuato anche per aggregare le varie etnie delle vittime arrivando ad avere solo quattro macro gruppi: afroamericani, asiatici, caucasici e ispanici.
                    </p>

                    <p>
                        I dati utilizzati per le visualizzazioni sono stati:
                    </p>


                    <ul>
                        <li>NEIGHBORHOOD: i distretti di LA</li>
                        <li>Longitude, Latitude: le coordinate geografiche relative al luogo in cui si è verificato il crimine</li>
                        <li>ETHNIC DIVERSITY INDEX: indice rappresentate la diversità etnica per distretto</li>
                        <li>POPULATION PER SQMI: popolazione per miglio quadrato per distretto</li>
                        <li>LESS THAN HIGH SCHOOL: tasso di scolarizzazione (scuole superiori) per distretto</li>
                        <li>MEDIAN INCOME $: reddito mediano per distretto</li>
                        <li>Genere: il sesso della vittima</li>
                        <li>Crimini: i crimini specifici</li>
                        <li>Crime Code Description new: macro-categorie di crimini</li>
                        <li>Victim Descent new: etnia della vittima</li>
                        <li> Year: anni</li>
                    </ul>

                    <p>
                        Le infografiche sono state realizzate tramite il software
                        <a href="https://public.tableau.com/en-us/s/" target="_blank">
                            Tableau
                        </a>.
                    </p>

                    <!--infografica 1-->
                    <h3>
                        Infografica 1: La mappa di Los Angeles
                    </h3>
                    <p>
                        La nostra prima visualizzazione presenta una mappa i cui punti geografici, rappresentanti i distretti di Los Angeles, sono stati ricavati utilizzando le coordinate geografiche riportate nei rapporti ufficiali per ciascun distretto.
                    </p>
                    <p>
                        La dimensione dei punti indica il numero di crimini complessivamente registrato per quel distretto;
                        il colore rappresenta l'indice di diversità etnica, dove un colore più scuro indica una maggiore presenza di differenti etnie sul territorio.
                    </p>

                    <p>
                        Passando il mouse su ogni singolo punto è possibile visualizzare i dati in versione testuale: nome del distretto, il numero di crimini e l'indice di diversità etnica in percentuale.
                    </p>

                    <p>
                        Il line chart posizionato in basso a destra rappresenta l'andamento annuale del numero complessivo dei crimini.
                    </p>

                    <p>
                        Il filtro per tipologia di crimine permette di evidenziare i dati specifici per quel determinato crimine sia per quanto riguarda il numero di record sia l'andamento annuale.
                    </p>

                    <!--infografica 2-->
                    <h3>
                        Infografica 2: scolarizzazione, reddito e criminalità
                    </h3>
                    <p>
                        La seconda infografica mette in relazione, per ciascun distretto, la percentuale di scolarizzazione (asse delle ascisse) con  il reddito mediano (asse delle ordinate).
                    </p>
                    <p>
                        Il dato inerente alla scolarizzazione presentava inizialmente valori alti per indicare un minore tasso di istruzione; pertanto, in modo da ottenere un dato più intuitivo, il valore è stato invertito (un valore basso per bassa scolarizzazione e un valore alto per alta scolarizzazione).
                    </p>
                    <p>
                        Ciascun distretto viene rappresentato tramite un punto la cui dimensione è proporzionale al numero di crimini.
                        <br />
                        Il colore ci permette di dividere i distretti in tre gruppi in base alla densità di popolazione per miglio quadrato (bassa, media e alta): all'aumentare della scurezza corrisponde un distretto maggiormente popolato.
                    </p>
                    <p>
                        Al passaggio del mouse si evidenziano le informazioni testuali di cui sopra: nome del distretto, numero di crimini, popolazione per miglio quadrato, reddito mediano, scolarizzazione (scuole superiori).
                    </p>


                    <!--infografica 3-->
                    <h3>
                        Infografica 3: Il crimine in base al genere e all'etnia
                    </h3>
                    <p>
                        La terza visualizzazione presenta l'elenco completo dei crimini senza aggregazione e per ciascuno indica quante sono state le vittime di sesso femminile e quelle di sesso maschile evidenziando la disparità tra i generi.
                    </p>
                    <p>
                        Per rappresentare il sesso femminile e quello maschile è stata usata la convenzione colore rosa-azzurro; per aiutare le persone affette da problemi di daltonismo a visualizzare correttamente l'infografica, in aggiunta al colore è stato usato un elemento grafico caratterizzante (cerchio per le femmine e rombo per i maschi).
                    </p>
                    <p>
                        Al passaggio del mouse sono visibili le informazioni testuali quali il genere e il numero di crimini.
                    </p>

                    <p>
                        La parte inferiore della visualizzazione rappresenta la percentuale delle vittime in base all'etnia e al genere rispetto al crimine selezionato, infatti entrambe le visualizzazioni possono essere filtrate per macro categorie di crimini.
                    </p>

                    <p>
                        In questo caso, al passaggio del mouse è possibile leggere informazioni riguardo la percentuale di vittime che hanno subito quel crimine, il genere e la discendenza etnica.
                    </p>

                    <hr>



                    <!-- In questa parte descrivere il processo di valutazione euristica e questionario-->
                    <!--euristiche-->
                    <h2>
                        Euristiche considerate
                    </h2>
                    <p>
                        Abbiamo creato le nostre infografiche al fine di rispettare alcune euristiche principali, tra cui:
                    </p>
                    <ul>
                        <li>
                            <strong>Overview</strong>: si è cercato di creare infografiche che siano il più possibile sintetiche ed intuitive, allo scopo di facilitarne la comprensione dell'utente e velocizzarne l'uso.
                        </li>
                        <li>
                            <strong>Filter</strong>: attraverso i filtri presenti sulla destra della visualizzazione, l'utente ha la possibilità di selezionare la tipologia di crimine a cui fare riferimento.
                        </li>

                        <li>
                            <strong>Details-on-demand</strong>: selezionando un singolo elemento con un “click” è possibile visualizzare i relativi dati escludendo temporaneamente il resto.
                        </li>
                    </ul>

                    <!--questionario-->
                    <h2>
                        Valutazione della qualità: il questionario
                    </h2>
                    <p>
                        Per la valutazione della qualità delle infografiche proposte si è deciso di utilizzare un test d'utente e un questionario psicometrico. Il primo aveva come scopo principale far risolvere all'utente specifici task al fine di comprendere quanto le visualizzazioni fossero intuitive e chiare. In particolare, è stato assegnato ad un gruppo di 12 persone, tutti studenti dell'Università di Milano Bicocca. Durante l'esecuzione del test sono stati registrati i tempi e gli eventuali errori commessi.
                    </p>
                    <p>
                        Il questionario psicometrico, invece, misurava il livello di gradimento di ogni info-visualizzazione sotto i seguenti profili: bellezza, utilità, intuitività, chiarezza e valore informativo. È stato assegnato a 32 persone divise in due gruppi distinti in base al genere. La classificazione dei due gruppi ha permesso di  analizzare le eventuali differenze statistiche ed esaminare il trend delle risposte (suddividendole tra risposte positive e negative).
                    </p>

                    <!--test utente-->

                    <h3>Test Utente</h3>
                    <p>
                        Per ciascuna delle tre infografiche è stato chiesto ai 12 studenti dell'Università Bicocca di rispondere a delle domande, in particolare due per ogni visualizzazione, la cui risposta era da trovarsi tramite l'interazione con esse.
                    </p>
                    <p>
                        Per una migliore analisi dei risultati si è deciso di aggregare i tempi di esecuzione dei <em>task</em> per ogni visualizzazione e per poter effettuare un confronto più accurato, tra i risultati degli utenti che non avevano mai visto le visualizzazioni e i risultati dei componenti del gruppo che le avevano create, ogni membro del gruppo ha svolto i medesimi <em>task</em> per tre volte consecutive (interazione lenta, media, veloce) al fine di rilevare un tempo di esecuzione "ottimale". Quest'ultimo risulta come la media dei tempi di esecuzione delle tre prove svolte dai componenti del gruppo e viene considerato come <em>benchmark</em>.
                        Per quanto riguarda la prima infografica è stato creato il seguente <em>violin plot</em> che raffigura, appunto, la distribuzione dei tempi di esecuzione dei task degli utenti.
                    </p>
                    <img src="media/Times_for_plot_1.png" />
                    <p>In particolare, in verde viene rappresentata la media ed il rispettivo intervallo di confidenza del <em>benchmark</em>, mentre la media del tempo di esecuzione da parte degli utenti con il rispettivo intervallo di confidenza è rappresentata in blu.</p>

                    <p>È possibile riscontrare dal <em>violin plot</em> sopra rappresentato, una netta differenza tra le medie dei tempi di esecuzione dei due gruppi. Tale differenza viene confermata dal test <em>t di Student</em> per campioni indipendenti il quale ci fornisce un valore della statistica t pari a 3.3812 (25 gradi di libertà) con p-value 0.0024. Tale risultato definisce statisticamente significativa la differenza tra le due medie (ad un livello di confidenza del 99%).</p>
                    <div class="text-center">
                        <img src="media/formula_1.png" />
                    </div>
                    <p>Per quanto riguarda la seconda infografica si è ottenuto il seguente <em>violin plot</em>:</p>
                    <img src="media/Times_for_plot_2.png" />

                    <p>Restando valide le stesse considerazioni effettuate per il precedente plot, comparando le medie dei due gruppi si evince, anche in questo caso, una differenza. Ottenendo un valore della statistica test pari a 3.4622 con p-value 0.002 la differenza tra le due medie è da considerarsi statisticamente significativa (ad un livello di confidenza del 99%).</p>

                    <p>Quest'ultimo <em>violin plot</em> rappresenta l'analisi dei risultati della terza visualizzazione:</p>

                    <img src="media/Times_for_plot_3.png" />

                    <p>
                        Si nota subito come i tempi di esecuzione da parte degli utenti risultino nettamente superiori rispetto ai tempi ottimali. Senza sorpresa infatti la statistica test assume valore 5.6332 con p-value 0.00005, segno di una estrema significatività a livello statistico.
                    </p>

                    <p>
                        In conclusione, i tempi di esecuzione da parte degli utenti si sono rilevati, in ogni caso, maggiori rispetto al <em>benchmark</em>. In particolare, il maggior gap fra le medie si rileva nella terza visualizzazione, che risulta maggiormente complicata.
                    </p>

                    <p>Sono state analizzate anche il numero di risposte corrette e non corrette per le singole domande di ogni visualizzazione. Ogni domanda ha ottenuto il 100% di risposte corrette, eccetto quella che riguardava il tasso di scolarizzazione e il reddito mediano. Come era prevedibile il tasso di risposte scorrette è prossimo allo zero, probabilmente perché il campione analizzato è familiare alle infografiche.</p>
                    <p>Invece, i risultati ottenuti con il questionario psicometrico sono maggiormente interessanti in quanto il campione si è rivelato più propenso all'errore, in quanto meno esperto di infografiche. Per questo motivo si è deciso di visualizzare soltanto i risultati relativi al questionario psicometrico.</p>

                    <p>Considerando il tasso di errore per ogni domanda relativa alla stessa visualizzazione non risultano differenze statisticamente significative. Invece, per quanto riguarda i risultati ottenuti a livello generale, esistono delle differenze statisticamente significative, individuabili tramite gli intervalli di confidenza, tra il tasso di errore della domanda due della seconda infografica rispetto alle domande uno e due della prima infografica, e alla domanda due della terza info-visualizzazione. Possiamo concludere che tale quesito (domanda due della visualizzazione due) è risultato più complesso e quindi causa di maggior errore.</p>

                    <p>
                        Questa conclusione è ulteriormente rafforzata dal risultato ottenuto con l'user test: il campione esperto di infografiche ha ottenuto un tasso di errore maggiore di 0 solo per tale domanda.
                    </p>

                    <img src="media/ERR_questionari.png" />


                    <!--questionari psicometrici-->
                    <h3>Questionari psicometrici</h3>

                    <p>
                        In questa fase si è deciso di sottoporre ad un campione di 32 persone, diviso in egual numero tra maschi e femmine, un questionario psicometrico per valutare la qualità delle infografiche create.
                        Una volta mostrata la visualizzazione, è stato chiesto ad ogni utente di esprimere un giudizio rispetto all'utilità, all'intuitività, alla chiarezza, alla bellezza e al suo valore informativo, tramite l'assegnazione di un valore su una scala da 1 a 5.
                    </p>
                    <p>
                        Di seguito vengono forniti i risultati raccolti dal questionario, prendendo in considerazione come valori positivi i giudizi pari all'intervallo [4,5] mentre negativi i valori nell'intervallo [1,2,3].
                    </p>

                    <h4>
                        Item trend visualization
                    </h4>
                    <p>
                        Tramite un test binomiale abbiamo valutato  la polarizzazione delle risposte date per ogni item.
                    </p>
                    <p>
                        Per quanto riguarda la visualizzazione uno, la polarizzazione delle risposte è positiva e significativa per gli item utilità e valore informativo, al contrario intuitività, chiarezza e bellezza risultano non significative.
                    </p>

                    <p>Invece, la visualizzazione due ha ottenuto valori non significativi per tutti gli items, tranne per l'item valore informativo (livello di confidenza 95%).</p>
                    <p>
                        I risultati, invece, ottenuti con la terza visualizzazione sono differenti: si hanno polarizzazioni negative significative per quanto riguarda gli item: bellezza, chiarezza e intuitività. Il valore informativo, invece ha una tendenza positiva significativa, mentre la polarizzazione dell' item utilità non è risultata significativa.
                    </p>

                    <table>
                        <tr>
                            <th>Visualizzazione</th>
                            <th>Item</th>
                            <th>Polarizzazione</th>
                            <th>P-value</th>
                        </tr>
                        <tr>
                            <td>1</td>
                            <td>UTILITÁ</td>
                            <td>POSITIVA</td>
                            <td>0,01</td>
                        </tr>
                        <tr>
                            <td>1</td>
                            <td>INTUITIVITÁ</td>
                            <td>POSITIVA</td>
                            <td>0,0551</td>
                        </tr>
                        <tr>
                            <td>1</td>
                            <td>CHIAREZZA</td>
                            <td>POSITIVA</td>
                            <td>0,0551</td>
                        </tr>
                        <tr>
                            <td>1</td>
                            <td>VALORE INFORMATIVO</td>
                            <td>POSITIVA</td>
                            <td>0,0001</td>
                        </tr>
                        <tr>
                            <td>1</td>
                            <td>BELLEZZA</td>
                            <td>POSITIVA</td>
                            <td>0,0551</td>
                        </tr>
                        <tr>
                            <td>2</td>
                            <td>UTILITÁ</td>
                            <td>POSITIVA</td>
                            <td>0,0551</td>
                        </tr>
                        <tr>
                            <td>2</td>
                            <td>INTUITIVITÁ</td>
                            <td>POSITIVA</td>
                            <td>0,43</td>
                        </tr>
                        <tr>
                            <td>2</td>
                            <td>CHIAREZZA</td>
                            <td>-</td>
                            <td>0,57</td>
                        </tr>
                        <tr>
                            <td>2</td>
                            <td>VALORE INFORMATIVO</td>
                            <td>POSITIVA</td>
                            <td>0,0035</td>
                        </tr>
                        <tr>
                            <td>2</td>
                            <td>BELLEZZA</td>
                            <td>POSITIVA</td>
                            <td>0,43</td>
                        </tr>
                        <tr>
                            <td>3</td>
                            <td>UTILITÁ</td>
                            <td>POSITIVA</td>
                            <td>0,1077</td>
                        </tr>
                        <tr>
                            <td>3</td>
                            <td>INTUITIVITÁ</td>
                            <td>NEGATIVO</td>
                            <td>0,0035</td>
                        </tr>
                        <tr>
                            <td>3</td>
                            <td>CHIAREZZA</td>
                            <td>NEGATIVO</td>
                            <td>0,01</td>
                        </tr>
                        <tr>
                            <td>3</td>
                            <td>VALORE INFORMATIVO</td>
                            <td>POSITIVA</td>
                            <td>0,0035</td>
                        </tr>
                        <tr>
                            <td>3</td>
                            <td>BELLEZZA</td>
                            <td>NEGATIVO</td>
                            <td>0,0251</td>
                        </tr>
                    </table>

                    <p>Di seguito vengono presentati i grafici inerenti alla proporzione di risposte positive e negative per ogni item. Inoltre, è stato calcolato l'intervallo di confidenza tramite la seguente formula:</p>

                    <div class="text-center">
                        <img src="media/formula_2.png" />
                    </div>
                    <img src="media/viz1.png" />
                    <img src="media/viz2.png" />
                    <img src="media/viz3.png" />

                    <h4>
                        Differenza tra gruppi su item
                    </h4>
                    <p>
                        Di seguito, tramite l'utilizzo del violin plot vengono visualizzate le distribuzioni delle risposte assegnate dai maschi e dalle femmine per ogni item. Il test di Mann-Whitney, che è un test non parametrico, ci permette di indagare se sussiste una differenza tra i due gruppi rispetto agli item. L'ipotesi nulla del test è che le due popolazioni, in questo caso maschi e femmine, derivino dalla stessa popolazione. I risultati ottenuti non riportano differenze significative tra i due gruppi, eccetto per l'item utilità della terza visualizzazione, dove il p-value è uguale a  0.04, per cui si rifiuta l'ipotesi nulla ad un livello di confidenza del 95%.
                    </p>
                    <img src="media/Violin_plot_1.png" />
                    <img src="media/Violin_plot_2.png" />
                    <img src="media/Violin_plot_3.png" />

                    <h4>Item correlation</h4>
                    <p>
                        Infine, sono state analizzate le correlazioni tra gli item. Le correlazioni in ogni visualizzazione sono positive e elevate tra tutti gli items.
                    </p>

                    <img src="media/corr_1.png" />
                    <img src="media/corr_2.png" />
                    <img src="media/corr_3.png" />


                </div>



                <!-- Inserire i link di google spreadsheet con i dati al posto di #.-->
                <div class="col-md-3 col-md-offset-1 howToSide">
                    <h5>Dati utilizzati</h5>
                    <p><a href="https://www.kaggle.com/cityofLA/crime-in-los-angeles" target="_blank">Dataset originale</a></p>
                    <p><a href="data/los_angeles_completo.csv">Dataset integrato</a></p>


                    <!-- Inserire i link agli strumenti utilizzati per la gestione dei dati e per la visualizzazione-->
                    <h5 id="tools">Strumenti utilizzati</h5>
                    <p><a href="https://public.tableau.com/en-us/s/" target="_blank">Tableau </a>- Visualizzazioni progetto</p>
                    <p class="indent">
                        Python - Valutazione qualità
                        <a href="https://matplotlib.org/" target="_blank">libreria Matplotlib</a>
                        <a href="https://seaborn.pydata.org/" target="_blank">libreria Seaborn</a>
                    </p>
                    <p class="indent">
                        RStudio - Valutazione qualità
                        <a href="https://cran.r-project.org/web/packages/corrplot/index.html" target="_blank">Corrplot</a>
                    </p>
                </div>

            </div>
        </div>
    </div>
    <!-- /#page-content-wrapper -->
    <!-- Bootstrap core JavaScript
    ================================================== -->
    <!-- Placed at the end of the document so the pages load faster -->
    <script src="https://ajax.googleapis.com/ajax/libs/jquery/1.12.4/jquery.min.js"></script>
    <script>window.jQuery || document.write('<script src="../../assets/js/vendor/jquery.min.js"><\/script>')</script>
    <script src="js/bootstrap.min.js"></script>
    <!-- IE10 viewport hack for Surface/desktop Windows 8 bug -->
    <script src="js/ie10-viewport-bug-workaround.js"></script>
    <script>
        $(document).ready(function () {
            var trigger = $('.hamburger'),
                overlay = $('.overlay'),
                isClosed = false;

            trigger.click(function () {
                hamburger_cross();
            });

            function hamburger_cross() {

                if (isClosed == true) {
                    overlay.hide();
                    trigger.removeClass('is-open');
                    trigger.addClass('is-closed');
                    isClosed = false;
                } else {
                    overlay.show();
                    trigger.removeClass('is-closed');
                    trigger.addClass('is-open');
                    isClosed = true;
                }
            }

            $('[data-toggle="offcanvas"]').click(function () {
                $('#wrapper').toggleClass('toggled');
            });
        });
    </script>
</body>
</html>
