
# Modellazione della diffusione del SARS-CoV-2 e delle strategie di contenimento in Italia

Questo progetto modella la diffusione del **COVID-19 in Italia durante la Fase 1 della pandemia (marzo-maggio 2020)** utilizzando un **modello SEIR implementato in GLEAMviz**, con l'obiettivo di:
- Valutare l’efficacia delle misure restrittive introdotte dal governo;
- Confrontare simulazioni con dati reali;
- Simulare uno scenario alternativo senza restrizioni per quantificare l'impatto delle misure.

Il lavoro nasce all'interno del corso *Sistemi Complessi: Modelli e Simulazione* presso l’Università di Milano-Bicocca.

Simone Lesinigo, [@github](https://github.com/Leso246)
Andrea Broccoletti, [@github](https://github.com/BrockDeveloper/)

## Simulazioni effettuate

### Scenario 1: Covid-19 con restrizioni
- Periodo: 4 marzo 2020 - 4 maggio 2020
- Misure restrittive graduali: lockdown, riduzione mobilità
- Riduzione traffico aereo e pendolarismo.

### Scenario 2: Covid-19 senza restrizioni
- Periodo: 4 marzo 2020 - 4 maggio 2020
- Nessuna restrizione: tasso di contagio costante e mobilità invariata

---

## Risultati

### Con restrizioni:
- Picco simulato ~2800-3000 casi al 24 marzo.
- Riduzione a ~1700-1800 casi al 4 maggio.
- Andamento coerente con dati reali nella fase discendente, pur sottostimando il picco iniziale.

### Senza restrizioni:
- Crescita esponenziale senza contenimento.
- Picchi >150.000 casi giornalieri.
- Conferma l'efficacia delle restrizioni nel contenere la diffusione.
- 
## Gleamviz
Per ogni ulteriore specifica sul simulatore utilizzato, si rimanda al [sito ufficiale](https://www.gleamviz.org/index.html) dello stesso.

[The GLEAMviz computational tool, a publicly available software to explore realistic epidemic spreading scenarios at the global scale](http://www.biomedcentral.com/1471-2334/11/37).  
W. Van den Broeck, C. Gioannini, B. Gonçalves, M. Quaggiotto, V. Colizza, A. Vespignani. _BMC Infectious Diseases_ **11**, 37 (2011).

[Seasonal transmission potential and activity peaks of the new influenza A(H1N1): a Monte Carlo likelihood analysis based on human mobility](http://www.biomedcentral.com/1741-7015/7/45/abstract).  
D. Balcan, H. Hu, B. Goncalves, P. Bajardi, C. Poletto, J. J. Ramasco, D. Paolotti, N. Perra, M. Tizzoni, W. Van den Broeck, V. Colizza, A. Vespignani. _BMC Medicine_ **7**, 45 (2009).

