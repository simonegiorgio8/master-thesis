# Exploring the Impact of Extractive Summarization on GPT‑based Abstractive Summarization

In questo studio si è andati a esplorare l'impatto della extractive summarization su una GPT-based abstractive summarization, valutando il beneficio nel vincolare gli abstract generati dal summarizer GPT-based con delle sentences estratte utilizzando MemSum e KeyBERT, due modelli per la extractive summarization (il secondo un keyword extractor adattato a tale scopo), utilizzandoli in modalità singola ed in modalità ensemble. 

Oggetto dello studio sono stati 9 Datasets provenienti da campi eterogenei in modo da valutare l’adattabilità dei modelli a diversi domini applicativi (articoli scientifici, atti legali, news, letteratura etc.) 

Le prestazioni complessive sono state valutate in diversi modi: utilizzando le metriche ROUGE ed utilizzando un sistema di ratings che chiede a GPT di votare da 1 a 5 i summary in input secondo diversi criteri (informatività, qualità, coerenza, attribuibilità, overall preference).

Successivamente i risultati ottenuti sono stati confrontati con una summarization di tipo puramente astrattivo, facendo emergere che, sotto particolari condizioni, un'assistenza estrattiva permette di ottenere summary più compatti mantenendo una specificità e dettaglio tecnico maggiore.

[Presentazione in PDF](./Presentazione.pdf)
