# ABDU Traslochi

Sito animato per traslochi e sgomberi a Bellinzona.

## Versione aggiornata

- Italiano, spagnolo, francese, tedesco e inglese.
- Selettore lingua accessibile in alto a destra, con preferenza memorizzata nel browser.
- Due scene animate dallo scroll: sgombero e trasloco.
- Apertura compatta, con la fascia vuota sotto l’immagine rimossa.
- Chiamata diretta e richiesta sopralluogo via email.
- Layout per desktop e telefono; riduzione del movimento rispettata.

Questa è la versione autonoma approvata nell’anteprima locale. Tutti gli asset necessari sono inclusi nel repository.

## Avvio locale

Dalla cartella del repository:

    python3 -m http.server 4173 --bind 127.0.0.1

Apri http://127.0.0.1:4173. Non servono installazioni di pacchetti o chiavi API.

## File

- index.html: pagina iniziale e metadati.
- site.js: interfaccia, traduzioni, selettore, modulo email e animazioni.
- style.css: stile e impaginazione.
- assets/: immagini, filmati e poster desktop/mobile.
- fonts/: font locali.

Le traduzioni si trovano nell’oggetto translations all’inizio di site.js. I link con ?lang=it, ?lang=es, ?lang=fr, ?lang=de o ?lang=en aprono la lingua indicata.

Puoi pubblicare questi file su un hosting statico, senza compilazione. I percorsi relativi consentono di servire il sito anche da una sottocartella.

## Contatti

ABDU Traslochi  
Via delle Vigne 6, Bellinzona, Svizzera  
076 483 75 71  
trasportoabdu23@gmail.com

Il modulo prepara un messaggio nell’app email del visitatore. L’invio viene confermato dal visitatore e la data del sopralluogo si concorda direttamente con Abdu.

## Verifiche

Le cinque lingue e il selettore sono stati verificati nell’anteprima locale. Il layout compatto è stato verificato a 1250, 1280 e 1440 pixel senza scorrimento orizzontale.
