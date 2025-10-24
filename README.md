[README.md](https://github.com/user-attachments/files/23129813/README.md)
# Organizador Fortuny

Proyecto cliente (frontend) para gestionar solicitudes de vacaciones, días libres y asuntos propios.

## Estructura
- `index.html` — interfaz y estilos.
- `script.js` — lógica (FullCalendar, EmailJS, exportación, panel admin).
- `data/solicitudes.json` — JSON de ejemplo (solo lectura al arrancar).
- Los cambios se guardan en `localStorage`. Para respaldo/transferencia se puede **guardar JSON** y **cargar JSON** desde el panel admin.

## Uso
1. Coloca los archivos en una carpeta.
2. Abre con un servidor local (recomendado) o directamente `index.html` (funcionará, pero algunas funciones con fetch pueden necesitar servidor).
3. Configura EmailJS en `script.js`.
4. Inicia pruebas.

## Notas
- La app carga `data/solicitudes.json` al inicio **solo en lectura** y solo si `localStorage` está vacío.
- Exportar a `.xlsx` y descargar JSON están implementados del lado cliente.
