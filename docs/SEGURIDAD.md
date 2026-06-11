# Seguridad

Este proyecto es una guía local para aprender y configurar entornos de desarrollo. No debe usarse como caja fuerte de credenciales reales.

## No subas información privada

Antes de subir cambios a GitHub, revisa que no estés incluyendo:

- Contraseñas reales.
- Tokens.
- Llaves SSH.
- Archivos `.env`.
- Respaldos SQL reales.
- Datos de clientes.
- IPs privadas sensibles.
- Capturas con información personal.
- JSON locales con datos tuyos.

## Cuidado con comandos peligrosos

Lee dos veces antes de ejecutar comandos con:

- `sudo`
- `rm`
- `chmod`
- `chown`
- `mkfs`
- `dd`
- cambios en `/etc`
- cambios en Apache
- cambios en MariaDB
- reglas de firewall

## Recomendación para principiantes

Cuando no estés seguro, prueba primero en una carpeta de práctica.

Ejemplo:

```bash
mkdir -p "$HOME/practica-linux"
cd "$HOME/practica-linux"
```

Así puedes experimentar sin tocar archivos importantes.
