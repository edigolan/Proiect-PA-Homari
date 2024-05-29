# Maximizarea Capturii de Homari

## Descriere
Acest proiect implementează o soluție pentru problema maximizării capturii de homari, în care un pescar trebuie să selecteze homari pentru a umple plasa sa cu o capacitate maximă, astfel încât să maximizeze valoarea totală a capturii, respectând în același timp limita de capacitate a plasei.

## Problema
Un pescar explorează o regiune de coastă bogată în homari, fiecare având dimensiunea sa (în centimetri) și valoarea sa (în monede de aur). Plasa pescarului are o capacitate limitată, exprimată în numărul total de centimetri pe care o poate conține. Având o listă detaliată cu dimensiunile și valorile homarilor disponibile în acea regiune, sarcina este să se elaboreze o strategie prin care pescarul să selecteze homarii în așa fel încât să maximizeze valoarea totală a capturii, respectând în același timp limita de capacitate a plasei.

## Exemplu
### Homari disponibili:
- Homarul A: Dimensiune = 4 cm, Valoare = 20 monede de aur
- Homarul B: Dimensiune = 3 cm, Valoare = 15 monede de aur
- Homarul C: Dimensiune = 2 cm, Valoare = 10 monede de aur
- Homarul D: Dimensiune = 5 cm, Valoare = 25 monede de aur

### Capacitatea plasei: 10 cm

Provocarea este de a selecta combinația de homari care maximizează valoarea totală fără a depăși o dimensiune totală de 10 cm.

### Soluție
O posibilă soluție ar implica alegerea homarilor A și C, oferindu-ne o dimensiune totală de 6 cm (4 cm + 2 cm) și o valoare totală de 30 monede de aur (20 + 10). Totuși, o soluție mai bună ar fi să alegem homarii B, C și D, care împreună au o dimensiune totală de 10 cm (3 cm + 2 cm + 5 cm) și oferă o valoare totală mai mare de 50 monede de aur (15 + 10 + 25). Această combinație umple exact capacitatea plasei și maximizează valoarea capturii.

## Utilizare
Pentru a utiliza acest program, compilați și rulați codul sursă disponibil în acest repository. Programul va solicita introducerea numărului de homari, dimensiunile și valorile acestora, precum și capacitatea plasei. După introducerea datelor, programul va afișa valoarea maximă a capturii și homarii incluși în plasă pentru a atinge această valoare maximă.

## Contribuții
Contribuțiile sunt binevenite! Dacă aveți sugestii de îmbunătățire a codului sau a documentației, vă rugăm să trimiteți un pull request.

## Licență
Acest proiect este licențiat sub [MIT License](LICENSE).
