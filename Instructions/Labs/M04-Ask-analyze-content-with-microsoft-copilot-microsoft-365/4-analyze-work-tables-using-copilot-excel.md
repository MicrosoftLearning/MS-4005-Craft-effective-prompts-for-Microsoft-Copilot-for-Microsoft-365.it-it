# Analizzare e servirsi delle tabelle usando Microsoft 365 Copilot in Excel

Se non si ha la certezza di come scrivere una formula per una nuova colonna, Microsoft 365 Copilot può aggiungere rapidamente nuove colonne con formule basate sui dati.

1. Con i dati formattati come tabella, selezionare il pulsante **Copilot** sulla barra multifunzione.

1. Selezionare **Aggiungi colonne della formula** o **Mostra suggerimenti per le colonne della formula**. È anche possibile descrivere le colonne da aggiungere digitandole con parole proprie.

1. Copilot fornisce suggerimenti sulle formule con una spiegazione sul funzionamento di ogni formula. Visualizzare la spiegazione selezionando **Spiega formula**.

1. Selezionare Inserisci colonna per aggiungere la colonna della formula alla tabella.

> [!IMPORTANT]
> Come con qualsiasi contenuto generato dall'intelligenza artificiale, è importante rivedere, modificare e verificare qualsiasi contenuto creato da Copilot.

## Iniziamo a creare

Innanzitutto, scaricare **_[Fabrikam Q1 marketing campaigns.xlsx](https://go.microsoft.com/fwlink/?linkid=2269124)_** e salvare il file nella **cartella di OneDrive** (se non è ancora stato fatto).

Aprire il foglio di calcolo in Excel e il riquadro **Copilot** selezionando la relativa icona nella scheda **Home** della barra multifunzione. Immettere le richieste riportate di seguito e seguire la procedura.

> [!NOTE]
> Richiesta iniziale:
>
> _Suggerire una colonna della formula._

In questa semplice richiesta si inizia con l'**obiettivo** di base: _creare una nuova colonna con una formula._ Tuttavia, non sono disponibili dettagli sufficienti per determinare cosa dovrebbe calcolare la formula.  

| Elemento | Esempio |
| :------ | :------- |
| **Richiesta di base:** iniziare con un **obiettivo** | **_Suggerire una colonna della formula._** |
| **Buona richiesta:** aggiungere **contesto** | L'aggiunta di **contesto** consente a Copilot di comprendere cosa deve calcolare la formula. _"...in modo che la colonna J determini il rapporto di engagement di ogni campagna"._ |
| **Richiesta migliore:** specificare le **origini** | L'**origine** di questa richiesta è la colonna specifica necessaria per il calcolo. _"...deve usare i valori di "Utenti con engagement" e "Utenti di destinazione totali"._ |
| **Richiesta ottimale:** impostare **aspettative** chiare | L'aggiunta di **aspettative** consente a Copilot di strutturare correttamente la formula. _"Assicurarsi che la formula divida gli "Utenti con engagement" dagli "Utenti di destinazione totali" e formatti il risultato come percentuale"._ |

> [!NOTE]  
> **Richiesta creata**:  
>
> _Suggerire una formula in modo che la colonna J calcoli il rapporto di engagement di ogni campagna. Usare i valori di "Utenti con engagement" e "Utenti di destinazione totali". Assicurarsi che la formula divida gli "Utenti con engagement" dagli "Utenti di destinazione totali" e formatti il risultato come percentuale._  

![Screenshot dei risultati della richiesta creata usando Copilot in Excel.](../media/ask_copilot-explain-formula-results-excel.png)

Copilot dispone di tutte le informazioni necessarie per fornire una risposta efficace grazie all'**obiettivo**, al **contesto**, all'**origine** e alle **aspettative** di questa richiesta.

## Esplora altro

Usare questi prompt come punto di partenza. Copiarli e modificarli in base alle proprie esigenze.

- Calcolare il costo totale per prodotto in una nuova colonna.

- Aggiungere una colonna che calcola il profitto totale per ogni campagna di marketing nel 2022.

- Aggiungere una colonna che calcola il numero di giorni dopo l'evento di lancio del prodotto.

Per altre informazioni, vedere [Generare le colonne delle formule con Copilot in Excel](https://support.microsoft.com/office/generate-formula-columns-with-copilot-in-excel-d866d926-9791-4e5f-be2a-c6dd9e587a47).
