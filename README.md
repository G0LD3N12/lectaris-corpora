# lectaris-corpora

Paquetes de datos para [Lectaris](https://github.com/G0LD3N12/lectaris). Este repositorio no contiene código: solo sirve los ficheros del release `corpora-v1`.

## Ficheros del release `corpora-v1`

| Fichero | Contenido | Licencia y atribución |
|---|---|---|
| `verbum-hebrew-oshb-2.2-v1.db.zst` | Hebreo WLC con anotaciones morfológicas OSHB 2.2 y datos léxicos STEP Bible | WLC: dominio público. Anotaciones OSHB y datos STEP Bible: CC BY 4.0 (Tyndale House Cambridge). |
| `verbum-semantics-rv1909-v1.db.zst` | Vectores de búsqueda semántica generados desde la Reina-Valera 1909 | Dominio público. |
| `hebrew-glosses-es-*.json` (6 ficheros) | Cachés de glosas españolas del corpus hebreo, derivadas de OSHB y STEP Bible | CC BY 4.0 (fuentes). Las glosas se generaron con asistencia de IA y **no tienen revisión humana**. |

Cada fichero se verifica con su SHA-256 antes de usarse: el manifiesto de la app está en `src-tauri/resources/corpus-packages.json` y los cachés, en `pipeline/hebrew-glosses.lock.json` del repositorio principal.

El corpus ONBV (Open Nueva Biblia Viva, CC BY-SA 4.0) no se publica por ahora.
