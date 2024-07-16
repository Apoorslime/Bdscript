## Struttura di Base del Linguaggio

### Esempio Ipotetico di un'Istruzione

```
$token_istruzione_uno_esempio[arg1;arg2;arg3;...]
$token_istruzione_due_esempio[arg1;arg2;arg3;...]
```

- Il simbolo `$` indica l'inizio di un'istruzione. 
- `token_istruzione_uno_esempio` è la parola chiave ipotetica dell'istruzione.
- Le parentesi `[]` racchiudono l'istruzione. Il carattere `]` indica sia la chiusura dell'istruzione che funge da delimitatore.
- Il punto e virgola `;` all'interno dell'istruzione separa gli argomenti.

### Esempio Ipotetico di un'Istruzione a Blocco

```
$token_istruzione_uno_esempio[arg1;arg2;...]
codice qui 
$end[token_istruzione_uno_esempio]
```

- `$end[<nome_parola_chiave>]` indica la chiusura di un blocco di codice, equivalente alla chiusura di un blocco `{}` in altri linguaggi.
