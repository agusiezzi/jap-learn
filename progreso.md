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
- **Momento puntual con に**: dijo `3年前始めました`; mejor `3年前に始めました` (con に, como `午後に`).
- **それも (también eso) mal usado**: dijo `それも週に2回ぐらいします`; para sumar info: `そして` / `今は`.
- **Años y meses**: dijo `2018に1月と2月で`; falta `年` (`2018年`), los meses llevan `に`, y para un período es `1月から2月まで`.
- **旅行**: dijo `日本の旅行をしました`; natural: `日本を旅行しました` / `日本旅行をしました` / `日本へ旅行に行きました` (sin の).
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
| 始める | はじめる | empezar | 2026-11-05 |
| 〜前 | 〜まえ | hace… / antes de | 2026-11-05 |
| 週に〜回 | しゅうに〜かい | … veces por semana | 2026-11-05 |
| ぐらい | ぐらい | aproximadamente | 2026-11-05 |
| 旅行 | りょこう | viaje, viajar | 2026-11-05 |
| 〜から〜まで | 〜から〜まで | desde… hasta… | 2026-11-05 |
| 本当に | ほんとうに | de verdad, realmente | 2026-11-05 |

## Temas conversados

- Rutina de la mañana: hora de levantarse y desayuno (2026-11-01).
- Planes del día: oficina, volver a la tarde, clase de tenis (2026-11-05).
- Tenis: empezó hace 3 años, juega ~2 veces por semana (2026-11-05).
- Viaje a Japón: enero–febrero de 2018 (2026-11-05).

## Para la próxima vez

- Repasar を (objeto) y ちょうど vs ちょっと. Bloque 1 resuelto (を y ちょうど bien). Reforzar frases completas con verbo en 〜て.
- Bloque 2: ejercicios 1-4 todos correctos (と, 勉強しなければなりません, 夜に, スーパーに行かなければなりません).
- Bloque 3: tenis + viaje a Japón. Ejercicios del bloque 3 resueltos (に con 〜前, 週に3回, そして). Pendientes: 〜から〜まで, 年 en fechas (la última respuesta llegó en romaji, posible dictado/teclado: confirmar). Siguiente pregunta: dónde fue en Japón y qué comió.

## Historial de sesiones

- 2026-11-01 — Se crea el archivo. Bloque 1: rutina de la mañana. Frases correctas: 8時に起きました、コーヒーを飲みました. Ejercicios: を y ちょうど correctos; la traducción la rehízo bien tras autocorregirse (buena señal: se corrige solo).
- 2026-11-05 — Bloque 2: planes del día. Bien: formas て, 会社に行く. A reforzar: なければならない, と vs を, に con momentos del día.
- 2026-11-05 — Ejercicios del bloque 2 resueltos (4/4 bien). Arranca bloque 3: tenis.
- 2026-11-05 — Bloque 3 (tenis + viaje a Japón): bien 週に2回ぐらい, 5年前に日本に行きました, 週に3回スーパーに行きます. A reforzar: に con 〜前, 年/月 en fechas, 〜から〜まで, 旅行 como verbo.
