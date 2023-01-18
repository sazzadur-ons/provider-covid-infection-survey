# provider-covid-infection-survey

This repo is a test case for transforming ONS Covid Infection Survey data into CSV-Ws, as well as training. This is a republication of existing data and no additional functionality can be derived from this repo.


Additionally, below is how to curl SPARQL queries to gss-data.org.uk's SPARQL end point as a proof of concept.

```bash
curl  -H "Accept: text/csv" 'https://beta.gss-data.org.uk/sparql' --data-urlencode query="$(< query.rq)"
```

```bash
curl  -H "Accept: application/json" 'https://beta.gss-data.org.uk/sparql' --data-urlencode query="$(< query.rq)"
```
