# 6.2.Bateria-de-ejercicios

## Ejercicio 1 
```mermaid
classDiagram
    Usuario : -String nombre
    Usuario : -String contraseña
    Usuario : +String coreo
    Usuario : +cambiarPassword()
    Usuario : -validarEmail()
```

## Ejercicio 2
```mermaid
classDiagram
	Persona : -String nombre
	Persona : -String dni
	Estudiante : -String numeroExpediente
	Estudiante :-double notaMedia
	Estudiante --|> Persona
```

## Ejercicio 3
```mermaid
classDiagram
	Computadora 
	PlacaBase
	Raton

	Computadora *-- PlacaBase
	Computadora o-- Raton
```

## Ejercicio 4
```mermaid
classDiagram
	CentroComercial
	Tienda

	CentroComercial "1" -- "1.." Tienda
```
