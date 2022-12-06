## Del 2 - CI

#### Oppgave 3:
* For å nekte mulighet til å pushe direkte på main branch kan man gå inn i settings => branches og legge til en branch protection rule.\
Her kan du skrive inn main og checke "Require a pull request before merging".
* For å i tillegg kreve godkjent review før mulighet til å merge sørger du for at "Require approvals" er checked med 1 som required approval. Det siste er default.
* Du kan checke "Require status checks to pass before merging" for å sørge for at feature branchen PRen er basert på er verifisert av Github Actions.

## Del 4 - Docker
#### Oppgave 1:
For å få workflowen til å fungere med min DockerHub konto må jeg legge inn mitt brukernavn og en access token som secrets i GitHub. I utganspunktet feiler workflowen fordi den ikke klarer å autentisere mot DockerHub. 