# 🔓 HacheJota IPTV - APK Liberado

**XTREAM IPTV v2.0.16** - Liberado por HacheJota

## ✅ Modificaciones

- **VIP/Premium eliminado**: Todas las funciones Pro desbloqueadas
- **Anuncios eliminados**: Google AdMob removido completamente
- **Suscripciones eliminadas**: Google Billing removido
- **Compatibilidad corregida**: targetSdkVersion bajado a 34 (Android 14)
- **Split APK corregido**: Removido requiredSplitTypes para instalación directa

## 📋 Cambios técnicos

| Cambio | Detalle |
|--------|---------|
| PLibBridge | shouldCastPremium = siempre false (Pro siempre activo) |
| CastingBridge | getCheckProStatus = siempre true (Pro verificado) |
| OpenScreenBridge | Pantallas de premium/promo deshabilitadas |
| PromoMethodChannel | Flujo de compra de suscripción deshabilitado |
| AndroidManifest | Permisos de ads, billing y AD_ID eliminados |
| targetSdkVersion | 36 → 34 (mejor compatibilidad) |

## 📲 Cómo instalar (IMPORTANTE)

Esta app es un **split APK** (XAPK). Necesitas los 3 archivos APK para que funcione:

1. `com.mca.iptvplayer.new.apk` (base - ya incluido, parcheado)
2. `config.arm64_v8a.apk` (librerías nativas - DE TU XAPK ORIGINAL)
3. `config.hdpi.apk` (recursos de pantalla - DE TU XAPK ORIGINAL)

### Método 1: Usando SAI (Split APKs Installer) - RECOMENDADO

1. Descarga [SAI](https://github.com/Aefyr/SAI) desde Google Play o F-Droid
2. Extrae los archivos `config.arm64_v8a.apk` y `config.hdpi.apk` de tu XAPK original
3. En SAI, selecciona "Instalar APKs"
4. Selecciona los 3 archivos APK juntos
5. ⚠️ **Necesitas firmar todos los APKs con la misma clave** antes de instalar

### Método 2: Usando MT Manager

1. Abre MT Manager
2. Extrae los 3 APKs del XAPK original
3. Reemplaza el APK base con el parcheado
4. Firma TODOS los APKs con la misma clave
5. Instala usando "Instalar como XAPK"

### Método 3: Firmar y fusionar (Avanzado)

1. Descarga el APK base parcheado desde Releases
2. Extrae `config.arm64_v8a.apk` y `config.hdpi.apk` de tu XAPK original
3. Firma TODOS los APKs con la misma clave usando apksigner o MT Manager
4. Empaqueta como XAPK e instala con SAI

## ⚠️ Nota importante sobre firmas

Android requiere que TODOS los split APKs estén firmados con la **misma clave**. 
El APK base parcheado está firmado con una clave nueva, así que necesitas:

1. Firmar también `config.arm64_v8a.apk` y `config.hdpi.apk` con la misma clave
2. Usa MT Manager o apktool para resignar los config APKs

---
*Liberado por HacheJota*
