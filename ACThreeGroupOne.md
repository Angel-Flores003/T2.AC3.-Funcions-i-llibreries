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

1. TypeIntAvatar
   - Descripció: Posar un int vàlid a avatar
   - Entrada: 3
   - Accions: Bucle();
   - Resultat Esperat: 3
   - Resultat obtingut:

2. TypeInvalidIntAvatar
   - Descripció: Posar un int invàlid a avatar
   - Entrada: -3
   - Accions: Bucle();
   - Resultat Esperat: Error
   - Resultat obtingut:

3. TypeIntEvilness
   - Descripció: Posar un int vàlid a evliness
   - Entrada: 5000
   - Accions: Bucle();
   - Resultat Esperat: 5000
   - Resultat obtingut:

4. TypeInvalidIntEvilness
   - Descripció: Posar un int invàlid a evliness
   - Entrada: -5000
   - Accions: Bucle();
   - Resultat Esperat: Error
   - Resultat obtingut:

5. TypeStringNameAvatarPlusTwoVowels
   - Descripció: Posar una string al nom de l'avatar amb més de dues vocals
   - Entrada: "Hola"
   - Accions: GetVocals();
   - Resultat Esperat: True
   - Resultat obtingut:

6. TypeStringNameAvatarMinusTwoVowels
   - Descripció: Posar una string al nom de l'avatar amb menys de dues vocals
   - Entrada: "Hol4"
   - Accions: GetVocals();
   - Resultat Esperat: False
   - Resultat obtingut:

7. TypeStringNameAvatarOneVowel
   - Descripció: Posar una string al nom de l'avatar amb només un caràcter
   - Entrada: "H"
   - Accions: LengthName();
   - Resultat Esperat: Repeat until in range or error
   - Resultat obtingut:

8. TypeIntEvilnessTwoVowels
   - Descripció: Posar un valor vàlid a evliness i introduir un valor al nom de l'avatar amb més de dues vocals
   - Entrada: 1000
   - Accions: Bucle(); GetVocals();...
   - Resultat Esperat: power = 250, evilness = 0
   - Resultat obtingut:

9. TypeIntEvilnessMinusTwoVowels
   - Descripció: Posar un valor vàlid a evliness i introduir un valor a avatar amb menys de dues vocals
   - Entrada: 1000
   - Accions: Bucle(); GetVocals();...
   - Resultat Esperat: power = 50, evilness = 950
   - Resultat obtingut:

10. TypeSpecialChar
   - Descripció: Posar un caràcter especial considerat a la variable del nom de l'avatar
   - Entrada: "#a"
   - Accions: EspecialChar();
   - Resultat Esperat: Repeat until there are no special chars on the string or error
   - Resultat obtingut:
