# Lista de cotejo formativa de IA — Preparatorias (MCCEMS 2025)

Página web estática para orientar la revisión formativa de evidencias escolares y el diálogo sobre el uso transparente de IA generativa en Educación Media Superior.

## Publicar en GitHub Pages

1. Crea un repositorio público en GitHub (por ejemplo, `checklist-ia-prepas`).
2. Sube `index.html` y `.nojekyll` a la raíz del repositorio. Puedes subir también este `README.md`.
3. Abre **Settings → Pages**.
4. En **Build and deployment**, selecciona **Deploy from a branch**.
5. Selecciona la rama **main** y la carpeta **/(root)**. Guarda.
6. Abre la dirección indicada en **Settings → Pages**. Suele seguir la forma `https://USUARIO.github.io/checklist-ia-prepas/`.

## Funcionamiento

- Marcado de indicadores y selección de intensidad de 1 a 5 estrellas.
- Ajuste de pesos, notas del evaluador y carga de un caso ficticio.
- Guardado local temporal/persistente en `localStorage` del navegador (no se envían datos a un servidor por esta página).
- Exportación de PDF y CSV desde el navegador. El PDF requiere que carguen las bibliotecas externas de jsPDF y AutoTable desde cdnjs; si no están disponibles, se genera un informe HTML.
- Compatible con escritorio y móvil. No necesita backend ni cuentas.

## Cuidado de datos y alcance

**No ingreses datos personales reales de menores ni información sensible** en una página publicada o un dispositivo compartido. El nombre del caso puede ser un código ficticio. La información de trabajo se guarda en el navegador local y puede quedar accesible para quienes utilicen el mismo perfil; usa «Nuevo caso» y borra los datos del sitio si el equipo es compartido.

El puntaje **no prueba** uso de IA ni constituye base automática para sanciones. Los pesos y umbrales son propuestas no validadas y se usan para decidir qué conversar y revisar formativamente. Es una adaptación didáctica, no una herramienta oficial del MCCEMS 2025.

## Dependencias externas

- [jsPDF 2.5.1](https://cdnjs.com/libraries/jspdf) y AutoTable 3.8.2 para exportar PDF.
- Google Fonts para tipografía (la página dispone de fuentes de sistema alternativas).

Los archivos de CDN y fuentes externas pueden generar solicitudes de red; revisa las políticas de tu plantel antes de usarlo con datos reales.
