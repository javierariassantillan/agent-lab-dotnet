# Instrucciones del Proyecto

## Objetivo
Este proyecto es una aplicación web en Blazor llamada **Soc Ops**, un juego de bingo social que se ejecuta localmente con .NET.

## Estructura principal
- `SocOps/` : aplicación Blazor.
- `SocOps/Components/` : componentes de la interfaz de usuario.
- `SocOps/Data/` : datos del juego.
- `SocOps/Models/` : modelos de datos.
- `SocOps/Services/` : lógica del juego y servicios.
- `workshop/` : guía de taller y ejercicios en español, portugués e inglés.

## Requisitos
- [.NET 10 SDK](https://dotnet.microsoft.com/download/dotnet/10.0) o superior.

## Cómo ejecutar
1. Abre una terminal en la raíz del repositorio.
2. Entra en la carpeta del proyecto:
   ```bash
   cd SocOps
   ```
3. Ejecuta la aplicación:
   ```bash
   dotnet run
   ```
4. Abre el navegador en `https://localhost:7132` o en la URL que muestre la terminal.

## Cómo compilar
Desde la carpeta `SocOps`:
```bash
dotnet build
```

## Desarrollo y edición
- Para modificar la lógica del juego, revisa `SocOps/Services/BingoGameService.cs` y `SocOps/Services/BingoLogicService.cs`.
- Para cambiar la interfaz de usuario, edita los archivos `.razor` en `SocOps/Components/`.
- El archivo `SocOps/Data/Questions.cs` contiene las preguntas del bingo.

## Consejos rápidos
- Usa `dotnet run` para probar cambios rápidamente.
- Revisa la guía del taller en `workshop/` para entender el flujo y los objetivos.
- Si trabajas con GitHub Codespaces, abre el repositorio en Codespaces y ejecuta el proyecto desde la terminal integrada.

## Recursos adicionales
- `README.es.md` : versión en español del README.
- `README.md` : README principal.
- `workshop/` : material del taller para seguir los pasos del proyecto.

## Lineamientos de diseño
- Mantener un estilo corporativo limpio y profesional: tonos azules, grises suaves y blanco.
- Usar una tipografía legible y moderna; priorizar jerarquía clara entre títulos, subtítulos y texto de soporte.
- Preferir tarjetas con bordes suaves, sombras sutiles y suficiente espacio entre elementos.
- Hacer que los botones sean prominentes y consistentes: fondo azul, texto blanco y bordes redondeados.
- Garantizar buena legibilidad en móvil y escritorio; usar espacios amplios y evitar interfaces recargadas.
- Aplicar transiciones suaves para estados de botón y tarjetas, pero sin exagerar las animaciones.
- Mantener la arquitectura del CSS utilitario actual, evitando introducir frameworks externos si no es estrictamente necesario.
