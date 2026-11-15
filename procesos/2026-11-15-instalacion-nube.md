# 2026-11-15 · Terminar instalación (sesión en la nube)

**Qué se pidió:** "Continuar instalación".

**Qué se hizo:**
- La actualización automática fallaba porque la rama de trabajo no existía en GitHub. Se creó y se enlazó: `git pull` ya funciona.
- Se crearon las carpetas `privado/`, `bandeja/`, `entregables/`, `procesos/`.
- Se instalaron las librerías para leer PDF, Word, PowerPoint y Excel.
- `scripts/a_pdf.py`: en la nube (Linux) Chrome se trababa; ahora usa `--no-sandbox` y no crea perfil aparte solo en Linux. En Mac/Windows sigue igual.
- Prueba: la plantilla `plantillas/documento.html` se convirtió a PDF sin problema.

**Falta (es de Jacky):** entrevista inicial, logo/colores en `bandeja/`, documentos de ejemplo.
