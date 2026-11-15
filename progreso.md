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
- 2026-11-14: escribió un párrafo todo en japonés (sin romaji), con causa y secuencia (それで, そして); aparecen lógica narrativa y vocabulario de viaje. Sigue fallando la gramática de partículas y ある/いる.
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
- **Lugar de la acción con で** (error repetido): dijo `会社に働きます` dos veces; correcto `会社で働きます`. に = destino/existencia (`会社に行きます`).
- **Falta 年 en los años** (error repetido): `2018に`, `2022日本へ`; siempre `2022年に`.
- **Orden de horas**: escribió `5時から9時まで` queriendo decir 9 a 5; en japonés se dice en el orden real: `9時から5時まで`.
- **Redundancia**: `日本へ、日本旅行をしました`; basta `日本へ旅行に行きました` o `日本旅行をしました`.
- **年 otra vez** (3.ª vez): `2018の旅行`; siempre `2018年`.
- **Ortografía**: `友どち` → `友だち`; `友どちといった` → `友だちと行った` (と + 行く).
- **観光 vs 環境**: en romaji escribió `Kankyo` (環境 = medio ambiente); «hacer turismo» es `観光（かんこう）`.
- **それも** (2.ª vez) usado como «y además»; usar `それから` / `そして`.
- **思い出す**: dijo `〜旅行と思い出します`; «recordar» lleva を: `素晴らしい旅行を思い出します`; «creo que fue» es `〜だったと思います`; simple: `本当に素晴らしい旅行でした`.
- **Cerrar frases enumerando**: `冬の食べ物を食べたラーメンと…` → `冬の食べ物を食べました。ラーメンやセブンイレブンの食べ物です。`
- **Romaji**: varias respuestas llegaron en romaji (posible dictado por voz o teclado). Regla del proyecto: furigana, no romaji; pedir kana/kanji.
- **選べなければならない** (error repetido, ver 行けなければ): `選べなければなりません`; correcto `選ばなければなりませんでした` (verbo en forma ない → なければ; `選べる` = poder elegir).
- **に vs で con destino** (repetido): `ディズニーランドで行って` → `ディズニーランドに行って`.
- **ある vs いる**: `大仏がいた`, `神社がいた` → `ありました` (objetos/lugares = ある; personas/animales = いる).
- **い-adjetivo + sustantivo**: `近いな町` → `近い町` (sin な).
- **Negar un deseo/acción**: `行きない` no existe; `行きたくなかった` (no quería ir) o `行かなかった`.
- **外 vs 他**: `外の町` (= afuera) → `他（ほか）の町` (otra ciudad).
- **時間があった**: «pasarla bien» = `いい時間を過ごしました` o `楽しかったです`.
- **〜と思う**: `鎌倉と思う` → `鎌倉だと思います`. También mezcla estilo plano y です/ます en un mismo texto: elegir uno.
- **犬があって** (ejercicio): usó `ある` para un animal y `〜てと` para unir; correcto `公園に犬がいて、木があります`.
- **Verbo + sustantivo sin の**: dijo `違うのところ`; correcto `違うところ` (el verbo/adjetivo modifica directo al sustantivo; sin の).
- **Orden en frases relativas**: dijo `一番ところで行きたいのは熊野`; correcto `一番行きたいところは熊野です`.
- **Palabras en katakana mal copiadas**: `コード` (code/acorde) por `古道（こどう）`; `熊野古道（くまのこどう）`.
- **について**: dijo `熊野古道のことを読みました`; para «leer sobre» usar `〜について読みました`.
- **それも** (3.ª vez, ya recurrente): usado como «y además»; usar `それから` / `そして` / `あと`.
- **Posición de 本当に**: `鎌倉本当も` → `鎌倉にも本当にまた行きたいです`.
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
| 熊野古道 | くまのこどう | Kumano Kodo (ruta de peregrinación) | 2026-11-15 |
| 有名 | ゆうめい | famoso | 2026-11-15 |
| 最近 | さいきん | últimamente | 2026-11-15 |
| 人気がある | にんきがある | ser popular | 2026-11-15 |
| 歩く | あるく | caminar | 2026-11-15 |
| 〜について | 〜について | acerca de, sobre | 2026-11-15 |
| 違う | ちがう | diferente | 2026-11-15 |
| 鎌倉 | かまくら | Kamakura | 2026-11-14 |
| 大仏 | だいぶつ | Gran Buda | 2026-11-14 |
| 神社 | じんじゃ | santuario sintoísta | 2026-11-14 |
| 選ぶ | えらぶ | elegir | 2026-11-14 |
| 一人で | ひとりで | solo/a | 2026-11-14 |
| 過ごす | すごす | pasar (el tiempo) | 2026-11-14 |
| ある日 | あるひ | un día (cierto día) | 2026-11-14 |
| 他 | ほか | otro | 2026-11-14 |
| 理由 | りゆう | motivo | 2026-11-14 |
| 観光 | かんこう | turismo | 2026-11-14 |
| 友だち | ともだち | amigo/a | 2026-11-14 |
| ずっと | ずっと | todo el tiempo, siempre | 2026-11-14 |
| たとえば | たとえば | por ejemplo | 2026-11-14 |
| 思い出す | おもいだす | recordar | 2026-11-14 |
| 素晴らしい | すばらしい | maravilloso | 2026-11-14 |
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
- Viaje a Japón: enero–febrero de 2018 y otro viaje en 2022 (2026-11-05).
- Viaje futuro: quiere volver a Japón, caminar el Kumano Kodo; también Tokio, Kioto y Kamakura (2026-11-15).
- Mejor ciudad: Kamakura (Gran Buda, santuarios), fue solo mientras su amigo iba a Disneylandia (2026-11-14).
- Itinerario 2018: Tokio, Osaka, Kioto, Hokkaido (Sapporo, Hakodate), Morioka, Nikko, Hiroshima, Nagasaki; invierno; ramen y konbini (2026-11-14).

