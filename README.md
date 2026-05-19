🌐 [Português (BR)](README.pt_BR.md) | [Español](README.es.md)

# Soc Ops

## 🎉 Juego de Bingo Social para eventos y equipos

**Soc Ops** es una aplicación web Blazor diseñada para romper el hielo en reuniones presenciales. Busca compañeros que cumplan las preguntas, marca casillas y consigue 5 en línea antes que los demás.

[▶️ Ver Demo](https://dotnet-presentations.github.io/vscode-github-copilot-agent-lab/) • [📘 Guía del taller](https://dotnet-presentations.github.io/vscode-github-copilot-agent-lab/docs/)

---

## ✨ ¿Por qué Soc Ops?

- ✅ Experiencia interactiva en tiempo real con Blazor.
- ✅ Ideal para eventos, talleres y actividades de networking.
- ✅ Fácil de personalizar con nuevas preguntas y reglas.
- ✅ Construido como plantilla de aprendizaje para agentes y desarrollo frontend.

---

## 🚀 Características principales

- Tablero de bingo dinámico
- Juego social colaborativo
- Componentes reutilizables con Razor
- Lógica de juego separada en servicios
- Guía de taller completa en `workshop/`

---

## 📁 Estructura del proyecto

- `SocOps/` - aplicación Blazor principal
- `SocOps/Components/` - componentes UI reutilizables
- `SocOps/Data/` - contenido y preguntas del juego
- `SocOps/Models/` - modelos de datos del juego
- `SocOps/Services/` - lógica de bingo y gestión del estado
- `workshop/` - material del taller en varios idiomas

---

## 🛠️ Requisitos

- [.NET 10 SDK](https://dotnet.microsoft.com/download/dotnet/10.0) o superior

---

## ▶️ Ejecutar localmente

```bash
cd SocOps
dotnet run
```

Abre la URL que indique la terminal, normalmente `https://localhost:7132`.

---

## ✅ Compilar

```bash
cd SocOps
dotnet build
```

---

## 💡 Útiles para desarrolladores

- `SocOps/Services/BingoGameService.cs` - lógica del juego
- `SocOps/Services/BingoLogicService.cs` - reglas de bingo
- `SocOps/Components/` - interfaz y experiencia de usuario
- `SocOps/Data/Questions.cs` - preguntas de la sesión de bingo

---

## 📚 Guías y recursos

- `README.es.md` - versión en español
- `README.pt_BR.md` - versión en portugués
- `workshop/` - pasos del taller y ejercicios prácticos

---

## 🚀 Despliegue

El proyecto se publica automáticamente en GitHub Pages al hacer push a `main`.
