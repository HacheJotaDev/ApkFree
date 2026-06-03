# HacheJota APK Free

Reproductor IPTV basado en Xtream Codes API - **Sin VIP, Sin Anuncios, 100% Libre**

Desarrollado por **HacheJota**

## Caracteristicas

- TV en Vivo con categorias
- Peliculas (VOD) con detalles
- Series con temporadas y episodios
- Soporte para Xtream Codes API y listas M3U
- Reproductor de video integrado con controles completos
- Busqueda de contenido
- **Sin anuncios, sin restricciones VIP**
- Interfaz oscura moderna
- Notificaciones push (FCM)

## Conexion

### Xtream Codes
Ingresa tu servidor, usuario y contrasena de tu servicio IPTV.

### Lista M3U
Pega la URL de tu lista M3U para cargar los canales y peliculas.

## Descargar APK

Ve a la seccion [Releases](https://github.com/HacheJotaDev/ApkFree/releases) para descargar la ultima version de `HacheJota.apk`.

### Instalacion
1. Descarga `HacheJota.apk` desde la ultima release
2. Activa "Origenes desconocidos" en tu dispositivo Android
3. Instala el APK

## Compilacion manual

```bash
flutter pub get
flutter build apk --release
```

El APK se generara en `build/app/outputs/flutter-apk/app-release.apk`

## Build automatico

Cada push a la rama `main` activa GitHub Actions que:
1. Compila el APK en modo release
2. Lo renombra a `HacheJota.apk`
3. Crea una release automatica con el APK adjunto
