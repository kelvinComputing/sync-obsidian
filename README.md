## Como conectar Obsidian con un Repositorio en GitHub
- Crear un repositorio en GitHub:
		Ve a GitHub y crea un repositorio nuevo (puede ser público o privado ).
- Clonar el Repositorio en tu Computadora:
		Abre la terminal y clona tu repositorio con : git clone URL(URL De tu repositorio)
- Configurar Obsidian: 
		Abrir Obsidian y  seleccionar la carpeta clonada como tu vault.
- Inicilalizar Git (si es necesario):
		Si se usa una vault existente, iniciar Git en la carpeta: -git init       -git remote add origin URL(URL de tu repositorio)
- Organizar tus carpetas usando el metodo PARA:
		Organiza tu vault de Obsidian creando carpetas puedes ser desde Obsidian o Visual Studio Code siguiendo esta estructura: (Projects, Areas, Resources, Archives)
- Conectar Visual Studio Code para Editar Archivos de Obsidian: 
		Descarga e instala Visual Studio Code.
		Abrir Visual Studio Code ir a la sección de extensiones y busca e instala la extensión Obsidian.md
		Abre la carpeta de tu vault en VSCode para editar tus archivos .md directamente desde ahí
- ¡Eso es todo! Ahora puedes editar tus notas de Obsidian directamente desde VSCode.
- Puedes usar plugins en Obsidian, como "Obsidian Git", para automatizar el proceso de commit y push directamente desde la interfaz de Obsidian.