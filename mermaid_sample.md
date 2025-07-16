# Mermaid Sample

## Diagram Flowchart LR

```mermaid
flowchart LR
  A[Start] --> B{Rozhodnutí?}
  B -- Ano --> C[Akce 1]
  B -- Ne --> D[Akce 2]
  C --> E[Konec]
  D --> E
```

## Diagram Flowchart TB

```mermaid
flowchart TB
  A[Start] --> B{Rozhodnutí?}
  B -- Ano --> C[Akce 1]
  B -- Ne --> D[Akce 2]
  C --> E[Konec]
  D --> E
```

## Ostatní tvary

```mermaid
flowchart TB
  A((Start)) --> B{Rozhodnutí?}
  B -- Ano --> C[Proces]
  B -- Ne --> D[[Subrutina]]
  C --> E{{I/O operace}}
  D --> F([Konec])
  E --> F
```