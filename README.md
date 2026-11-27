# Organitza-un-viatge-amb-google

**Pràctica P5.1 - Organització d'un viatge amb Google**

# PRÀCTICA: ORGANITZA UN VIATGE AMB GOOGLE

## FASE 1: EL CORREU

### 1. Eines de Google

| Eina | Propòsit | Públic destinatari |
|---|---|---|
| Gmail | Enviar, rebre i organitzar correus electrònics. | Estudiants i professionals. |
| Google Calendar | Organitzar esdeveniments i recordatoris. | Estudiants i treballadors. |
| Google Maps | Consultar mapes i planificar rutes. | Viatgers i conductors. |
| Google Drive | Emmagatzemar i compartir fitxers. | Estudiants i empreses. |
| Google Sheets | Crear fulls de càlcul i pressupostos. | Estudiants i professionals. |
| Google Docs | Crear i editar documents de text. | Estudiants i treballadors. |

### 2. Diferència entre IMAP i POP3

IMAP permet consultar els correus des de diferents dispositius mantenint-los sincronitzats amb el servidor.

POP3 descarrega els correus al dispositiu i, segons la configuració, pot eliminar-los del servidor.

IMAP és més recomanable quan utilitzem diversos dispositius, mentre que POP3 serveix principalment per descarregar els missatges.

### 3. Etiqueta de Gmail

S'ha de crear una etiqueta anomenada `institut` i assignar-li el color verd.

També s'ha de comprovar que existeix l'etiqueta `promocions`.

### 4. Filtres de Gmail

| Filtre | Condició | Acció |
|---|---|---|
| 1 | El correu conté la paraula `puig`. | Aplicar l'etiqueta `institut`. |
| 2 | El correu conté la paraula `publicitat`. | Aplicar l'etiqueta `promocions` i ometre la safata d'entrada. |
| 3 | El remitent és un dels dos professors. | Marcar sempre com a important. |

### 5. Resposta automàtica

S'ha d'activar la resposta automàtica de vacances amb el missatge següent:

`Estic de vacances!`

### 6. Pregunta sobre el filtre de publicitat

Si no activem l'opció «Omet la safata d'entrada», els correus amb la paraula `publicitat` continuaran apareixent a la safata d'entrada, encara que tinguin aplicada l'etiqueta `promocions`.

Per tant, és important activar aquesta opció per mantenir la safata d'entrada organitzada.

---

## FASE 2: COMPROVAR L'ACCÉS AL CORREU

### 1. Configuració IMAP, POP3 i SMTP

| Servei | Servidor | Port | Xifratge |
|---|---|---|---|
| Entrada IMAP | imap.gmail.com | 993 | SSL/TLS |
| Entrada POP3 | pop.gmail.com | 995 | SSL/TLS |
| Sortida SMTP | smtp.gmail.com | 465 o 587 | SSL/TLS o STARTTLS |

L'usuari és l'adreça completa del compte de correu.

**Estat de l'accés IMAP:** [PENDENT DE COMPROVAR]

### 2. Prova entre dos comptes

S'han d'obrir dues sessions de Gmail alhora, una amb el compte del centre i una altra amb el compte d'un company.

S'ha d'enviar un missatge amb la paraula `puig` a l'assumpte i comprovar que arriba al segon compte amb l'etiqueta `institut`.

Després s'ha de respondre el missatge i comprovar que la resposta torna al primer compte.

### 3. Comprovació de les capçaleres

A l'original del missatge s'han de comprovar els tres protocols següents:

- **SPF:** comprova que el servidor que envia el correu està autoritzat pel domini.
- **DKIM:** comprova l'autenticitat i la integritat del missatge mitjançant una signatura digital.
- **DMARC:** estableix les polítiques per als missatges que no superen les comprovacions SPF o DKIM.

També s'han de localitzar les línies `Received` per identificar els servidors pels quals ha passat el missatge.

**Resultats de la comprovació:**

| Protocol | Resultat |
|---|---|
| SPF | [PENDENT DE COMPROVAR] |
| DKIM | [PENDENT DE COMPROVAR] |
| DMARC | [PENDENT DE COMPROVAR] |

### 4. Llista de proves del correu

| Núm. | Prova | Resultat |
|---|---|---|
| 1 | Crear l'etiqueta institut. | Pendent |
| 2 | Assignar el color verd a l'etiqueta. | Pendent |
| 3 | Comprovar el filtre de la paraula puig. | Pendent |
| 4 | Comprovar el filtre de publicitat. | Pendent |
| 5 | Comprovar que publicitat no apareix a la safata d'entrada. | Pendent |
| 6 | Comprovar el filtre dels dos professors. | Pendent |
| 7 | Comprovar que els correus dels professors són importants. | Pendent |
| 8 | Comprovar la resposta automàtica de vacances. | Pendent |
| 9 | Enviar un correu entre dos comptes i comprovar-ne la recepció. | Pendent |
| 10 | Respondre el correu i comprovar SPF, DKIM i DMARC. | Pendent |

---

## FASE 3: EL VIATGE

### 1. Organització de la ruta amb Google Maps

El país escollit és Itàlia.

El viatge tindrà una durada de set dies i inclourà les ciutats de Roma, Florència i Venècia.

| Dia | Ciutat | Activitats |
|---|---|---|
| 1 | Roma | Arribada des de Barcelona i visita al centre històric. |
| 2 | Roma | Visita al Colosseu i al Fòrum Romà. |
| 3 | Roma | Visita al Vaticà. |
| 4 | Florència | Trasllat des de Roma i visita al centre històric. |
| 5 | Florència | Visita a museus i monuments. |
| 6 | Venècia | Trasllat des de Florència i visita als canals. |
| 7 | Venècia | Última visita i tornada a Barcelona. |

