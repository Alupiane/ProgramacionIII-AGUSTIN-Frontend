# Programación III - Frontend (Agustín Lupianez)

Proyecto Angular de la materia: Header, Dashboard, Footer, **Login** contra la API y ejercicios de **Angular Forms**.
El backend (API .NET) está en el repositorio `ProgramacionIII-AGUSTIN-Backend`.

## Ejecutar

```bash
npm install
npm start
```

- `http://localhost:4200/` → Dashboard
- `http://localhost:4200/login` → Login (necesita la API del backend ejecutándose en `http://localhost:5006`)
- `http://localhost:4200/registro` → Ejercicio 1 de Forms: registro con FormBuilder, validaciones, grupo anidado y patchValue
- `http://localhost:4200/pasatiempos` → Ejercicio 2 de Forms: formulario dinámico con FormArray

## Tests

```bash
npm test
```

El recorrido completo de los datos del login está explicado en [`RECORRIDO-LOGIN.md`](RECORRIDO-LOGIN.md).
