### Contenido

- Pseudocódigo
- Mermaid código
- Flowchart

###Pseudocódigo

```
Algoritmo cajero
    Definir dinero, retiro Como Entero
    dinero <- 800
    Escribir "Ingrese la cantidad que desea retirar:"
    Leer retiro
    Si retiro <= dinero Entonces
        Escribir "Retiro exitoso. Retire su dinero."
        dinero <- dinero - retiro
        Escribir "Saldo restante: ", dinero
    Sino
        Escribir "Saldo insuficiente."
    FinSi
FinAlgoritmo
```

###Mermaid codigo
```
flowchart TD
    A(["Inicio"]) --> B["Definir dinero = 800"]
    B --> C[/"Ingrese la cantidad que desea retirar:"/]
    C --> D[/"retiro"/]
    D --> E{"¿retiro &lt;= dinero?"}
    E -- Sí --> F["Retiro exitoso. Retire su dinero."]
    F --> G["dinero = dinero - retiro"]
    G --> H["Saldo restante: , dinero"]
    H --> I(["Fin"])
    E -- No --> J@{ label: "Escribir \"Saldo insuficiente.\"" }
    J --> I

    F@{ shape: lean-r}
    H@{ shape: lean-r}
    J@{ shape: lean-r}

```

[![Captura](https://drive.google.com/uc?export=view&id=1ComCi2J9kg9Z9xs0I_u_vH19GNtI-6P- "Captura")](https://drive.google.com/uc?export=view&id=1ComCi2J9kg9Z9xs0I_u_vH19GNtI-6P- "Captura")


