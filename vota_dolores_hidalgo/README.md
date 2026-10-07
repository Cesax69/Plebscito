# Vota Dolores Hidalgo - Plebiscito Vecinal Digital

Este es un proyecto construido siguiendo la metodología TDD (Test-Driven Development) en Flutter. 

## Evidencias de Checklist TDD

### 1. Reglas de negocio con sus propias pruebas
> (voto único, opción válida, fecha de cierre, empates)
![Reglas de Negocio](<img width="656" height="188" alt="image" src="https://github.com/user-attachments/assets/59241402-4914-4ff3-a48f-c61adf9d96a8" />
)

### 2. Uso de `ResultadoVoto` sin excepciones
> `ResultadoVoto` se usa para casos esperados; no se abusa de excepciones para control de flujo normal.
![ResultadoVoto](<img width="960" height="540" alt="image" src="https://github.com/user-attachments/assets/83a036f1-0e15-484d-933b-8759528184ca" />
)

### 3. Manejo de división entre cero
> `obtenerResultados()` no puede dividir entre cero cuando no hay votos.
![División entre cero](<img width="683" height="228" alt="image" src="https://github.com/user-attachments/assets/8c655611-8c38-4e3c-b979-6ff06b3257d3" />
)

### 4. Responsabilidad de la Interfaz
> La interfaz (`VotacionScreen`) no duplica ninguna regla ya cubierta por `ServicioVotacion`.
![Interfaz delegando lógica](<img width="960" height="538" alt="image" src="https://github.com/user-attachments/assets/905c1a9c-e74a-49a4-95dc-39f280902918" />
)

### 5. Prueba de Integración
> Existe una prueba de integración que simula un plebiscito completo, incluyendo un intento de voto duplicado.
![Prueba de Integración](<img width="960" height="540" alt="image" src="https://github.com/user-attachments/assets/7bdfcee9-ecd9-4292-91d3-76e809484e7f" />
)

### Aplicacion funcionando
![Prueba de Integración](<<img width="1912" height="890" alt="image" src="https://github.com/user-attachments/assets/bc9b1955-9a7b-4caa-9396-b94e4611e5a5" />
<img width="1919" height="922" alt="image" src="https://github.com/user-attachments/assets/1adea402-ddc7-446d-9340-5eec19a4ebaf" />

)



