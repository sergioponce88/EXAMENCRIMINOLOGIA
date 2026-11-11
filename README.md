# Examen final 2026 · Criminología · IESP

- **Examen:** `index.html`. 6 preguntas: una respuesta, varias respuestas y verdadero/falso. El orden de las preguntas y de las opciones se mezcla para cada evaluado. Salir de la pantalla anula la pregunta en curso. Nota de 1 a 10. En las de varias respuestas se aprueba solo si se marcan todas las correctas y ninguna incorrecta.
- **Monitor docente:** `monitor.html`. Se entra con clave. Resultados en vivo cada 20 s, preguntas más falladas, filtros, CSV e informe PDF.

## Conectar la planilla (una sola vez)
1. Crear una planilla nueva de Google Sheets y entrar a Extensiones > Apps Script.
2. Pegar `apps-script/Codigo.gs` y cambiar `CLAVE_DOCENTES`.
3. Implementar > Nueva implementación > Aplicación web · Ejecutar como: Yo · Acceso: Cualquier usuario.
4. Copiar la URL `/exec` y pegarla en `SCRIPT_URL` de `index.html` y de `monitor.html`.
