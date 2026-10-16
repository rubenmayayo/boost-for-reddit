<p align="center">
  <a href="https://boostforreddit.com"><img src=".github/assets/boost-icon.png" width="128" height="128" alt="Boost for Reddit icon"></a>
</p>

<h1 align="center">Boost for Reddit</h1>

<p align="center">
  An Android client for Reddit by Ruben Mayayo
  <br><br>
  <a href="https://boostforreddit.com">Website</a>
  ·
  <a href="https://github.com/rubenmayayo/boost-for-reddit/releases/latest">Releases</a>
  ·
  <a href="https://www.reddit.com/r/BoostForReddit">r/BoostForReddit</a>
</p>

This repository is the only place where Boost is published. Download signed APKs from [**Releases**](https://github.com/rubenmayayo/boost-for-reddit/releases/latest). The app's source code is not public: the "Source code" archives attached to each release only contain this README.

If you find it useful, you can buy me a coffee:

<a href="https://ko-fi.com/mayayo"><img src="https://storage.ko-fi.com/cdn/kofi2.png?v=3" alt="Buy me a coffee at ko-fi.com" height="36"></a>
<a href="https://paypal.me/mayayo"><img src=".github/assets/paypal-button.png" alt="Donate with PayPal" height="36"></a>

## Requirements

- Android 7.0 or newer
- A Reddit client ID. Since version 1.14.0, Boost needs your own Reddit API client ID. The app shows a step-by-step guide the first time you open it.

## Install

1. Open the [latest release](https://github.com/rubenmayayo/boost-for-reddit/releases/latest) on your phone and download `boost-for-reddit-X.Y.Z.apk` from **Assets**.
2. Open the downloaded file. If Android blocks it, allow **Install unknown apps** for your browser or file manager, then go back and tap **Install**.
3. Open Boost, follow the Reddit setup guide, and log in.

## Coming from Google Play

Boost is no longer available on Google Play, and the old Play version stopped working because Reddit blocked its API access.

The APKs here use the same signing key as the Google Play version. Install the latest one over your current Boost, **without uninstalling**, to keep your settings, saved accounts and local subscriptions. Then open Boost, follow the guide to set up your Reddit client ID, and log in again.

## Update

- **In the app:** Boost checks this page for new releases once a day and shows what's new. Tap **Download** to get the APK, then install it over the current version. You can turn this off in Settings > About > Check for updates.
- **Obtainium:** add `https://github.com/rubenmayayo/boost-for-reddit` to [Obtainium](https://github.com/ImranR98/Obtainium) to get notified of new releases.
- **By hand:** download the new APK and install it over the current version.

Android cannot install an older version over a newer one. To downgrade, uninstall first. Uninstalling deletes your local settings.

## Verify the APK

Every release lists the SHA-256 of the APK and of the signing certificate. The certificate must always be:

```
C5:4B:55:F6:05:36:0A:BB:60:7C:33:09:57:A4:B3:04:E3:6F:62:F0:45:7D:CA:50:52:8E:EE:34:53:AB:28:32
```

Check it with [AppVerifier](https://github.com/soupslurpr/AppVerifier) on the phone, or with the Android SDK:

```sh
apksigner verify --print-certs boost-for-reddit-X.Y.Z.apk
sha256sum boost-for-reddit-X.Y.Z.apk
```

Only install APKs downloaded from this page.

## Changelog

See the [release notes](https://github.com/rubenmayayo/boost-for-reddit/releases) or [CHANGELOG.md](CHANGELOG.md).

## Contact

- Bugs and suggestions: [Issues](https://github.com/rubenmayayo/boost-for-reddit/issues)
- Reddit: [u/rmayayo](https://www.reddit.com/user/rmayayo)
- X: [@rmayayo](https://x.com/rmayayo)

---

## En español

Descarga el APK firmado desde [Releases](https://github.com/rubenmayayo/boost-for-reddit/releases/latest), ábrelo y permite **Instalar apps desconocidas** si Android te lo pide. Necesitas Android 7.0 o superior. Desde la versión 1.14.0 también necesitas tu propio client ID de la API de Reddit; la app te guía al abrirla por primera vez.

Boost ya no está en Google Play, y la versión antigua de Play dejó de funcionar porque Reddit bloqueó su acceso a la API. Si la tienes instalada, instala el APK de aquí encima, **sin desinstalar**: lleva la misma firma y conservarás tus ajustes, cuentas guardadas y suscripciones locales. Después configura tu client ID y vuelve a iniciar sesión.

La app comprueba una vez al día si hay una versión nueva aquí y te avisa (puedes desactivarlo en Ajustes > Acerca de > Buscar actualizaciones). También puedes añadir este repositorio a Obtainium.

Boost es gratis y no tiene anuncios. Si te resulta útil, puedes invitarme a un café en [Ko-fi](https://ko-fi.com/mayayo) o [PayPal](https://paypal.me/mayayo).
