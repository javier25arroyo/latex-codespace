# LaTeX Codespace

Este repositorio está configurado con un entorno completo de LaTeX usando GitHub Codespaces.

## 🚀 Inicio Rápido

1. Haz clic en el botón **Code** > **Codespaces** > **Create codespace on main**
2. Espera a que el codespace se configure (esto puede tardar unos minutos la primera vez)
3. Una vez listo, abre el archivo `main.tex` y empieza a editar

## 📝 Uso

### Compilar un documento LaTeX

1. Abre cualquier archivo `.tex` en el editor
2. El documento se compilará automáticamente al guardar cambios
3. Para ver el PDF generado, haz clic en el icono de "View LaTeX PDF" en la barra superior o usa el comando `Ctrl+Alt+V` (o `Cmd+Alt+V` en Mac)

### Comandos útiles

- **Build LaTeX project**: `Ctrl+Alt+B` (o `Cmd+Alt+B` en Mac)
- **View PDF**: `Ctrl+Alt+V` (o `Cmd+Alt+V` en Mac)
- **Clean auxiliary files**: Usa la paleta de comandos (`Ctrl+Shift+P`) y busca "LaTeX Workshop: Clean"

## 🛠️ Características incluidas

- **TeX Live**: Distribución completa de LaTeX
- **LaTeX Workshop**: Extensión de VS Code para edición de LaTeX
  - Autocompilación al guardar
  - Vista previa de PDF integrada
  - Syntax highlighting
  - IntelliSense para comandos LaTeX
  - Snippets útiles
- **Soporte para español**: Paquetes de idioma español incluidos

## 📦 Paquetes instalados

- `texlive-latex-base`: Paquetes básicos de LaTeX
- `texlive-latex-extra`: Paquetes adicionales de LaTeX
- `texlive-fonts-recommended`: Fuentes recomendadas
- `texlive-fonts-extra`: Fuentes adicionales
- `texlive-lang-spanish`: Soporte para español
- `latexmk`: Herramienta de compilación automática

## 📄 Archivo de ejemplo

El archivo `main.tex` incluye:
- Estructura básica de un documento
- Secciones y subsecciones
- Listas
- Fórmulas matemáticas
- Configuración para español

## 🔧 Personalización

Puedes modificar la configuración en `.devcontainer/devcontainer.json` para:
- Agregar más paquetes de LaTeX
- Instalar extensiones adicionales de VS Code
- Cambiar configuraciones de compilación

## 📚 Recursos

- [Documentación de LaTeX](https://www.latex-project.org/help/documentation/)
- [LaTeX Workshop Wiki](https://github.com/James-Yu/LaTeX-Workshop/wiki)
- [Overleaf Learn](https://www.overleaf.com/learn) - Tutoriales de LaTeX

## ❓ Solución de problemas

**Problema**: El PDF no se genera
- **Solución**: Verifica que no haya errores de sintaxis en tu archivo `.tex`. Los errores aparecerán en el panel de "Problems" de VS Code.

**Problema**: Faltan paquetes
- **Solución**: Agrega los paquetes necesarios en el `postCreateCommand` del archivo `devcontainer.json` y reconstruye el codespace.

## 📝 Licencia

Este proyecto es de código abierto y está disponible para uso personal y educativo.