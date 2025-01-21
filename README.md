# CompAppTP
TP computacion applicada
# Trabajo Práctico Integrador

## Participantes del equipo
- Federico Fabrykant

## Infraestructura armada
- **Sistema operativo:** Debian GNU/Linux.
- **Servicios configurados:**
  - Apache: Con soporte PHP (sirve `index.php` y `logo.png`).
  - MariaDB: Base de datos cargada desde el script `db.sql`.
  - SSH: Configurado con clave pública.
- **Almacenamiento:**
  - `/www_dir`: 3 GB, para el servidor web.
  - `/backup_dir`: 6 GB, para los backups generados.
- **Red:**
  - **IP estática:** `192.168.18.21`
  - **Puerta de enlace:** `192.168.18.1`
  - Configuración DNS: `8.8.8.8`, `8.8.4.4`.

## Diagrama topológico
El diagrama de la infraestructura armada se encuentra en el archivo `diagrama_topologia.png`.

## Instrucciones para reproducir
1. Descargar y descomprimir los archivos comprimidos en sus respectivas ubicaciones:
   - `/root`
   - `/etc`
   - `/opt`
   - `/var`
   - `/www_dir`
   - `/backup_dir`
2. Configurar la red según el archivo `/etc/network/interfaces`.
3. Reiniciar los servicios instalados (Apache, MariaDB).
4. Verificar la conectividad SSH y el funcionamiento del servidor web.

---
