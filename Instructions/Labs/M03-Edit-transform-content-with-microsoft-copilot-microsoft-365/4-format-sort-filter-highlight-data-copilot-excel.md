# Formattare, ordinare, filtrare ed evidenziare i dati usando Microsoft 365 Copilot in Excel

Con Microsoft 365 Copilot in Excel, è facile evidenziare, ordinare e filtrare le tabelle per richiamare rapidamente l'attenzione sugli aspetti importanti. Con una sola tabella in Excel, Copilot eseguirà senza problemi le seguenti operazioni:

- Ordinamento e filtro dei dati.

- Applicazione della formattazione condizionale semplice.

Per iniziare, formattare i dati in un [formato supportato](https://support.microsoft.com/topic/format-data-for-copilot-in-excel-1604c8eb-57f1-4db1-8363-d53336228c65) e selezionare il pulsante **Copilot** sulla barra multifunzione. Indicare a Copilot come modificare la tabella per visualizzare meglio parti dei dati.

Nell'esempio seguente, si parte da un prompt di base a cui vengono progressivamente aggiunti ulteriori elementi. Seguire l'esempio usando i propri dati.

## Iniziamo a creare

Innanzitutto, scaricare **_[Fabrikam Q1 marketing campaigns.xlsx](https://go.microsoft.com/fwlink/?linkid=2269124)_** e salvare il file nella **cartella di OneDrive** (se non è ancora stato fatto).

Aprire il foglio di calcolo in Excel e il riquadro **Copilot** selezionando la relativa icona nella scheda **Home** della barra multifunzione. Immettere le richieste riportate di seguito e seguire la procedura.

> [!NOTE]
> Richiesta iniziale:
>
> _Ordina questa tabella._

Con questa semplice richiesta si inizia con l'**Obiettivo** di base, ovvero _ordinare e filtrare una tabella di Excel_. Non vi sono tuttavia indicazioni sul tipo di ordinamento da applicare ai dati e su quale campo basare il filtro.

| Elemento | Esempio |
| :------ | :------- |
| **Richiesta di base:** iniziare con un **obiettivo** | **_Ordina questa tabella..._** |
| **Buona richiesta:** aggiungere **contesto** | Aggiungendo un **Contesto**, Copilot potrà capire meglio a cosa fanno riferimento le diapositive e su quale argomento concentrarsi. _"...per cercare il venditore con il maggiore impatto."_ |
| **Richiesta migliore:** specificare le **origini** | Si suppone che l'**Origine** di questa richiesta sia la tabella con cui si sta lavorando in Excel. _"...questa tabella [Tabella1]..."_ |
| **Richiesta ottimale:** impostare **aspettative** chiare | Infine, aggiungendo **Aspettative** si può aiutare Copilot a capire come ordinare, filtrare e presentare la tabella. _"ed evidenziare i primi e gli ultimi proprietari della campagna in base ai ricavi netti"._ |

> [!NOTE]
> **Richiesta creata**:
>
> _Ordinare questa tabella [Tabella1] per cercare il venditore con il maggiore impatto ed evidenziare i primi e gli ultimi proprietari della campagna in base ai ricavi netti_

Questa richiesta richiede l'esecuzione di più passaggi, una tecnica di richiesta denominata **concatenamento** in cui si chiede a Copilot di eseguire comandi back-to-back sequenziali per raggiungere un singolo obiettivo.

**Prima richiesta**:

```text
Sort this table [Table1] to look for the most impactful salesperson.
```

**Seconda richiesta**:

```text
highlight the top and bottom campaign owners based off of net revenue
```

Copilot dispone di tutte le informazioni necessarie per fornire una risposta efficace grazie all'**obiettivo**, al **contesto**, all'**origine** e alle **aspettative** di questa richiesta.

## Esplora altro

Provare queste richieste semplici per evidenziare, ordinare e filtrare i dati e aggiungere altri elementi per migliorare i risultati:

- Mettere in grassetto i primi 10 valori nella colonna Vendite.

- Evidenziare i valori più alti in Unità vendute.

- Ordinare il tasso di engagement dal più piccolo al più grande.  

- Filtrare i prodotti che scadono la prossima settimana.

> [!IMPORTANT]
> Copilot lavorerà solo sui file archiviati in OneDrive o SharePoint. Se non è possibile selezionare il pulsante Copilot nella barra multifunzione, provare prima a salvare il file nel cloud. Per altre informazioni, consultare [Evidenziare, ordinare e filtrare i dati con Copilot in Excel](https://support.microsoft.com/office/highlight-sort-and-filter-your-data-with-copilot-in-excel-05302e3f-de42-4475-b235-be9cb3d4e936).
