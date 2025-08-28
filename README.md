# team-notes
## Instalación
1. Clonar el repo: git clone https://github.com/tu-usuario/team-notes.git
2. Entrar a la carpeta: cd team-notes
3. Instalar dependencias (si aplica): pip install -r requirements.txt

## Uso
- Para agregar una nota: python -m app.cli add "Título" "Contenido"
- Para listar notas: python -m app.cli list
- Para buscar notas: python -m app.cli search "palabra"
- Para eliminar nota: python -m app.cli delete <id>