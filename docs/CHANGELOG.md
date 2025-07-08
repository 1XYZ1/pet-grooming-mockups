========================================================
PROTOTIPO AUTH – HISTORIAL DE VERSIONES
Repositorio : github.com/tuusuario/prototipo-auth
Flujo : main (congelada) • develop (iteraciones)
Storage : Mockitt → Export • Git LFS para binarios
========================================================

v0.3-rc (2025-06-22) — Release Candidate
────────────────────────────────────────────────────────
Autor : Ramón Hernández <ra.hernandezc@duocuc.cl>
Descripción : Pantalla de bloqueo tras 3 intentos,
mensajes de error accesibles, ajuste
de contraste AA en botones primarios.
Archivos nuevos : design/frames-v0.3/login-locked.png
design/frames-v0.3/err-msg.png
Modificados : design/styleguide/colors.md
Notas : • Validado contraste 4.5:1 (WCAG AA)
• Debate en PR #7 con Tomás: aprobado.
• Tag creado → `git tag v0.3-rc`.

v0.2-beta (2025-06-15) — Registro seguro
────────────────────────────────────────────────────────
Autor : Tomás Riquelme <to.orellana@duocuc.cl>
Descripción : Captcha en registro, pantalla de
confirmación por correo, copy revisado.
Archivos nuevos : design/frames-v0.2/captcha.png
design/frames-v0.2/confirm-email.png
Modificados : docs/README.md (sección “Seguridad”)
Detalles por cambiar:
✓ Añadir enlace “reenviar código”.
✓ Probar compatibilidad móvil (<375 px).

v0.1.1-hotfix (2025-06-11) — Corrección de naming
────────────────────────────────────────────────────────
Autor : Ramón Hernández
Descripción : Renombrar “User Type” → “Role” en todos
los wireframes para consistencia.
Comando : git mv design/frames-v0.1/user-type.png \
 design/frames-v0.1/role.png
Notas : Issue #2 cerrado.

v0.1-alpha (2025-06-10) — Wireframes base
────────────────────────────────────────────────────────
Autor : Ramón Hernández
Descripción : Login, dashboard Admin, panel Peluquero,
registro Cliente, recuperación de clave.
Archivos nuevos : design/frames-v0.1/\*.png (13 archivos)
Documentación : docs/CHANGELOG.md creado
docs/README.md creado
Acción Git : git tag v0.1-alpha
Pendiente : añadir mensajes de error y loader.

========================================================
Convenciones de Commit
────────────────────────────────────────────────────────
feat: Nueva pantalla / componente
fix: Ajuste visual o de copy
docs: Cambios en markdown o guía de estilos
ref: Reorganización de carpetas sin cambios visuales
hotfix: Corrección urgente en main (shotgun fix)

Notas generales
────────────────────────────────────────────────────────
• Todos los binarios (.png) versionados con Git LFS.
• Cada etiqueta corresponde a una demo enviada a
stakeholders (Mockitt share link registrado en PR).
• PR incluyen checklist: accesibilidad, naming, enlaces.
• Issues vinculados a requisitos: PREFIX-A1, PREFIX-C3…

========================================================
