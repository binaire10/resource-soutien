Cryptage César

http://www.cryptage.org/chiffre-cesar.html
Le chiffre de César est la méthode de cryptographie la plus ancienne communément admise par l'histoire. Il consiste en une substitution mono-alphabétique : chaque lettre est remplacée("substitution") par une seule autre("mono-alphabétique"), selon un certain décalage dans l'alphabet ou de façon arbitraire. D'après Suétone, César avait coutume d'utiliser un décalage de 3 lettres : A devient D, B devient E, C devient F, etc. Il écrivait donc son message normalement, puis remplaçait chaque lettre par celle qui lui correspondait.

Realisé le cryptage César ROT13 avec un décalage de 13

|Clair | A | B | C | D | E | F | G | H | I | J | K | L | M | N | O | P | Q | R | S | T | U | V | W | X | Y | Z |
|------|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|
|Code  | D | E | F | G | H | I | J | K | L | M | N | O | P | Q | R | S | T | U | V | W | X | Y | Z | A | B | C |

implémenter les predicats : 
```cpp
bool isMaj(char);
bool isMin(char);
bool isAlpha(char);
```
isMaj est une fonction qui dit si le caractère est une majuscule.
isMin est une fonction qui dit si le caractère est une minuscule.
isAlpha est une fonction qui dit si le caractère est une lettre de l'alphabet.

implémenter les fonctions:
```cpp
char sucesseur(char);
char predecesseur(char);
char decalerCaractere(char, int);
```
puis
```cpp
char cryptage(std::string &, int decalage);
char cryptagePairImpair(std::string &);
char cryptagePosition(std::string &);
char cryptagePairImpairEtPosition(std::string &);
```
