### Creazione Prodotti

Per la creazione di un nuovo prodotto è sempre consigliabile attingere ad esempi già esistenti all'interno del Database: in questo modo è possibile ereditare automaticamente la Categoria del prodotto (e conseguentemente intuirne il prefisso da inserire nel Riferimento interno), la tipologia (prodotto stoccabile, servizio, etc), il percorso di magazzino (produzione o acquisto) e la sua finalità rispetto al cliente/fornitore (può essere venduto, può essere acquistato).

È importante inoltre - nel caso ad esempio di componenti acquistati da uno o più Fornitori - inserire la provenienza del prodotto nell'apposita scheda acquisti, nel seguente formato:

**Nome Fornitore - Nome prodotto Fornitore - Codice Prodotto Fornitore - Quantità - Prezzo**

> Nome Fornitore: Nome dell'azienda presso cui andremo ad acquistare il prodotto
>
> Nome prodotto Fornitore: Nome utilizzato dal Fornitore per chiamare uno specifico prodotto
>
> Codice Prodotto Fornitore: Codice di riferimento con cui il Fornitore codifica un prodotto
>
> Quantità: Numero di prodotti da acquistare in relazione al prezzo/lotto minimo specifico di un Fornitore
>
> Prezzo: Prezzo per quantità di uno specifico prodotto

In questo modo - andando ad inserire un nostro **Riferimento Interno** in un nuovo preventivo - avremo da subito la possibilità di sapere **da chi è fornito** un particolare prodotto, **quanto ci costerà** in relazione alla **quantità** richiesta e **quando** verrà ricevuto il materiale.