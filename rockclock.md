# Manual de uso — Rock & Clock

Reloj con la **hora**, el **clima** y los **próximos conciertos** en Chile, en una pantalla táctil que cambia sola cada 10 segundos.

## 1. Si no se conecta solo al WiFi

Si no encuentra tu red, el reloj crea la suya y muestra un **código QR**:

1. **Escanea el QR** con el celular (o conéctate a la red **RelojClock**, clave **12345678**).
2. Abre el navegador en **192.168.4.1** si no se abre solo.
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

| Problema | Qué hacer |
|---|---|
| Hora en **rojo** | Falló una descarga: revisa el WiFi, se arregla sola. |
| `--:--` | Aún no hay hora: falta internet. |
| "Desconectado N min" | Sin internet; revisa el router. |
| Aparece la red **RelojClock** y un QR | No encuentra tu WiFi: ver el punto 1. |
| **No suena** | Mira el icono: parlante rojo = MUTE. Revisa que la microSD esté puesta y que el concierto tenga demo. |
| "microSD no encontrada" tras cargar firmware | Desconecta y vuelve a conectar el cable USB. |
| Un demo se corta o no baja | Usa una tarjeta microSD de marca, de 32 GB o menos, en FAT32. |

Al encender hay **6 s** para elegir tema **oscuro o claro** tocando la pantalla; si no tocas, sigue con el último.
