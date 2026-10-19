# Letterlab — lesreeks

Alle oefeningen van één les in de juiste volgorde, in één link. De
lesgever opent in de les die ene link en klikt van stap naar stap. Bij
elke stap staat een tip (lampje), zodat geen belangrijke stap uit het
stappenplan vergeten wordt.

Een stap is een link naar een Letterlab-tool, een Genially, een
YouTube-video of een andere webpagina. Een stap zonder link toont de tip
groot op het scherm, bijvoorbeeld voor een klasgesprek.

## Een lesreeks maken

Open `ligolimino.github.io/les/`.

1. **Snel een les maken**: kies een paragraaf (bv. *A 2.1 raam*). Het
   kernwoord, de nieuwe klank en alle gekende klanken worden vanzelf
   ingevuld. Plak eventueel de link van de Genially. Kies **Reeks
   klaarzetten**.
2. De tool zet een reeks volgens het stappenplan klaar: kernwoord, hoor je
   hetzelfde, analyse, hoor je de klank, waar hoor je de klank, kort of
   lang, letters flitsen, hakken en plakken, klik-klak, leesrijtjes en
   dictee. Woorden voor de luisteroefeningen en het dictee komen eerst
   uit een lijst met eenvoudige, frequente woorden (`COMMON_WORDS` in het
   script, vrij aan te vullen).
3. Controleer en pas aan: namen, links en tips. Stappen verschuiven met
   de pijltjes, verwijderen met ✕. Links uit de createpagina mag je
   gewoon plakken.
4. Kopieer de link of de Genially-code.

Wat je maakt, wordt in deze browser bewaard. Een bestaande lesreeks
aanpassen: plak de link onderaan en kies **Laden**.

## De link

| In de link | Betekenis |
|---|---|
| `titel=A 2.1 raam` | Titel bovenaan. |
| `n1=Kernwoord` | Naam van stap 1 (tot 40 stappen: n1, n2, n3 ...). |
| `l1=hakstrook/?woord=raam` | Link van stap 1. Zonder `https://` is het een Letterlab-tool op ligolimino.github.io. |
| `t1=...` | Tip voor de lesgever bij stap 1. |
| `tips=open` | De tips staan meteen open. |

## Bediening

| Knop | Toets | Wat |
|---|---|---|
| bolletjes bovenaan | | rechtstreeks naar een stap (groen = al getoond) |
| pijlen onderaan | PageDown/PageUp, Alt + pijl | volgende of vorige stap |
| lampje | T | tip voor de lesgever tonen of verbergen |
| pijl in een kader | | de stap apart openen in een nieuw tabblad |
| herladen | | de stap opnieuw beginnen |
| volledig scherm | F | |

Een stap blijft staan zoals hij was als je terugkeert. Toetsen werken als
de lesreeks zelf de focus heeft. Na een klik in een oefening gelden de
toetsen van die oefening.

## Paragrafen

De lijst met paragrafen staat in het script bij `PARAGRAPHS`: de
kapstokwoorden van TaalCompleet *Leer lezen en schrijven* in leervolgorde,
met de nieuwe klank. Paragrafen met clusters (Alfa B) en
herhalingsparagrafen stel je zelf samen.

## Publiceren (eenmalig)

1. Maak bij **ligolimino** een openbare repository `les`.
2. Kies **uploading an existing file** en sleep de **inhoud** van deze map
   erin (niet de map zelf). Kies **Commit changes**.
3. **Settings → Pages**: branch `main`, map `/ (root)`, **Save**.
4. Na enkele minuten: `https://ligolimino.github.io/les/`.

Open je die link zonder iets erachter, dan zie je een uitlegpagina met een
formulier om zelf een link te maken.

## Zelfstandig en onderhoudsvrij

- Alleen gewone bestanden: geen installatie, geen bouwstap, geen databank.
- Het lettertype Andika staat in de repository zelf.
- De volledige oefening staat in de link. Een link blijft werken zolang de
  repository online staat.
- In Genially is de achtergrond doorzichtig, zodat de dia zichtbaar blijft.

## Na een wijziging

Telefoons kunnen een oude versie bewaren. Wacht even of herlaad de pagina.

## Licentie lettertype

Andika valt onder de SIL Open Font License, zie
`assets/fonts/OFL-LICENSE.txt`.
