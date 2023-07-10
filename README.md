Un element HTML devine un container grid atunci când proprietatea sa display este setată pe grid sau în inline-grid.

Exemplu:
.grid-container {
  display: grid;
}

Exemplu:
.grid-container {
   afișare: inline-grid;
}

Toți copiii direcți (direct children) ai containerului grid devin automat elemente grid.

Coloane Grid (Grid Columns)

Liniile verticale ale elementelor grid se numesc coloane (columns).



Rânduri Grid (Grid Rows)

Liniile orizontale ale elementelor grid se numesc rânduri (rows).

apuri Grid

Spațiile dintre fiecare coloană/rând (column/row) se numesc gaps.




Puteți ajusta dimensiunea gapului folosind una dintre următoarele proprietăți:
grid-column-gap
grid-row-gap
grid-gap

Exemplu:

Proprietatea grid-column-gap stabilește diferența dintre coloane:
.grid-container {
  display: grid;
  grid-column-gap: 50px;
}

Exemplu:

Proprietatea grid-row-gap stabilește diferența dintre rânduri:
.grid-container {
  display: grid;
  grid-row-gap: 50px;
}

Exemplu:

Proprietatea grid-gap este o proprietate shorthand pentru proprietățile grid-column-gap și grid-row-gap:
.grid-container {
  display: grid;
  grid-gap: 50px 100px;
}

Exemplu:

Proprietatea grid-gap poate fi, de asemenea, folosită pentru a seta atât row gap cât și column gap într-o singură valoare:
.grid-container {
  display: grid;
  grid-gap: 50px;
}
