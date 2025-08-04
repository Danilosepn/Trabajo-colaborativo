# Trabajo-colaborativo
### 1. Configuración inicial
- Se creó un repositorio en GitHub llamado **proyecto-colaborativo**.
- Se otorgaron permisos de escritura a todos los integrantes.

### 2. Simulación de trabajo colaborativo
- **Danilo Unapucha** creó la rama `feature-danilo` y realizó dos cambios:
  1. Modificó el mensaje en la función `saludo()` para identificarse.
  2. Añadió un mensaje previo en la función `suma()` indicando que se está calculando la suma.

- **Henry Luisa** creó la rama `feature-henry` y realizó dos cambios:
  1. Modificó el mensaje en la función `saludo()` para identificarse (en la misma línea que Danilo, provocando un conflicto).
  2. Cambió el formato de salida en la función `suma()` para mostrar el resultado final directamente.

- Ambos subieron sus cambios y realizaron **Pull Requests** hacia `main`.

### 3. Conflictos y resolución
- **Conflicto detectado en `funciones.c`**:  
  La línea modificada en `saludo()` era diferente en ambas ramas.
  - **Solución acordada por el equipo**:
Se combinó el mensaje para reflejar el trabajo conjunto:
```c
void saludo() {
    printf("Hola, somos Danilo y Henry trabajando juntos.\n");
}
