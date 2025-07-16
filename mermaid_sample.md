```mermaid
<typ_diagramu>
  …obsah…

  flowchart LR
  A[Start] --> B{Rozhodnutí?}
  B -- Ano --> C[Akce 1]
  B -- Ne --> D[Akce 2]
  C --> E[Konec]
  D --> E

  