## Para la próxima vez

- Repasar を (objeto) y ちょうど vs ちょっと. Bloque 1 resuelto (を y ちょうど bien). Reforzar frases completas con verbo en 〜て.
- Bloque 2: ejercicios 1-4 todos correctos (と, 勉強しなければなりません, 夜に, スーパーに行かなければなりません).
- Bloque 3: tenis + viaje a Japón. Ejercicios del bloque 3 resueltos (に con 〜前, 週に3回, そして). Pendientes: 〜から〜まで, 年 en fechas (una respuesta llegó en romaji, posible dictado/teclado; después reescribió en japonés). Contó el viaje de 2018 (Tokio, Osaka, Kioto, Hokkaido, Hiroshima, Nagasaki; invierno, Japan Rail Pass). Contó por qué Kamakura fue lo mejor (fue solo a ver el Gran Buda y santuarios mientras su amigo iba a Disneylandia). Ejercicios resueltos: 2023年に一人で鎌倉に行った ✅; 勉強しなければならない (falta el pasado: ならなかった/なりませんでした); 犬が*ある* ✗ (犬はいる). Bloque 4 (viajes futuros): quiere volver a Japón, ir a Kumano Kodo, y repetir Tokio, Kioto y Kamakura. Ejercicios pendientes: 〜について, orden de 一番行きたいところは…, それから. Reforzar: いる/ある, pasado de なければならない.

## Historial de sesiones

- 2026-11-01 — Se crea el archivo. Bloque 1: rutina de la mañana. Frases correctas: 8時に起きました、コーヒーを飲みました. Ejercicios: を y ちょうど correctos; la traducción la rehízo bien tras autocorregirse (buena señal: se corrige solo).
- 2026-11-05 — Bloque 2: planes del día. Bien: formas て, 会社に行く. A reforzar: なければならない, と vs を, に con momentos del día.
- 2026-11-05 — Ejercicios del bloque 2 resueltos (4/4 bien). Arranca bloque 3: tenis.
- 2026-11-05 — Bloque 3 (tenis + viaje a Japón): bien 週に2回ぐらい, 5年前に日本に行きました, 週に3回スーパーに行きます. A reforzar: に con 〜前, 年/月 en fechas, 〜から〜まで, 旅行 como verbo.
- 2026-11-07 — Repaso de ejercicios del bloque 3: `会社で働きます` y `年` en fechas siguen fallando; reforzar con ejercicios en la próxima sesión.
- 2026-11-14 — Bloque 3 (viaje de 2018): párrafo largo, ambicioso, parte en romaji. Pendiente de reforzar: 年, 観光, それから en vez de それも, 思い出す.
- 2026-11-14 — Bloque 3 (Kamakura): párrafo largo todo en japonés; errores nuevos: ある/いる, 近いな, 外/他, 選べなければ (repetido), に/で destino.
- 2026-11-14 — Ejercicios Kamakura: 1/3 perfecto (2023年に一人で…), 1 casi (falta el pasado), 1 a repasar (いる/ある con animales).
- 2026-11-15 — Bloque 4 (viajes futuros): bien 〜たい, 人気がある, 熊野古道と言います, 歩きたい. A reforzar: sin の tras verbo, orden de la frase relativa, について, それも→それから.
