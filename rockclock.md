# Manual de uso — Rock & Clock

Reloj con la **hora**, el **clima** y los **próximos conciertos** en Chile, en una pantalla táctil que cambia sola cada 10 segundos.

## 1. Si no se conecta solo al WiFi

Si no encuentra tu red, la pantalla dice **"Sin WiFi"** y muestra un **código QR**; el reloj crea su propia red:

1. **Escanea el QR** con el celular, o conéctate a la red **RelojClock** con la clave **12345678** (ambos datos salen en la pantalla).
2. La pantalla dice "Luego abre **192.168.4.1**": abre esa dirección en el navegador si no se abre sola.
3. **Elige tu red** de la lista y escribe la clave. Guarda.

⚠️ Solo redes de **2,4 GHz** (no la "5G"). Mientras el portal está abierto, el reloj sigue probando las redes que conoce y se cierra solo si conecta.

## 2. Volumen

- **Siempre arranca en MUTE.**
- Toca la **esquina inferior izquierda**: cada toque cambia **MUTE → BAJO → NORMAL → MUTE**.

| Icono | Estado |
|---|---|
| Parlante **rojo con X** | MUTE |
| Parlante **verde con flecha ↓** | BAJO |
| Nada | NORMAL |

- **Demo de 30 s:** toca la parte de abajo de un concierto (fuera de las esquinas); otro toque lo corta.
- **A cada hora en punto** suena el demo de uno de los 2 conciertos mostrados (no suena en MUTE).

## 3. Marcar a qué conciertos vas ("voy")

1. **Toca arriba** (zona de la hora) para recorrer la lista hasta el concierto.
2. Toca el **cuadro de la esquina inferior derecha**: queda **verde con un visto**.
3. Aparece la **cuenta regresiva** ("Faltan 21 días") y ese concierto rota entre los 2 que se muestran solos.

Para desmarcarlo, toca el cuadro otra vez. Queda guardado aunque apagues el reloj.

> Solo **arriba** cambia de pantalla. A los 30 s sin tocar vuelve a la secuencia automática.

## 4. Si algo falla

| Lo que ves | Qué hacer |
|---|---|
| Hora en **rojo** | Falló la última descarga de conciertos o de clima. Revisa el WiFi; se arregla sola. |
| `--:--` en lugar de la hora | Aún no hay hora válida: falta internet. |
| **"Desconectado 12min"** en rojo en el clima | Sin internet desde hace esos minutos. Revisa el router; el reloj sigue reintentando. |
| **"Cargando clima…"** o **"Cargando conciertos…"** | Aún no bajó los datos. Si no cambia en unos minutos, revisa el WiFi. |
| **"Sin conciertos próximos"** | La lista no trae conciertos futuros por ahora. |
| **"Sin WiFi"** y un QR | No encuentra tu red: ver el punto 1. |
| **"LittleFS no disponible"** / **"Sube la carpeta data/"** | Faltan los archivos de fuentes e iconos en el reloj: hay que cargarlos desde el computador. |
| Un concierto **no tiene el cuadro de volumen** abajo a la izquierda | El reloj no encontró la microSD: revisa que esté puesta y reinicia el reloj (desconecta y vuelve a conectar el USB). |
| Hay cuadro de volumen pero **no suena** | Mira el icono: parlante rojo = MUTE. Si no es eso, ese concierto aún no tiene demo en la tarjeta. |
| Un demo se corta o no se baja | Usa una tarjeta microSD de marca, de 32 GB o menos, en FAT32. |

Al encender hay **6 s** para elegir tema **oscuro o claro** tocando la pantalla; si no tocas, sigue con el último.
