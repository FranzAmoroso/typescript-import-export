# TypeScript Import and Export

In questo progetto, abbiamo adottato una struttura modulare per organizzare logicamente la nostra applicazione utilizzando TypeScript. Abbiamo suddiviso la logica in diversi file per migliorare la leggibilità e la manutenibilità del codice.

#### Aggiornamento di ECMAScript

Per garantire l'utilizzo delle funzionalità più recenti di ECMAScript, abbiamo apportato alcune modifiche al file `tsconfig.json`:

```json
// File: tsconfig.json

{
  "compilerOptions": {
    /* ... altre opzioni ... */

    /* Cambiamo la versione di EcmaScript a ES6 */
    "target": "ES6",

    /* Cambiamo la versione di EcmaScript per i moduli a ES6 */
    "module": "ES6",

    /* ... altre opzioni ... */
  }
}
