# progreso.md — Práctica de japonés

> Este archivo lo lee Claude al inicio de cada sesión y lo actualiza (commit + push) después de cada bloque de práctica.

## Reglas de la práctica (para Claude)

- Explicaciones en **español rioplatense**; la práctica en **japonés**.
- **Furigana** en los kanji (formato `漢字（かんじ）`). Nada de romaji.
- Estilo Schliemann, en cada bloque:
  1. Pregunta de la vida real en japonés, acorde al nivel.
  2. El usuario responde escribiendo en japonés.
  3. Respuesta natural reformulando lo que dijo bien.
  4. Frases del usuario corregidas con una explicación breve (en español).
  5. Ejercicios cortos para reforzar.
  6. Actualizar este archivo y hacer commit + push.
- Guardar **después de cada bloque**, no solo al final.
- Ramas: este archivo vive en la rama principal (`main`). Si no se puede pushear a `main`, usar `claude/japanese-conversation-project-v1hydp` y avisar al usuario.

## Nivel actual

- Ya usa correctamente と, に (momentos del día) y 〜なければなりません en ejercicios guiados; falta que le salga solo en frases libres.
- Maneja bien la forma て para encadenar acciones (働いて、帰って、食べて).
- Intermedio-bajo (autoevaluado, sin test formal; aprox. N4–N3 bajo).
- Se ajustará con la práctica.

## Errores frecuentes

- **Partícula を vs と**: dijo `バナナと食べました` (と = «con»); lo correcto es `バナナを食べました` (を marca lo que se come/bebe).
- **ちょっと vs ちょうど**: dijo `ちょっと8時` (= «un poco»); para «justo/en punto» es `ちょうど8時`.
- **でも (pero) mal usado**: usó `でも` sin contraste; para sumar acciones: `それから` / `〜て、〜`. Para «solo»: `だけ`.
- **〜てみる**: dijo `飲んでみました` (= «probé a tomar»); para una acción normal alcanza con `飲みました`. Usar `〜てみる` solo si es probar algo nuevo.
- **Potencial vs obligación**: dijo `行けなければなります`; «tener que ir» es `行かなければなりません` (forma ない → なければ + なりません). `行ける` = «poder ir».
- **と (con) vs を**: dijo `チームを話して`; hablar con alguien es `チームと話して`.
- **Tiempo con に**: dijo `午後で帰って`; para momentos del día es `午後に帰って`.
- **〜とか y 〜ので colgantes**: usó `〜とか` para encadenar acciones (alcanza con `〜て`; `〜とか` es «cosas como…») y cerró con `ありますので` sin oración principal. Mejor `あるので、〜` o terminar en `あります`.
- Tendencia: `今日の朝` → más natural `今朝（けさ）`.

## Vocabulario nuevo

| Palabra | Lectura | Significado | Fecha |
|---|---|---|---|
| 今朝 | けさ | esta mañana | 2026-11-01 |
| ちょうど | ちょうど | justo, en punto | 2026-11-01 |
| だけ | だけ | solo, nada más | 2026-11-01 |
| それから | それから | y después | 2026-11-01 |
| もう一度 | もういちど | una vez más | 2026-11-01 |
| 〜てみる | 〜てみる | probar a hacer algo | 2026-11-01 |
| 〜なければなりません | 〜なければなりません | tener que… | 2026-11-05 |
| 働く | はたらく | trabajar | 2026-11-05 |
| 午後 | ごご | tarde (PM) | 2026-11-05 |
| 特に | とくに | especialmente | 2026-11-05 |
| 〜ので | 〜ので | porque / ya que | 2026-11-05 |

## Temas conversados

- Rutina de la mañana: hora de levantarse y desayuno (2026-11-01).
- Planes del día: oficina, volver a la tarde, clase de tenis (2026-11-05).

## Para la próxima vez

- Repasar を (objeto) y ちょうど vs ちょっと. Bloque 1 resuelto (を y ちょうど bien). Reforzar frases completas con verbo en 〜て.
- Bloque 2: ejercicios 1-3 correctos (と, 勉強しなければなりません, 夜に). Falta el 4: スーパーに行かなければなりません (traducción sin responder).
- Bloque 3: el tenis (hobbies/deportes). Pendiente de respuesta.

## Historial de sesiones

- 2026-11-01 — Se crea el archivo. Bloque 1: rutina de la mañana. Frases correctas: 8時に起きました、コーヒーを飲みました. Ejercicios: を y ちょうど correctos; la traducción la rehízo bien tras autocorregirse (buena señal: se corrige solo).
- 2026-11-05 — Bloque 2: planes del día. Bien: formas て, 会社に行く. A reforzar: なければならない, と vs を, に con momentos del día.
- 2026-11-05 — Ejercicios del bloque 2 resueltos (3/3 contestados bien, el 4 quedó sin responder). Arranca bloque 3: tenis.
