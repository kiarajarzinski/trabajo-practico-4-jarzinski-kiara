# Glosario 

## Tipo
Define la naturaleza de los datos (por ejemplo, string, number, boolean).
**Ejemplo:**
```typescript
let edad: number = 20;
```

## Tipo Unión 
Permite que una variable acepte más de un tipo de dato.
**Ejemplo:**
```typescript
let id: string | number;
id = "A1";
id = 10;
```

## Interfaz 
Define la estructura que debe tener un objeto.
**Ejemplo:**
```typescript
interface Persona {
  nombre: string;
  edad: number;
}
```

## Enum
Permite definir un conjunto de constantes con nombre.
**Ejemplo:**
```typescript
enum Color {
  Rojo,
  Verde,
  Azul
}
```

## Tipo Literal
 Restringe una variable a un conjunto específico de valores.
**Ejemplo:**
```typescript
type Estado = "activo" | "inactivo";
let estado: Estado = "activo";
```

## Función Tipada
 Una función que define el tipo de sus parámetros y su valor de retorno.
**Ejemplo:**
```typescript
function sumar(a: number, b: number): number {
  return a + b;
}
```

## Type Assertion (Aserción de tipo)
 Permite indicar manualmente el tipo de una variable cuando TypeScript no puede inferirlo.
**Ejemplo:**
```typescript
let valor: any = "123";
let longitud: number = (valor as string).length;
```