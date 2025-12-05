# Compilar y ejecutar (Windows)

Instrucciones rápidas para compilar y ejecutar el proyecto en Windows.

Usando PowerShell (recomendado):

```powershell
.
cd "c:\Users\mokas\OneDrive\Documents\ADA07"
.
# Ejecutar el script PowerShell de compilación
.
powershell -ExecutionPolicy Bypass -File .\build.ps1

# Ejecutar el binario
.\output\main.exe
```

Usando CMD (batch):

```cmd
cd "c:\Users\mokas\OneDrive\Documents\ADA07"
build.bat
output\main.exe
```

Usando la tarea de VS Code:

- Abrir la paleta de comandos (Ctrl+Shift+P) -> `Tasks: Run Build Task` (o tecla rápida Ctrl+Shift+B).
