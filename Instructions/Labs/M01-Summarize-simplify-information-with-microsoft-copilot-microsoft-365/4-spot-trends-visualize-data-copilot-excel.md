# Individuare le tendenze e visualizzare i dati con Copilot in Excel

Microsoft 365 Copilot in Excel consente di eseguire altre operazioni con i dati nelle tabelle di Excel generando suggerimenti per le colonne delle formule, visualizzando informazioni dettagliate nei grafici e nelle tabelle pivot ed evidenziando parti interessanti dei dati.

In Excel selezionare **Copilot**  sulla barra multifunzione per aprire il riquadro della chat.

![Screenshot dell'icona di Copilot nella barra multifunzione di Excel.](../media/summarize_copilot-ribbon-excel.png)

Per usare Copilot in Excel, i dati devono essere formattati in uno dei modi seguenti:

- Come tabella di Excel
- Come intervallo di supporto

È possibile creare una tabella o convertire un intervallo di celle in una tabella se si dispone di un intervallo di dati. Per farlo, seguire questa procedura:

1. Selezionare la cella o l'intervallo nei dati.

1. Selezionare **Home > Formatta come tabella**.

1. Nella finestra di dialogo  **Formatta come tabella**  selezionare la casella di controllo accanto a  **Tabella personale con intestazioni**  se si desidera che la prima riga dell'intervallo sia la riga di intestazione.

1. Selezionare **OK**.

Se si preferisce mantenere i dati in un intervallo e non convertirli in una tabella, sarà necessario soddisfare tutti i requisiti seguenti:

- Solo una riga di intestazione
- Le intestazioni sono solo sulle colonne, non sulle righe
- Le intestazioni sono univoche; non sono presenti intestazioni duplicate
- Non sono presenti intestazioni vuote
- I dati sono formattati in modo coerente
- Non sono presenti subtotali
- Non sono presenti righe o colonne vuote
- Non sono presenti celle unite

Nell'esempio seguente, iniziamo con una richiesta di base di analisi di una tabella, poi vengono aggiunti progressivamente elementi per rendere il prompt più efficace.

![Screenshot del pannello Copilot in Excel alla prima apertura.](../media/summarize_copilot-pane-excel.png)

## Iniziamo a creare

Iniziare scaricando il file **_[Contoso Chai Tea market trends 2023.xlsx](https://go.microsoft.com/fwlink/?linkid=2268822)_** e salvandolo nella propria **cartella OneDrive** se non è ancora stato fatto.

Aprire il foglio di calcolo in Excel e il riquadro **Copilot** selezionando la relativa icona nella scheda **Home** della barra multifunzione. Immettere le richieste riportate di seguito e seguire la procedura.

> [!NOTE]
> Richiesta iniziale:
>
> _Analizzare questa tabella in Excel._

In questa semplice richiesta si parte dall'**obiettivo** di base: _analizzare una tabella Excel._ Tuttavia, non sono disponibili informazioni sul motivo per cui la tabella deve essere riepilogata o per che cosa è necessario il riepilogo.

| Elemento | Esempio |
| :------ | :------- |
| **Richiesta di base:** iniziare con un **obiettivo** | **Analizzare questa tabella in Excel.** |
| **Buona richiesta:** aggiungere **contesto** | L'aggiunta di **contesto** consente a Copilot di comprendere lo scopo dell'analisi e di regolare di conseguenza la risposta. _"Stiamo cercando i prodotti più venduti da maggio ad agosto per le vendite di tè chai artigianale o di tè chai preconfezionato."_ |
| **Richiesta migliore:** specificare le **origini** | L'aggiunta di **origini** può aiutare Copilot a restringere l'ambito indicandogli di usare informazioni o intervalli specifici. _"... da maggio ad agosto per le vendite di tè chai artigianale o di tè chai preconfezionato..."_ |
| **Richiesta ottimale:** impostare **aspettative** chiare | Infine, l'aggiunta di **Aspettative** può aiutare Copilot a comprendere come formattare il riepilogo e quale livello di dettaglio è necessario. _"Riepiloga il prodotto più venduto per ogni mese."_ |

> [!NOTE]
> **Richiesta creata**:
>
> _Analizza questa tabella in Excel. Stiamo cercando i prodotti più venduti da maggio ad agosto per le vendite di tè chai artigianale o di tè chai preconfezionato. Riepiloga il prodotto più venduto per ogni mese._

Questo prompt fornisce a Copilot tutte le informazioni necessarie per elaborare una buona risposta, compresi gli elementi di **Obiettivo**, **Contesto**, **Origine** e **Aspettative**.

## Esplora altro

Provare la richiesta finale creata e altre con la propria tabella di Excel. Ecco alcuni suggerimenti per altre richieste che è possibile provare. Copiarle e aggiungere **contesto**, **origini** e **aspettative**.  

- Tracciare le vendite per categoria nel tempo.

- Mostrare le vendite totali per ogni prodotto.

- Mostrare il totale delle vendite pubblicitarie per ogni area nell'anno precedente.

> [!IMPORTANT]
> Questa funzionalità è disponibile per i clienti con una licenza di Microsoft 365 Copilot o Copilot Pro. Per altre informazioni sulle tabelle di Excel e su come crearle, consultare [Creare una tabella in Excel](https://support.microsoft.com/office/bf0ce08b-d012-42ec-8ecf-a2259c9faf3f).
