# OVIEDO BANK

Banco ficticio para el roleplay de OVIEDO RP.

## Publicación con GitHub Pages

1. Crea un repositorio público llamado `oviedo-bank`.
2. Sube `index.html`, `README.md` y `.nojekyll` a la raíz del repositorio.
3. Entra en **Settings → Pages**.
4. En **Build and deployment**, selecciona **Deploy from a branch**.
5. Selecciona la rama `main` y la carpeta `/ (root)`.
6. Guarda y espera a que GitHub Pages publique la web.

## Imagen de marca

El logotipo aparece en la cabecera, en el inicio y como favicon del sitio.

## Funciones de esta versión

- Alta de cuentas ficticias.
- Saldo y número de cuenta.
- Transferencias entre cuentas del mismo navegador.
- Ingresos y pagos manuales.
- Historial de movimientos.
- Panel local de administración.
- Exportación de copia de seguridad.

## Aviso importante

Esta versión es una demostración de front-end. Los datos se guardan en el almacenamiento local del navegador (`localStorage`), por lo que no se sincronizan entre dispositivos ni entre miembros. El PIN de administración del prototipo está en el código y no proporciona seguridad real. No introducir datos personales, contraseñas ni información bancaria real.

Para una versión multiusuario se necesita un backend con autenticación, base de datos y permisos seguros.
