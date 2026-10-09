# WaveType

Dicta en cualquier app de tu Mac: pulsa un atajo, habla y el texto aparece donde está el cursor. También graba notas de voz y transcribe reuniones, todo en tu Mac si usas los modelos locales.

Este repositorio publica las **versiones** de WaveType y recibe los **reportes de problemas y sugerencias**. El código de la app no está aquí.

## Descargar

Descarga el último `WaveType-<versión>.dmg` desde [Releases](https://github.com/JotaMiller/wave-type-releases/releases/latest), ábrelo y arrastra WaveType a *Aplicaciones*.

Requisitos: macOS 26 o posterior. Los modelos descargables (Parakeet) requieren un Mac con Apple silicon.

> Si macOS no deja abrir la app la primera vez, ve a *Ajustes del Sistema → Privacidad y seguridad* y pulsa «Abrir igualmente».

Después de instalarla, WaveType se actualiza sola: avisa en la barra de menús cuando hay una versión nueva.

## Reportar un problema o sugerir algo

Abre un [issue](https://github.com/JotaMiller/wave-type-releases/issues/new/choose). Incluye la versión (Configuración → General) y, si puedes, los pasos para reproducirlo. **No pegues API keys ni texto privado dictado.**

---

*Para quien publica:* `appcast.xml` es el canal de actualizaciones de Sparkle y se sirve desde GitHub Pages en `https://jotamiller.github.io/wave-type-releases/appcast.xml`. Lo genera `scripts/make-appcast.sh` en el repositorio de la app; no se edita a mano.
