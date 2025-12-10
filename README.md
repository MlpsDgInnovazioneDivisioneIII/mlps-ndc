# Asset per il catalogo nazionale della semantica dei dati
Questo è il repository MLPS per l'alimentazione del National Data Catalog (NDC): https://www.schema.gov.it/.
Esso contiene l'ontologia di MLPS che descrive il patrimonio informativo dell'ente relativamente al dominio del _fascicolo sociale e lavorativo del cittadino_ e della _prestazione di sostegno_.

Il catalogo nazionale della semantica dei dati, o NDC, consente:
> "Ricerca e riuso di asset semantici, tra cui ontologie, schemi dati e vocabolari controllati per supportare lo sviluppo di API semanticamente e sintatticamente interoperabili"

## Organizzazione delle informazioni

I file presenti in questo repository sono organizzati secondo la seguente alberatura:

```bash
┌─ assets/controlled-vocabularies/
│  ├─ ...
│  ├─ frame-short.yamlld
│  └─ notes.md
├─ assets/ontologies/
│  ├─ core
│  │   ├─ latest
│  │   │   ├─ core.n3
│  │   │   ├─ core.owl
│  │   │   └─ core.ttl
│  │   ├─ v{version}
│  │   │   ├─ core.n3
│  │   │   ├─ core.owl
│  │   │   └─ core.ttl
│  ├─ ...
│  └─ notes.md
├─ assets/schemas/
│  ├─ ...
│  └─ notes.md
├─ README.md
└─ publiccode.yaml
```

Ontologie e [vocabolari controllati](https://www.agid.gov.it/it/dati/vocabolari-controllati) sono documenti [RDF](https://www.w3.org/RDF/) serializzati in formato [TURTLE](https://www.w3.org/TR/turtle/) mentre gli schemi  [Open Api 3 (OAS3)](https://spec.openapis.org/oas/v3.1.0) sono serializzati in formato [YAML](https://yaml.org/).

