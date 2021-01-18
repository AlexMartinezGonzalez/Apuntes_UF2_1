# Apuntes_UF2_1

## QUE ES FA EN AQUESTA UF?

- Identificar els diferents tipus de proves.
- Definir casos de prova.
- Efectuar proves unitàries de classes i funcions.
- Efectuar proves d'integració, de sistema i d'acceptació.
- Realitzar mesures de qualitat sobre el programari desenvolupat.


### OBJECTIUS PROVES

Les proves es centren en dos objectius:
1. Provar si el programari no fa el que ha de fer.
2. Provar si el programari fa el que no ha de fer.

Per fer les proves utilizem diferents **frameworks**.

### Model en V

Es un model molt semblant a el model en cascada.
- Visió jerarquitzada amb diferents nivells.
- Els nivells superiors indiquen major abstracció.
- Els nivells inferiors indiquen major nivell de detall.
- El resultat d'una fase és l'entrada de la següent fase.
- Existeixen diferents variants amb més o menys quantitat d'activitats.



### FRAMEWORK

Els framework estan compostos per:

- un conjunt de les millors pràctiques i suposicions
- eines comunes
- biblioteques

Permet unificar el procés de desenvolupament entre desenvolupadors.




## **PROVES**

Tenim dos tipus:

- **Proves dinàmiques:** Requereixen l'execució de l'aplicació. Permeten mesurar el comportament de l'aplicació desenvolupada.

- **Proves estàtiques:** Es realitzen sense executar el codi de l'aplicació. S'examina el codi font.



### ESTRATÈGIES DE PROVA DE CAIXA NEGRA
- S'estudia el sistema des de fora.
- Es treballa sobre la interfície.
- No es tenen en compte els detalls interns de funcionament.
- Es proporcionen entrades i s'estudien les sortides.
- Principals tècniques:
  - Particions d'equivalència
  - Valors límit

### ESTRATÈGIES DE PROVA DE CAIXA BLANCA
- S'examina el codi font i la seva execució.
- Es comproven els fluxos d'execució dins de cada unitat (funció, classe, mòdul, etc.)
- També poden comprovar els fluxos entre unitats durant la integració.
- I fins i tot entre subsistemes, durant les proves de sistema.
- Principals tècniques:
  - Cobertura de codi
  - Prova de bucles


### TIPUS DE PROVES
**Funcionals:** Avaluen el compliment dels requisits.

**No funcionals:** Avaluen aspectes addicionals com rendiment, seguretat, ...



### PROVES FUNCIONALS
- Proves unitàries (o d'unitat)
- Proves de regressió
- Proves d'integració
- Proves de fum (proba de foc)
- Proves de sistema
- Proves alfa i beta
- Proves d'acceptació (validació per part de client)
