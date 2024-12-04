flowchart LR
    subgraph Diagnóstico y reparación
        B{Diagnóstico y evaluación} --> C{Desarme y limpieza}
        C --> D[Reparación de componentes]
    end

    A(Recepción del equipo) --> B
    D --> E{Ensamblaje y pruebas}
    E --> F{Control de calidad}
    F --> G(Almacenamiento y entrega al cliente)

    subgraph style Diagnóstico y reparación fill:#fff,stroke:#333,stroke-width:2px
