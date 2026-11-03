# Pomodoro 25/5 con notificaciones en el reloj

PWA estática: 25 min de trabajo, 5 min de descanso, máximo 4 pomodoros
(T1 → D1 → T2 → D2 → T3 → D3 → T4 → fin). Avisa al iniciar cada trabajo y cada descanso.

## Uso
Publicada con GitHub Pages en `https://<usuario>.github.io/github-slideshow/pomodoro/`
(requiere HTTPS para notificaciones). Prueba rápida: añade `?rapido=1` (1 min = 1 s).

## Notificaciones en el reloj
- **iPhone + Apple Watch** (iOS 16.4+): Safari → Compartir → «Añadir a pantalla de inicio», abrir desde el icono
  y activar notificaciones. iOS refleja la notificación en el Watch cuando el iPhone está bloqueado.
- **Android + Wear OS / Galaxy Watch**: las notificaciones de Chrome se reenvían al reloj.
- **ntfy (imprescindible en iPhone)**: los navegadores móviles suspenden JavaScript con la pantalla apagada, así que los avisos
  locales pueden retrasarse hasta que abras la app. Si escribes un tema de ntfy, al iniciar se programan en
  ntfy.sh todos los avisos de la sesión; instala la app ntfy, suscríbete al tema y permite sus notificaciones en el reloj.
  Limitación: pausar o reiniciar no cancela avisos ya programados en ntfy.
