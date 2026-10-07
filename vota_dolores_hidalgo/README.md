# Vota Dolores Hidalgo - Plebiscito Vecinal Digital

Este es un proyecto construido siguiendo la metodología TDD (Test-Driven Development) en Flutter. 

## Evidencias de Checklist TDD

### 1. Reglas de negocio con sus propias pruebas
> (voto único, opción válida, fecha de cierre, empates)
![Reglas de Negocio](imagenes/1_pruebas_reglas.png)

### 2. Uso de `ResultadoVoto` sin excepciones
> `ResultadoVoto` se usa para casos esperados; no se abusa de excepciones para control de flujo normal.
![ResultadoVoto](imagenes/2_resultado_voto.png)

### 3. Manejo de división entre cero
> `obtenerResultados()` no puede dividir entre cero cuando no hay votos.
![División entre cero](imagenes/3_division_cero.png)

### 4. Responsabilidad de la Interfaz
> La interfaz (`VotacionScreen`) no duplica ninguna regla ya cubierta por `ServicioVotacion`.
![Interfaz delegando lógica](imagenes/4_interfaz_logica.png)

### 5. Prueba de Integración
> Existe una prueba de integración que simula un plebiscito completo, incluyendo un intento de voto duplicado.
![Prueba de Integración](imagenes/5_prueba_integracion.png)
