# Introducción

Estos  apuntes sirven  como prueba  para  la posible  creación de  un  manual de  la materia  de
*Redacción y exposición de temas de ingeniería* en formato Markdown con Gitbook.

Los archivos originales estaban en formato Org-Mode.

```uml
@startuml

    Class Stage
    Class Timeout {
        +constructor:function(cfg)
        +timeout:function(ctx)
        +overdue:function(ctx)
        +stage: Stage
    }
     Stage <|-- Timeout

@enduml
```
