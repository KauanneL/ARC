```mermaid
flowchart TD
A[Inicio] --> B[Entrar com a idade]
B --> C{Maior de idade?}
C --> |Sim| D[Pode entrar]
C --> |Nao| E[Entrada proibida]
D --> F[Fim]
E --> F[Fim]

```