La ruta es farà amb transport adequat entre les ciutats i inclourà l'anada i la tornada a Barcelona.

**Enllaç de Google Maps:**

[PENDENT D'AFEGIR L'ENLLAÇ DE LA RUTA]

### 2. Pressupost amb Google Sheets

El pressupost màxim disponible és de 1.500 €.

El full de càlcul ha d'incloure les despeses següents:

| Concepte | Import |
|---|---:|
| Transport | Pendent |
| Allotjament | Pendent |
| Menjar | Pendent |
| TOTAL | Pendent |

El total s'ha de calcular amb una fórmula de suma.

També s'ha d'utilitzar la funció `IF` per comprovar si el pressupost és suficient.

**Fórmula IF:**

`=IF(B5<=1500; "Dins del pressupost"; "T'has passat")`

La funció IF té tres parts:

1. Una condició que s'ha de comprovar.
2. El resultat si la condició és certa.
3. El resultat si la condició és falsa.

En aquest cas, comprova si les despeses són inferiors o iguals a 1.500 €.

- Si no superen els 1.500 €, mostra «Dins del pressupost».
- Si superen els 1.500 €, mostra «T'has passat».

### 3. Compartició del full de càlcul

S'ha de compartir el full de càlcul amb el professorat amb el permís de visualització.

**Enllaç de Google Sheets:**

[PENDENT D'AFEGIR L'ENLLAÇ DEL FULL DE CÀLCUL]

### 4. Creació del calendari

S'ha de crear un calendari a Google Calendar amb el nom:

`CALENDARI_NOM_COGNOMS`

El calendari ha de tenir una data d'inici i una data de finalització i ha d'incloure un esdeveniment per cada dia del viatge.

| Dia | Esdeveniment | Lloc |
|---|---|---|
| 1 | Arribada i visita turística. | Roma |
| 2 | Visita al Colosseu. | Roma |
| 3 | Visita al Vaticà. | Roma |
| 4 | Trasllat i visita turística. | Florència |
| 5 | Visita a museus i monuments. | Florència |
| 6 | Trasllat i visita als canals. | Venècia |
| 7 | Tornada a Barcelona. | Venècia |

Cada esdeveniment ha de tenir el lloc i una descripció de les activitats.

### 5. Prestacions de Google Calendar

S'han de demostrar les prestacions següents:

- Crear un esdeveniment repetit amb una data de finalització.
- Convidar un company a un esdeveniment i comprovar que respon.
- Crear un recordatori i comprovar-ne el funcionament.
- Crear una llista de tasques amb les reserves i les dates límit.
- Compartir el calendari amb un company perquè pugui veure tots els detalls dels esdeveniments.

---

## FASE 4: PERMISOS I PROVES

### 1. Comprovació dels permisos

S'ha de comprovar qui té accés al full de càlcul i al calendari.

Els permisos han de ser:

- Professorat: veure el full de càlcul.
- Company: veure tots els detalls dels esdeveniments del calendari.

També s'han de retirar els permisos que no siguin necessaris.

### 2. Verificació en dues passes

S'ha de comprovar que la verificació en dues passes està activada al compte de Google.

Aquesta funció afegeix una capa extra de seguretat al compte.

### 3. Llista de proves del calendari

| Núm. | Prova | Resultat |
|---|---|---|
| 1 | Comprovar que el calendari està creat. | Pendent |
| 2 | Comprovar que el nom del calendari és correcte. | Pendent |
| 3 | Comprovar la data d'inici i de finalització. | Pendent |
| 4 | Comprovar que hi ha un esdeveniment per cada dia. | Pendent |
| 5 | Comprovar que els esdeveniments tenen lloc i descripció. | Pendent |
| 6 | Comprovar que l'esdeveniment repetit té una data de finalització. | Pendent |
| 7 | Comprovar que el convidat ha respost. | Pendent |
| 8 | Comprovar que el recordatori funciona. | Pendent |
| 9 | Comprovar que les tasques tenen dates límit. | Pendent |
| 10 | Comprovar els permisos del company i l'accés al calendari. | Pendent |

---

## COMPARTICIÓ I PRIVACITAT

### Diferència entre compartir amb un enllaç i compartir amb persones concretes

Compartir amb qualsevol persona que tingui l'enllaç permet que qualsevol usuari que disposi de l'enllaç pugui accedir al document segons els permisos establerts.

Compartir amb persones concretes limita l'accés als usuaris que han estat autoritzats expressament.

He escollit compartir amb persones concretes perquè ofereix més privacitat i control sobre qui pot consultar la informació.

---

## CAPTURES DE PANTALLA

Totes les captures han de mostrar l'escriptori complet, sense retallar.

### Fase 1: El correu

[PENDENT D'AFEGIR LES CAPTURES DE GMAIL]

### Fase 2: Comprovar l'accés

[PENDENT D'AFEGIR LES CAPTURES DE IMAP I LES PROVES DEL CORREU]

### Fase 3: El viatge

[PENDENT D'AFEGIR LES CAPTURES DE GOOGLE MAPS, SHEETS I CALENDAR]

### Fase 4: Permisos i proves

[PENDENT D'AFEGIR LES CAPTURES DELS PERMISOS I LES COMPROVACIONS]

---

## CONCLUSIÓ

Aquesta pràctica m'ha permès aprendre a utilitzar diferents eines de Google per organitzar un viatge de set dies.

He après a configurar Gmail, crear etiquetes i filtres, comprovar l'accés al correu electrònic, organitzar un calendari compartit, planificar una ruta amb Google Maps i calcular un pressupost amb Google Sheets.

També he après la importància de gestionar correctament els permisos i protegir la informació personal.

Aquestes eines permeten organitzar un viatge de manera més eficient, ordenada i segura.
