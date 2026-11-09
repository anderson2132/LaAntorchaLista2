# Seguridad

Si encuentras un problema de seguridad en esta página, repórtalo de forma privada desde la pestaña **Security → Report a vulnerability** de este repositorio. No abras un reporte público.

Medidas aplicadas en la página:
- Política de seguridad de contenido (CSP) restrictiva: solo se ejecuta el script propio (validado por hash) y solo se cargan fuentes de Google Fonts.
- Protección contra incrustación en marcos de otros sitios (clickjacking).
- Sin envío de referer a sitios externos; enlaces externos con `noopener noreferrer`.
- HTTPS obligatorio y página excluida de buscadores (`noindex`, `robots.txt`).
