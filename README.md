# Chat cifrado offline en HTML

Este proyecto contiene dos herramientas HTML que permiten intercambiar mensajes cifrados usando un PIN compartido. No dependen de servidores ni instalaciones: todo ocurre localmente en el navegador.

## ¿Para qué sirve?

Permite enviar mensajes privados por cualquier medio (Telegram, correo, WhatsApp, foros, etc.) sin que el contenido pueda ser leído por terceros. Solo necesitas acordar un PIN con la otra persona.

## Cómo funciona

1. Ambos usuarios acuerdan un **PIN**.
2. Cada uno introduce el PIN en su HTML y genera un **hash** para verificar que coinciden.
3. Una vez verificado, se habilita el área de cifrado.
4. Escribes un mensaje y el HTML genera un **código cifrado**.
5. Envías ese código por cualquier canal.
6. La otra persona lo pega en su HTML, introduce el PIN y obtiene el mensaje original.

## Archivos incluidos

- `modelo1.html` — Primer diseño del sistema de cifrado/descifrado.
- `modelo2.html` — Segundo diseño con la misma lógica.

## Seguridad

- Todo el cifrado ocurre en el navegador.
- No se envían datos a ningún servidor.
- La seguridad depende de la fortaleza del PIN elegido.

## Uso

1. Descarga los archivos desde este repositorio.
2. Ábrelos en tu navegador.
3. Introduce el PIN, verifica el hash y empieza a cifrar/descifrar mensajes.

## Licencia

Puedes usar y modificar este proyecto libremente.
