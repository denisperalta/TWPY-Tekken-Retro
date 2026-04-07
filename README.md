
# 🎮 Tekken 5 DR en RPCS3 (Online) — Tekken Warriors PY

Guía completa para instalar **Tekken 5 Dark Resurrection** en RPCS3 y jugar online mediante **RPCN**.

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
- [5. Instalación del juego](#5-instalación-del-juego)
- [6. Configuración Online (RPCN)](#6-configuración-online-rpcn)
- [7. Primer inicio](#7-primer-inicio)
- [8. Recomendaciones](#8-recomendaciones)

---

## 1. Requisitos

Descargar los siguientes archivos:

- RPCS3 → **https://rpcs3.net/** 

Selecciona "Download" en la pantalla principal y luego, en la sección "Windows", selecciona "Download for x64"

- Firmware de PS3 `PS3UPDAT.PUP` → **https://www.playstation.com/en-us/support/hardware/ps3/system-software/** 

Desde aquí, selecciona "Update using a computer", haz clic derecho en "Download PS3 Update" y selecciona "Guardar vínculo como". Tu navegador advertirá que es un archivo potencialmente malicioso, pero acepta la descarga en el gestor de descargas de tu navegador 

![PS3UPDAT.PUP](images/PS3UPDAT.png)

- Tekken 5 DR → **https://romspure.cc/download/tekken-5-dark-resurrection-online-110121/5** 

Espera unos segundos hasta que aparezca el botón amarillo "Download (590.92 M)" y descárgalo.

---

## 2. Estructura de carpetas

Crear una carpeta llamada `PS3` en la ubicación que prefieras y copia las descargas del paso anterior adentro de la misma.

La estructura final al descargar los archivos debe verse así:

```
PS3/
├── RPCS3/
├── PS3UPDAT.PUP
└── Tekken 5/
```

---

## 3. Instalación de RPCS3

1. Haz clic derecho sobre el archivo descargado

2. Selecciona **"Extraer todo"** (Windows 10 / 11)

   ![Extraer todo](<images/Extraer todo Windows 11.png>)

3. Elimina el archivo comprimido

4. Renombra la carpeta a:

```
RPCS3
```

5. Entra en la carpeta y ejecuta:

```
rpcs3.exe
```

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

2. Selecciona el archivo:

   ```
   PS3UPDAT.PUP
   ```

3. Espera a que finalice la instalación

✅ RPCS3 queda listo para usar.

---

## 5. Instalación del juego

1. En RPCS3, En el borde superior del emulador ir a:

   ```
   File > Install Packages
   ```

2. Extrae el archivo del juego:

   * Haz clic derecho en el archivo del juego → **"Extraer todo"**

3. Abre la carpeta `PS3` y verifica que contenga **2 archivos**:

   * Archivo del juego
   * Archivo de licencia

4. Seleccionar ambos archivos y hacer click en **Abrir**

5. Dejamos todos los ajustes en predeterminado, Click en:

   ```
   Install
   ```

6. Esperar a que termine la instalación

   ![RPCS3 Install game](<images/Configuring Game.png>)

✅ Ya puedes jugar **offline**.

---

## 6. Configuración Online (RPCN)

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

6. Verifica con el botón:

   ```
   Test Account
   ```
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

Guardar cambios con:

```
"Apply" y luego "Save"
```

---

## 7. Primer inicio del juego

1. Abre el juego

2. Acepta la descarga de datos adicionales con (**Yes**)

   ![RPCS3 screenshot](<images/Tekken 5 onboarding.png>)

3. Reinicia el emulador una vez que termine la descarga (usa `Alt + F4` o cierra la ventana).

Al abrir el juego nuevamente, no será más necesario descargar esos datos y el juego avanzará normalmente hasta el menú principal. Desde aquí ya pueden modificar los botones a su gusto en Settings o iniciar el online en Online Battle.

---

## 8. Recomendaciones

### ⚠️ Importante

* En el primer acceso a **Online Battle**:

  * Aceptar términos y condiciones

### 🎯 Para evitar errores/crasheos

En Online Battle usar únicamente:

* Create Room
* Custom Battle (Para buscar las salas)
* Profile

---

## 🎮 Listo

Ahora puedes jugar Tekken 5 DR online con la comunidad.

**Get ready for the next battle!**