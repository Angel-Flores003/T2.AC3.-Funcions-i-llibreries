# Proves
## Equivalencies

Nivell de maldat: {1000 - 50000}

Nom de l'avatar: {2 - 25}

Caracters especials: { "@", "#", "-", "/", "_" } - {$, !, ·, %, &, (, ), =, \, |}

Vocals: {a, e, i, o, u}


## Limits

num ha de ser un número entre 1000 i 50000, no inclosos. Ej 1001 o 49999.

Maldat: {999, 50001}

name ha de ser major que 2 i més petit que 25 snese incloure'ls.Ej 3 o 24.

Nom: {1, 26}

Caracters especials: {$, !, ·, %, &, (, ), =, \, |}


## Casos de prova
## Altres casos de prova:

1. Type string avatar
   - Descripció: Posar una string a int avatar
   - Entrada: "Hola"
   - Accions: Assigna entrada a avatar
   - Resultat Esperat: Format Error
   - Resultat obtingut:

2. Type string evilness
   - Descripció: Posar una string a int evliness
   - Entrada: "Hola"
   - Accions: Assigna entrada a evilness
   - Resultat Esperat: Format Error
   - Resultat obtingut:

3. Type string avatar +2
   - Descripció: Posar una string a avatar amb més de dues vocals
   - Entrada: "Hola"
   - Accions: Assigna entrada a avatar, GetVocals();
   - Resultat Esperat: True
   - Resultat obtingut:

4. Type string avatar -2
   - Descripció: Posar una string a avatar amb menys de dues vocals
   - Entrada: "Hol4"
   - Accions: Assigna entrada a avatar, GetVocals();
   - Resultat Esperat: False
   - Resultat obtingut:

5. Type vale OOR in evliness
   - Descripció: Posar un valor fora de l'interval de la condició d'evilness
   - Entrada: -34
   - Accions: Assigna entrada a evilness, Bucle();
   - Resultat Esperat: Repeat until in range
   - Resultat obtingut:

6. Type string with 1v in avatar
   - Descripció: Posar una string a avatar amb només un caràcter
   - Entrada: "H"
   - Accions: Assigna entrada a avatar, LengthName();
   - Resultat Esperat: Repeat until in range or error
   - Resultat obtingut:

7. Type valid int in evliness +2v
   - Descripció: Posar un valor vàlid a evliness i introduir un valor a avatar amb més de dues vocals
   - Entrada: 1000
   - Accions: Assigna entrada a avatar, Assigna entrada a evilness, GetVocals();...
   - Resultat Esperat: power = 250, evilness = 0
   - Resultat obtingut:

8. Type valid int in evliness -2v
   - Descripció: Posar un valor vàlid a evliness i introduir un valor a avatar amb menys de dues vocals
   - Entrada: 1000
   - Accions: Assigna entrada a avatar, Assigna entrada a evilness, GetVocals();...
   - Resultat Esperat: power = 50, evilness = 950
   - Resultat obtingut:

9. Type valid int in evliness +2v
   - Descripció: Posar un valor vàlid a evliness i introduir un valor a avatar amb més de dues vocals
   - Entrada: 1000
   - Accions: Assigna entrada a avatar, Assigna entrada a evilness, GetVocals();...
   - Resultat Esperat: power = 250, evilness = 0
   - Resultat obtingut:

10. Type special char not included in list
   - Descripció: Posar un caràcter especial no considerat a la variable avatar
   - Entrada: "$a"
   - Accions: Assigna entrada a avatar, EspecialChar();
   - Resultat Esperat: Repeat until there are no special chars on the string or error
   - Resultat obtingut:

11. Type special char
   - Descripció: Posar un caràcter especial considerat a la variable avatar
   - Entrada: "#a"
   - Accions: Assigna entrada a avatar, EspecialChar();
   - Resultat Esperat: Repeat until there are no special chars on the string or error
   - Resultat obtingut:
