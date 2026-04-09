# 🎮 Tekken en RPCS3 (Online) — Tekken Warriors PY

Guía completa para instalar juegos de **Tekken** en RPCS3 y jugar online mediante **RPCN**.

## ⚖️ Descargo de responsabilidad legal

Este tutorial es únicamente para fines educativos. La descarga e instalación de juegos implica derechos de autor; asegúrate de poseer una copia legal del juego antes de proceder. No nos responsabilizamos por el uso indebido de esta información.

> ⚠️ Esta guía está pensada para mantener una estructura ordenada. Se recomienda seguirla exactamente.

---

## 📑 Índice

- [Descargo de responsabilidad legal](#⚖️-descargo-de-responsabilidad-legal)
- [1. Requisitos](#1-requisitos)
- [2. Estructura de carpetas](#2-estructura-de-carpetas)
- [3. Instalación de RPCS3](#3-instalación-de-rpcs3)
- [4. Instalación del Firmware](#4-instalación-del-firmware)
- [5. Configuración Online (RPCN)](#5-configuración-online-rpcn)
- [6. Instalación del juego](#6-instalación-del-juego)
  - [6.1 Tekken 5 DR](#61-tekken-5-dr)
  - [6.2 Tekken 6](#62-tekken-6)
  - [6.3 Tekken Tag Tournament 2](#63-tekken-tag-tournament-2)
- [FAQ](#faq)

---

## 1. Requisitos base

Descargar los siguientes archivos:

- RPCS3 → **https://rpcs3.net/** 

Selecciona "Download" en la pantalla principal y luego, en la sección "Windows", selecciona "Download for x64"

- Firmware de PS3 `PS3UPDAT.PUP` → **https://www.playstation.com/en-us/support/hardware/ps3/system-software/** 

Desde aquí, selecciona "Update using a computer", haz clic derecho en "Download PS3 Update" y selecciona "Guardar vínculo como". Tu navegador advertirá que es un archivo potencialmente malicioso, pero acepta la descarga en el gestor de descargas de tu navegador 

![PS3UPDAT.PUP](images/PS3UPDAT.png)

- El juego en sí, en los pasos de cada juego en específico se encuentra el link de descarga.

---

## 2. Estructura de carpetas

Crear una carpeta llamada `PS3` en la ubicación que prefieras y copia las descargas del paso anterior adentro de la misma.

La estructura final al descargar los archivos debe verse así:

```
PS3/
├── RPCS3/
└── PS3UPDAT.PUP
```

---

## 3. Instalación de RPCS3

1. Haz clic derecho sobre el archivo descargado

2. Selecciona **"Extraer todo"** (Windows 10 / 11)

   ![Extraer todo](<images/Extraer todo Windows 11.png>)

3. Elimina el archivo comprimido

4. Renombra la carpeta a `RPCS3`

5. Entra en la carpeta y ejecuta `rpcs3.exe`

6. En la pantalla de bienvenida de RPCS3:

   * Desmarca **"Show at startup"** (opcional)
   * Marca **"I have read the Quickstart guide"** (requerido)
   * Haz clic en **Continue**

   ![RPCS3 Onboarding](<images/RPCS3 Quickstart.png>)

---

## 4. Instalación del Firmware

1. En el menú superior:

   ```
   File > Install Firmware
   ```

2. Selecciona el archivo `PS3UPDAT.PUP`

3. Espera a que finalice la instalación

✅ RPCS3 queda listo para usar.

---

## 5. Configuración Online (RPCN)

### Crear cuenta RPCN

1. En el borde superior del emulador ir a:

   ```
   Manage > Network Services > RPCN
   ```

2. En **Account**:

   * Haz clic en **Create Account**
   * Completa en cada formulario:

     * Usuario
     * Contraseña
     * Email válido

3. Confirma con **Yes**

4. Ingresa el **Token** recibido por email

5. Haz clic en **OK**

6. Verifica con el botón `Test Account`, si aparece la imagen con el texto "Your account is valid!" el proceso se terminó correctamente.

   ![RPCS3 screenshot](<images/Account valid.png>)

---

### Configurar red

En el borde superior del emulador ir a:

```
Configuration > Network
```

Configurar de la siguiente manera:

| Opción         | Valor     |
| -------------- | --------- |
| Network Status | Connected |
| Enable UPNP    | Enabled   |
| PSN Status     | RPCN      |
| Country        | Paraguay  |

![RPCS3 screenshot](<images/Network Settings.png>)

Guardar cambios con `"Apply" y luego "Save"`

---

## 6. Instalación del juego

### 6.1 Tekken 5 DR

1. Tekken 5 DR → **https://drive.proton.me/urls/TACT6M3FYR#szwv6YH19THH** 

2. Añádelo a la carpeta PS3 creada en los pasos anteriores. La estructura debería verse así:

   ```
   PS3/
   ├── RPCS3/
   ├── PS3UPDAT.PUP
   └── Tekken 5/
   ```

3. Extrae el archivo del juego:

   * Haz clic derecho en el archivo del juego → **"Extraer todo"**

4. Abre la carpeta extraída y verifica que contenga **2 archivos**:

   * Archivo del juego
   * Archivo de licencia

5. En RPCS3, En el borde superior del emulador ir a:

   ```
   File > Install Packages
   ```

6. Seleccionar ambos archivos dentro de la carpeta extraída y hacer click en **Abrir**

7. Dejamos todos los ajustes en predeterminado, Click en `Install`

8. Esperar a que termine la instalación

   ![RPCS3 Install game](<images/T5 Configuring Game.png>)

9. Abre el juego

10. Acepta la descarga de datos adicionales con (**Yes**)

   ![RPCS3 screenshot](<images/Tekken 5 onboarding.png>)

11. Reinicia el emulador una vez que termine la descarga (usa `Alt + F4` o cierra la ventana).

Al abrir el juego nuevamente, no será más necesario descargar esos datos y el juego avanzará normalmente hasta el menú principal. Desde aquí ya pueden modificar los botones a su gusto en Settings o iniciar el online en Online Battle.

✅ **Tekken 5 DR** instalado y listo para jugar online.

### ⚠️ Importante

* En el primer acceso a **Online Battle**:

  * Aceptar términos y condiciones

### 🎯 Para evitar errores/crasheos

En Online Battle usar únicamente:

* Create Room
* Custom Battle (Para buscar las salas)
* Profile

---

### 6.2 Tekken 6

⚠️ *Cuidado con la descarga de archivos maliciosos, asegúrate que el archivo sea Tekken 6 y pese aproximadamente 12 GB* ⚠️ 

1. Tekken 6 → **https://romspure.cc/download/tekken-6-2-18888-22595/5** 

> Espera unos segundos hasta que aparezca el botón amarillo "Download" y descárgalo.

2. Añádelo a la carpeta PS3 creada en los pasos anteriores. La estructura debería verse así:

   ```
   PS3/
   ├── RPCS3/
   ├── PS3UPDAT.PUP
   └── Tekken 6/
   ```

3. Extrae el archivo del juego:

   * Haz clic derecho en el archivo del juego → **"Extraer todo"**

4. Copiar el archivo .iso recién descargado adentro de la carpeta del emulador RPCS3, en la carpeta `"games"`

5. Descargar la actualización del juego: **https://drive.proton.me/urls/KAXRA8S6R4#D3aYF8yFbsOG**

6. Abre la carpeta extraída y verifica que contenga **1 archivo**:

   * Archivo de la actualización

7. En RPCS3, En el borde superior del emulador ir a:

   ```
   File > Install Packages
   ```

8. Seleccionar ambos archivos dentro de la carpeta extraída y hacer click en **Abrir**

9. Dejamos todos los ajustes en predeterminado, Click en `Install`

10. Esperar a que termine la instalación

   ![RPCS3 Install game](<images/T6 Configuring Game.png>)

✅ **Tekken 6** instalado y listo para jugar online.

---
### 6.3 Tekken Tag Tournament 2

⚠️ *Cuidado con la descarga de archivos maliciosos, asegúrate que el archivo sea Tekken Tag Tournament 2 y pese aproximadamente 17 GB* ⚠️ 

1. Tekken Tag Tournament 2 → **https://romspure.cc/download/tekken-tag-tournament-2-22601/1** 

> Espera unos segundos hasta que aparezca el botón amarillo "Download" y descárgalo.

2. Añádelo a la carpeta PS3 creada en los pasos anteriores. La estructura debería verse así:

   ```
   PS3/
   ├── RPCS3/
   ├── PS3UPDAT.PUP
   └── Tekken Tag Tournament 2/
   ```

3. Extrae el archivo del juego:

   * Haz clic derecho en el archivo del juego → **"Extraer todo"**

4. Copiar el archivo .iso recién descargado adentro de la carpeta del emulador RPCS3, en la carpeta `"games"`

5. Descargar la actualización y DLC del juego: **https://drive.proton.me/urls/QJJH4P2PX8#nYDYCDrPlMfe**

6. Abre la carpeta extraída y verifica que contenga **3 archivos**:

   * Archivo de la actualización
   * Archivo de los DLC
   * Online Pass

7. En RPCS3, En el borde superior del emulador ir a:

   ```
   File > Install Packages
   ```

8. Seleccionar **solamente los archivos DLC y Online Pass** dentro de la carpeta extraída y hacer click en **Abrir**

9. Dejamos todos los ajustes en predeterminado, Click en `Install`

10. Iniciar el juego normalmente, terminar una batalla (Puede ser en Arcade Battle) y cerrar el juego

11. En RPCS3, En el borde superior del emulador ir a:

      ```
      File > Install Packages
      ```

12. Dejamos todos los ajustes en predeterminado, Click en `Install`

13. Seleccionar **solamente los archivos de actualización** dentro de la carpeta extraída y hacer click en **Abrir**

14. Esperar a que termine la instalación

   ![RPCS3 Install game](<images/TTT2 Configuring Game.png>)

✅ **Tekken Tag Tournament 2** instalado y listo para jugar online.

---

## 🎮 Listo

Ahora puedes jugar Tekken Retro online con la comunidad.

**Get ready for the next battle!**

---

## FAQ

### ¿Es legal descargar e instalar estos juegos?

Esta guía es únicamente para fines educativos. La descarga e instalación de juegos implica derechos de autor; asegúrate de poseer una copia legal del juego antes de proceder. No nos responsabilizamos por el uso indebido de esta información.

### ¿Qué hacer si el juego no inicia?

- Verifica que el firmware del PS3 esté instalado correctamente.
- Asegúrate de que la configuración de red esté correcta para el modo online.
- Revisa que todos los archivos del juego estén instalados.

### ¿Cómo conectar con otros jugadores?

- Crea una cuenta RPCN siguiendo el paso 5.
- En el juego, ve a Online Battle y selecciona Create Room o Custom Battle.

### ¿El emulador es compatible con mi PC?

RPCS3 requiere una PC con rendimiento medio. Verifica los requisitos mínimos en el sitio oficial de RPCS3.

### ¿Dónde puedo reportar problemas?

Puedes contactar a Rushador Cuidadoso de Tekken Warriors PY para soporte adicional.