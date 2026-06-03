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

## 📲 Instalación

1. Descarga `HacheJota.apk` desde la sección de [Releases](../../releases)
2. Habilita "Orígenes desconocidos" en tu dispositivo
3. Instala el APK

## ⚠️ Nota

Este APK es la versión base (sin librerías nativas de ABI). Para funcionamiento completo en dispositivos ARM/ARM64, necesitarás también los split APKs de ABI.

---
*Liberado por HacheJota*
